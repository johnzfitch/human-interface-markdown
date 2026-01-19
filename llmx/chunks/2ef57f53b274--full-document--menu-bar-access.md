---
chunk_index: 2769
ref: "2ef57f53b274"
id: "2ef57f53b2742afc9e6906bf63f78940fed2ff33f79766e7c07ca79db42d498a"
slug: "full-document--menu-bar-access"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2899, 2902]
token_estimate: 280
content_sha256: "cc11a66d85f57e2042640c3d226634745b9ff6a39790d575c7a7765065513cfd"
compacted: false
heading_path: ["Modeless Dialog Boxes","Modeless Dialog Box Behaviors","Menu Bar Access"]
symbol: null
address: null
asset_path: null
---

#### Menu Bar Access

Although system software leaves the Help, Keyboard, and Application menus and their commands enabled, it does nothing else to manage the menu bar when you display a modeless dialog box. Your application is responsible for providing access to the rest of the menus in your menu bar as appropriate. Disable only those menus that contain commands that are invalid in the current context; if the modeless dialog box includes editable text items, enable the Cut, Copy, Paste, and Clear commands (and any other appropriate commands) in the Edit menu. For example, when a modeless dialog box used with a search-and-replace command appears, the application should allow access to the Edit menu to assist the user with the editable text items; it should also allow access to the File menu so that the user can open another file for searching and replacing text. However, your application should disable other menus if the commands in those menus cannot be used inside the active modeless dialog box. After your application removes a modeless dialog box, always restore the menus to their previous states.