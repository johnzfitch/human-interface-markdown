---
chunk_index: 2875
ref: "f79d8d571ba2"
id: "f79d8d571ba21f5c4442b722f58841a1d7c7b8c001371142433ce126aa6d0fbe"
slug: "full-document--moving-the-insertion-point"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4361, 4366]
token_estimate: 186
content_sha256: "afb88521f49cac4345af26215177d11beb16339a987ea45ff00aebafd92fda5b"
compacted: false
heading_path: ["The Keyboard","Arrow Keys","Appropriate Uses for the Arrow Keys","Moving the Insertion Point"]
symbol: null
address: null
asset_path: null
---

#### Moving the Insertion Point

The Left Arrow and Right Arrow keys move the insertion point one character left and right respectively. Up Arrow and Down Arrow move the insertion point up and down one line respectively.

During vertical movement of the insertion point, horizontal screen position is maintained in terms of screen pixels, not characters. (Character boundaries seldom line up vertically when proportional fonts are used.) When the insertion point moves to a new line, move it slightly left or right, to the nearest character boundary on the new line. During successive movements up or down, the application should keep the insertion point as close as possible to the original horizontal position as it moves from line to line.