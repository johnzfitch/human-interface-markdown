---
chunk_index: 2445
ref: "8cc36a631303"
id: "8cc36a631303ce6345cb12ed9c5aefc3e807d28401bbdc90fd41ce013145ee6d"
slug: "chunk-213--moving-the-insertion-point"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_213.md"
kind: "markdown"
lines: [12, 14]
token_estimate: 186
content_sha256: "20fee7017545972ed804978eb44b209d89bc32b9b2210a665a0ed6c14d5684ea"
compacted: false
heading_path: ["Appropriate Uses for the Arrow Keys","Moving the Insertion Point"]
symbol: null
address: null
asset_path: null
---

#### Moving the Insertion Point  
The Left Arrow and Right Arrow keys move the insertion point one character left and right respectively. Up Arrow and Down Arrow move the insertion point up and down one line respectively.  
During vertical movement of the insertion point, horizontal screen position is maintained in terms of screen pixels, not characters. (Character boundaries seldom line up vertically when proportional fonts are used.) When the insertion point moves to a new line, move it slightly left or right, to the nearest character boundary on the new line. During successive movements up or down, the application should keep the insertion point as close as possible to the original horizontal position as it moves from line to line.