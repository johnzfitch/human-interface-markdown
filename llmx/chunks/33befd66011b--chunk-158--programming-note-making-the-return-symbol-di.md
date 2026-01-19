---
chunk_index: 3791
ref: "33befd66011b"
id: "33befd66011b05ca48b7ecd145e9567018314016b3f1b6e01e81e8e3c2f556f7"
slug: "chunk-158--programming-note-making-the-return-symbol-di"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_158.md"
kind: "markdown"
lines: [23, 25]
token_estimate: 128
content_sha256: "75502f7dab3ff477912b027074d7210543dc99bf6d63590fe0ffea7230a49304"
compacted: false
heading_path: ["Choosing the Button's Result","**Choosing the Button's Image or Label**","Programming Note: Making the Return Symbol Disappear"]
symbol: null
address: null
asset_path: null
---

#### Programming Note: Making the Return Symbol Disappear  
All Application Kit panels automatically remove the Return symbol when the panel isn't the key window. Attention panels created with NXRunAlertPanel() and its related functions also remove the Return symbol automatically.  
For other panels, you need to explicitly remove and add the Return symbol for the appropriate button. You can do so in your implementation of the windowDidResignKey: and windowDid8ecomeKey: delegate methods of the Window class.