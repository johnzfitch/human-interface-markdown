---
chunk_index: 892
ref: "1f9d7a662608"
id: "1f9d7a662608104b57fa0cd7cc548d612bc2e17e3518048b946b74427526a1ad"
slug: "full-document--backspacing"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1193, 1201]
token_estimate: 127
content_sha256: "515818ab6ebd2921e2031eb3c5898be384ce212c1852f1b00f1cd316cffe5c08"
compacted: false
heading_path: ["Inserting Text","**Backspacing**"]
symbol: null
address: null
asset_path: null
---

## **Backspacing**

When the user presses the Backspace key, one of two things happens:

- <sup>o</sup> If the current selection is one or more characters, it's deleted.
- <sup>o</sup> If the current selection is an insertion point, the character to the left of the insertion point is deleted.

In either case, the insertion point replaces the deleted character (or characters) in the document. The deleted characters don't go into the Clipboard, but the deletion can be undone by immediately choosing Undo.