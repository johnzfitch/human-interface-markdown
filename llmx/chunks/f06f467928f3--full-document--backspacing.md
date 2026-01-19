---
chunk_index: 2045
ref: "f06f467928f3"
id: "f06f467928f3fd3365831af6559f87420b4470fe521cfa78daabeb8c392717b7"
slug: "full-document--backspacing"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2570, 2578]
token_estimate: 138
content_sha256: "bdc040c298d0df8d360851aea939c078afbeddd9523036ce2fd84cacc0cb555d"
compacted: false
heading_path: ["Backspacing"]
symbol: null
address: null
asset_path: null
---

# Backspacing

When the user presses the Backspace or Delete key, one of two things happens:

- D If the current selection is an insertion point, the character to the left of the insertion point is deleted.
- If the current selection is one or more characters, it's deleted. (This is equivalent to choosing Clear from the Edit menu.)

In either case, the insertion point replaces the deleted character (or characters) in the document. The deleted characters don't go into the Clipboard, but the user can undo the deletion by immediately choosing Undo.