---
chunk_index: 1430
ref: "15b45dfaa1c1"
id: "15b45dfaa1c10e2ae4adbe39fbc9d0a73e6360d6cda825ff77e618acb1df69f1"
slug: "full-document--returns-are-accepted-only-if-the-merchandise"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [2040, 2057]
token_estimate: 383
content_sha256: "2e45aa7612ce479988692a3469ff1dde779d613a563a6fc4a2442e26796ecee4"
compacted: false
heading_path: ["Intelligent cut and paste","Returns are accepted only if the merchandise is damaged."]
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