---
chunk_index: 2025
ref: "7722a248ec8f"
id: "7722a248ec8f8bc277b1d57ab224e5ee3d4f7ac7f857364504113d43362bf226"
slug: "full-document--moving-the-insertion-point"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2187, 2192]
token_estimate: 188
content_sha256: "eeb2b0df7e98e8bdd2f094c04e2fdde4cd5c91d7059be786f591ee8a955537db"
compacted: false
heading_path: ["Moving the insertion point"]
symbol: null
address: null
asset_path: null
---

# Moving the insertion point

The Left Arrow and Right Arrow keys move the insertion point one character left and right, respectively. Up Arrow and Down Arrow move the insertion point up and down one line, respectively.

During vertical movement of the insertion point, horizontal screen position is maintained in terms of screen pixels, not characters. (Character boundaries seldom line up vertically when proportional fonts are used.) When the insertion point moves to <sup>a</sup> new line, move it slightly left or right, to the nearest character boundary on the new line. During successive movements up or down, the application should keep the insertion point as close as possible to the original horizontal position as it moves from line to line.