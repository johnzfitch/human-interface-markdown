---
chunk_index: 1427
ref: "6fddc442c270"
id: "6fddc442c27099562bd5e019d4a985c5dce56af432baec7d8d8d8a80787be3aa"
slug: "full-document--backspacing"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [2017, 2025]
token_estimate: 138
content_sha256: "d51946b02b2e881a112bee1802a722d6d374dc215102d12a9bbbd8414752aeb6"
compacted: false
heading_path: ["**Inserting Text**","Backspacing"]
symbol: null
address: null
asset_path: null
---

## Backspacing

When the user presses the Backspace or Delete key, one of two things happens:

- If the current selection is an insertion point, the character to the left of the insertion point is deleted.
- If the current selection is one or more characters, it's deleted. (This is equivalent to chossing Clear from the Edit menu.)

In either case, the insertion point replaces the deleted character (or characters) in the document. The deleted characters don't go into the Clipboard, but the user can undo the deletion by immediately choosing Undo.