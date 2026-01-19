---
chunk_index: 4077
ref: "05025cf14356"
id: "05025cf14356f134ee11f58b8d89d62e4d97f6fcbe342809af6d238f5d7c6be0"
slug: "full-document--floating-panels"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1629, 1643]
token_estimate: 335
content_sha256: "11a197c58e026245b7a6b062105df2bcf6a503193da29bd6412f8552d3c2d144"
compacted: false
heading_path: ["5 *Panels*","**Exceptions to Ordinary Panel Behavior**","**Persisting Panels**","**Floating Panels**"]
symbol: null
address: null
asset_path: null
---

#### **Floating Panels**

Ordinary panels are normally in the same tier as standard windows. Sometimes, though, it's useful to have a panel float above all other standard windows and ordinary panels. For example, a small panel containing a palette of drawing tools is most useful if it floats above the application's other windows. An example of a palette is below.

![](images/_page_93_Picture_2.jpeg)

A panel should be allowed to float above standard windows only if it passes all four of the following tests:

- It's oriented to the mouse rather than the keyboard. Thus a panel that can become the key window should not be made a floating panel, unless it becomes the key window only when the user is ready to type (see "Becoming the Key Window" earlier in this chapter).
- It's important that the panel remain visible while the user works in the application's standard windows. This test is passed if the user must frequently move the cursor from a standard window to the panel and back again (as for a tool palette) or the panel gives information relevant to the user's actions in the standard window (as in some inspector panels).
- It's small enough not to obscure much of what's behind it.
- It doesn't persist (remain on-screen) when the application is deactivated.

Thus, panels float for some of the same reasons that menus do.