---
chunk_index: 3609
ref: "cf0ad8173cab"
id: "cf0ad8173cabad02ca2ebb28210c2b696519b59321e400c6122f95bae7da6d0b"
slug: "chunk-036--programming-note-the-mouse"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_036.md"
kind: "markdown"
lines: [8, 10]
token_estimate: 134
content_sha256: "5c1dd2e2f8374faee656cddfa081f5a3ee8907becbca8219534089bb37b13beb"
compacted: false
heading_path: ["**Multiple-Clicking**","**Programming Note: The Mouse**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: The Mouse**  
All the controls provided by the Application Kit automatically turn the mouse actions they recognize (such as clicks) into the result specified by the programmer (such as bringing up a pane!). The Text object also automatically receives and reacts to mouse actions such as clicks, double-clicks, triple-clicks, and dragging actions.  
If you implement a custom control or a custom content area, you'll probably have to write code to handle the mouse actions that the control or area responds to.