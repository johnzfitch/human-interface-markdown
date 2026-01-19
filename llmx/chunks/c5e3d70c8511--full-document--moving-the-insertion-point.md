---
chunk_index: 1408
ref: "c5e3d70c8511"
id: "c5e3d70c8511f1fe506cef8754ac231a045150c326387d94d864fc6c2d22b2fc"
slug: "full-document--moving-the-insertion-point"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1633, 1638]
token_estimate: 186
content_sha256: "a4008fb6860d6fc8a23dc7ce6f81ceda1dae0c334347e60e2c4269bc4530767d"
compacted: false
heading_path: ["Moving the insertion point"]
symbol: null
address: null
asset_path: null
---

# Moving the insertion point

The Left Arrow and Right Arrow keys move the insertion point one character left and right, respectively. Up Arrow and Down Arrow move the insertion point up and down one line, respectively.

During vertical movement of the insertion point, horizontal screen position is maintained in terms of screen pixels, not characters. (Character boundaries seldom line up vertically when proportional fonts are used.) When the insertion point moves to a new line, move it slightly left or right, to the nearest character boundary on the new line. During successive movements up or down, the application should keep the insertion point as close as possible to the original horizontal position as it moves from line to line.