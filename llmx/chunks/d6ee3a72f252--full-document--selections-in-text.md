---
chunk_index: 2891
ref: "d6ee3a72f252"
id: "d6ee3a72f25210919bad28b3edaf7926b27024b8b83f8d32ad946f1455f6ffe3"
slug: "full-document--selections-in-text"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4564, 4577]
token_estimate: 332
content_sha256: "97884d7dc545737cec511c7e4ed86d76c9ce76eaaca10965b8001cb34c4fb2c9"
compacted: false
heading_path: ["Selecting","Selections in Text"]
symbol: null
address: null
asset_path: null
---

## Selections in Text

In most applications, the user is required at some point to edit text. The principle of consistency (both within and among applications) requires that text be selected and edited in a consistent way, regardless of where it appears.

A block of text is a string of characters. A text selection is a substring of this string, which can have any length from zero characters to the whole block. Each of the text selection methods selects a different kind of substring. Figure 10-19 shows different kinds of text selections.

**Figure 10-19** Text selections

![](images/_page_316_Figure_3.jpeg)

The insertion point is a zero-length text selection. The user establishes the location of the insertion point by clicking somewhere in the text. The insertion point then appears at the nearest character boundary. If the user clicks anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character.

The insertion point shows where text will be inserted when the user begins typing, or where the contents of the Clipboard will be pasted. As each character is typed, the insertion point is moved to the right of that character.