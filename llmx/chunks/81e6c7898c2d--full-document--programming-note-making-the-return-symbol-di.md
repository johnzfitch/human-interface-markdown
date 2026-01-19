---
chunk_index: 4158
ref: "81e6c7898c2d"
id: "81e6c7898c2dfbd1c6fc4b8a19ba48d93f4279a746e6fff4e7279eb4c1ea4db4"
slug: "full-document--programming-note-making-the-return-symbol-di"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2671, 2676]
token_estimate: 128
content_sha256: "c6133c985e9ef9f936d7d6807f2c269705ede88b3d89034f1e7e3ec84bc1c6b8"
compacted: false
heading_path: ["7! *Controls*","Implementing Buttons","Choosing the Button's Result","Programming Note: Making the Return Symbol Disappear"]
symbol: null
address: null
asset_path: null
---

#### Programming Note: Making the Return Symbol Disappear

All Application Kit panels automatically remove the Return symbol when the panel isn't the key window. Attention panels created with NXRunAlertPanel() and its related functions also remove the Return symbol automatically.

For other panels, you need to explicitly remove and add the Return symbol for the appropriate button. You can do so in your implementation of the windowDidResignKey: and windowDid8ecomeKey: delegate methods of the Window class.