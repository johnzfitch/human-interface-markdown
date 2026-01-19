---
chunk_index: 2339
ref: "216c2c73ef84"
id: "216c2c73ef841a29ab5cb1ea9beb40c57da9a9cd7466d0abeaad22f59d703dc1"
slug: "chunk-130--menu-bar-access"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_130.md"
kind: "markdown"
lines: [3, 4]
token_estimate: 280
content_sha256: "4d99ddff84f283ac6bce7873e1256b62b97c17db491b1792ea0f1e29c31e0edd"
compacted: false
heading_path: ["Menu Bar Access"]
symbol: null
address: null
asset_path: null
---

#### Menu Bar Access  
Although system software leaves the Help, Keyboard, and Application menus and their commands enabled, it does nothing else to manage the menu bar when you display a modeless dialog box. Your application is responsible for providing access to the rest of the menus in your menu bar as appropriate. Disable only those menus that contain commands that are invalid in the current context; if the modeless dialog box includes editable text items, enable the Cut, Copy, Paste, and Clear commands (and any other appropriate commands) in the Edit menu. For example, when a modeless dialog box used with a search-and-replace command appears, the application should allow access to the Edit menu to assist the user with the editable text items; it should also allow access to the File menu so that the user can open another file for searching and replacing text. However, your application should disable other menus if the commands in those menus cannot be used inside the active modeless dialog box. After your application removes a modeless dialog box, always restore the menus to their previous states.