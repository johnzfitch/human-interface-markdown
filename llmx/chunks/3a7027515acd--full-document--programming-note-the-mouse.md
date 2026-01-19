---
chunk_index: 3976
ref: "3a7027515acd"
id: "3a7027515acd956b8946eab9a09d5fbae57a78e7327541f9f673835aee9f089f"
slug: "full-document--programming-note-the-mouse"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [679, 684]
token_estimate: 133
content_sha256: "004935fdc81d3ad6d78d39ae5a181199fe6bc259151fe8ed2de9fc51c8f81e4f"
compacted: false
heading_path: ["*Introduction*","**Clicking**","**Multiple-Clicking**","**Programming Note: The Mouse**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: The Mouse**

All the controls provided by the Application Kit automatically turn the mouse actions they recognize (such as clicks) into the result specified by the programmer (such as bringing up a pane!). The Text object also automatically receives and reacts to mouse actions such as clicks, double-clicks, triple-clicks, and dragging actions.

If you implement a custom control or a custom content area, you'll probably have to write code to handle the mouse actions that the control or area responds to.