---
chunk_index: 4021
ref: "14e29f759664"
id: "14e29f7596649a1b99255d5a568eacb89fdd2d27cb525500f3faa920cc9432e8"
slug: "full-document--control-arrow-combinations"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1118, 1125]
token_estimate: 280
content_sha256: "f7b3e6634c2e6e41c5f6bb46499cd8b1c696bcd96bc5c3b67d091c38ccf98b9a"
compacted: false
heading_path: ["*Introduction*","**Control-Arrow Combinations**"]
symbol: null
address: null
asset_path: null
---

## **Control-Arrow Combinations**

Modified by the Control key, the arrow keys move the insertion point to the edge of the current display. The left arrow key puts the insertion point before the first visible character on the line where the current selection begins, and the right arrow key puts it after the last visible character on the line where the current selection ends.

The up arrow key positions the insertion point in the first visible line of the display, directly above the beginning of the current selection. The down arrow key puts the insertion point in the last visible line, directly below the end of the current selection.

When the insertion point is already at the edge of the currently visible display, the Control-arrow combination that would otherwise move it to that edge first scrolls the display (by the amount of a page scroll), then moves the insertion point to the edge of the new display. Once the insertion point reaches the beginning of a line, the right arrow key won't move it further (for example, to another line). The left arrow key won't move it once it reaches the end of a line.