---
chunk_index: 589
ref: "7acff77592d6"
id: "7acff77592d63db36aad0aaaed976d8a2e114f83f1f98fbde42f3c0a8195cb2c"
slug: "full-document--forward-delete"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1937, 1945]
token_estimate: 142
content_sha256: "14988c57e69d723afa5d9219846f0ded17fdddddb9efec3017b66720a0dad63e"
compacted: false
heading_path: ["Forward Delete"]
symbol: null
address: null
asset_path: null
---

# Forward Delete

When the user presses Control-F, one of two things happens:

- If the current selection is one or more characters, it's deleted (exactly as with Delete).
- If the current selection is an insertion point, the character to the right of the insertion point is deleted. (The cursor in a MouseText-based program is a blinking underscore. Since the underscore itself is to the right of the insertion-point, the effect is that the character immediately above the underscore is deleted.)

In both cases, the deleted characters don't go into the Clipboard.