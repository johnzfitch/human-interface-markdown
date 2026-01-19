---
chunk_index: 4106
ref: "4b2d3464fa52"
id: "4b2d3464fa52be536538937a34dc038dbca207830bc3f39fa2f32f480dafee63"
slug: "full-document--submenus"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1989, 1996]
token_estimate: 177
content_sha256: "a40a1073d62c2422dbe7eadc063e6fd6ca09913809b583b1a6682e7507f18911"
compacted: false
heading_path: ["5 *Panels*","**Submenus**"]
symbol: null
address: null
asset_path: null
---

## **Submenus**

The main menu is the only menu in an application that isn't a submenu. Every other menu is a submenu of another menu, which is its *supermenu* in the application's hierarchy of menus.

Each submenu is associated with a particular command in its supermenu. The submenu becomes visible and *attaches* to its supermenu when the user chooses the command that it's associated with.

The user can drag from a controlling command into a submenu to choose one of the submenu's commands. As long as the mouse button is held down, the submenu remains visible and the controlling command stays highlighted. But once the mouse button goes up and the command has been executed, the submenu disappears.