---
chunk_index: 450
ref: "3ac8acbd1ff7"
id: "3ac8acbd1ff79b45f4c0deb118d5a5e24c41cdf043d796031bc87d178eb46787"
slug: "chunk-119"
path: "marker/1985 Apple II Human Interface Guidelines/chunks/chunk_119.md"
kind: "markdown"
lines: [1, 17]
token_estimate: 560
content_sha256: "26330dd1a1d68c17aefc908c1defaffbd63d0bd81f95f2e82b9c62a7907e3bcb"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 119 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 536 -->
An application that lets the user select a word by double-clicking should also see to it that the user doesn't regret using this feature. The only way to do this is by providing "intelligent" cut and paste.  
To understand why this feature is necessary, consider the following sequence of events in an application that doesn't provide it:  
- 1. A sentence in the user's document reads: "Returns are only accepted if the merchandise is damaged." The user wants to change this to: "Returns are accepted only if the merchandise is damaged."
- 2. The user selects the word "only" by double-clicking. The letters are highlighted, but not either of the adjacent spaces.
- The user chooses Cut, clicks just before the word "if", and chooses Paste.
- 4. The sentence now reads: "Returns are accepted onlyif the merchandise is damaged." To correct the sentence, the user has to remove a space between "are" and "accepted", and add one between "only" and "if". At this point he or she may be wondering why Apple computers are supposed to be easier to use than other computers.  
If an application supports intelligent cut and paste, the rules to follow are:  
- If the user selects a word or a range of words, highlight the selection, but not any adjacent spaces.
- When the user chooses Cut, if the character to the left of the selection is a space, discard it.
- When the user chooses Paste, if the character to the left of the current selection isn't a space, add a space. If the character to the right of the current selection isn't a punctuation mark or a space, add a space. Punctuation marks include the period, comma, exclamation point, question mark, apostrophe, colon, semicolon, and quotation mark.  
This feature makes more sense if the application supports the full definition of a word (as detailed above under "Selecting a Word"), rather than the definition of a word as anything between two spaces.  
These rules apply to any selection that's one or more whole words, whether it was chosen with a double-click or as a range selection.  
Figure 23 shows some examples of intelligent cut and paste.  
1/15/85 Tognazzini  
TEXT EDITING  
105