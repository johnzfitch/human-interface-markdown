---
chunk_index: 4033
ref: "078ab8de6764"
id: "078ab8de676451f42c4710fed800e62be25a9aa140facf664d039d4c54cb150c"
slug: "full-document--closing"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1232, 1245]
token_estimate: 281
content_sha256: "e276733a54e08219ad6e5fb77731e141293526c111450f72f8c32e304ddd132d"
compacted: false
heading_path: ["The Window Interface to Applications","**Closing**"]
symbol: null
address: null
asset_path: null
---

## **Closing**

The close button removes a window from the screen. What this means depends on the type of window:

Menus and panels

A menu that's closed is removed from the screen, but the user retains a way to retrieve it quickly through a command in another menu. Panels that are closed are retrievable in the same way. (See Chapter 6 for more information on menus.)

When a panel that was closed is returned to the screen, it assumes its former size and location, and it retains its former state. From the user's point of view, and programmatically, it's the same panel that was closed.

Standard windows

Closing a standard window usually removes it from the application as well as from the screen. From the user's point of view, the same window can't necessarily be made visible again. The application might create a new window with the same title and a similar display, but there might be differences. The selection might not be preserved, and the new window won't necessarily be located in the same place or have the same shape as the old one, especially if the user had moved or resized the window that was closed.