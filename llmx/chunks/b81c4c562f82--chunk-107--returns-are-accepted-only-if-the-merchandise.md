---
chunk_index: 1198
ref: "b81c4c562f82"
id: "b81c4c562f82d738e93fb96c2fec637855e6a482fa09d01916c19a6425b6851f"
slug: "chunk-107--returns-are-accepted-only-if-the-merchandise"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/chunks/chunk_107.md"
kind: "markdown"
lines: [6, 16]
token_estimate: 384
content_sha256: "343b542fe57933926ad9f2361dc27881f3021233a4a582ff4cb54cff45fed0ac"
compacted: false
heading_path: ["Returns are accepted only if the merchandise is damaged."]
symbol: null
address: null
asset_path: null
---

#### Returns are accepted only if the merchandise is damaged.  
- 2. The user selects the word *only* by double-clicking. The letters are highlighted, but neither of the adjacent spaces is highlighted.
- 3. The user chooses Cut, clicks just before the word *if*, and chooses Paste.
- 4. The sentence now reads  
Returns are accepted onlyif the merchandise is damaged.  
Note the extra space between *are* and *accepted*, and the lack of a space between *only* and *if*. To correct the sentence, the user has to remove the extra space between *are* and *accepted*, and add one between *only* and *if*. At this point he or she may be wondering why people bother with computers at all.  
If an application supports intelligent cut and paste, the rules are:  
- If the user selects a word or a range of words, the selection itself is highlighted, but spaces adjacent to the selection are not highlighted.
- When the user chooses Cut, if the character to the left of the selection is a space, cut the space along with the selection. If the character to the left of the selection is not a space, but the character to the right of the selection is a space, cut that space along with the selection.
- When the user chooses Paste, if the character to the left or right of the current selection is part of a word, insert a space before pasting.  
If the left or right end of a text selection is a word, follow these rules at that end, regardless of whether there's a word at the other end. Figure 65 shows an example of intelligent cut and paste.