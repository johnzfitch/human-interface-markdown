---
chunk_index: 4051
ref: "c30b49dc2003"
id: "c30b49dc20032d9c892503e4e5eab2b1ab02955f555b1da10a104c57c043ae54"
slug: "full-document--implementing-standard-windows"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1436, 1441]
token_estimate: 194
content_sha256: "8ed7d5e27c455aec59bdb243e8bddcdb18dbe98a0c7538abaaa62f25e406961c"
compacted: false
heading_path: ["The Window Interface to Applications","**Implementing Standard Windows**"]
symbol: null
address: null
asset_path: null
---

## **Implementing Standard Windows**

Standard windows are the most widely used type of window and the principal type for all applications. If an application lets the user edit files, each file should be displayed in a separate standard window. If the application is a game, the game board should be in a standard window, and if the application is a simple accessory like a clock, the clock face should occupy a small standard window of its own.

Every standard window has a title bar; most also have window controls—a resize bar, close button, and miniaturize button. This section discusses choosing the window's title and everything that you need to implement when the window controls are present. It also describes cases when it's acceptable to omit the window controls.