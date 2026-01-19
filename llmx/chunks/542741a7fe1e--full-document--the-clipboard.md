---
chunk_index: 1366
ref: "542741a7fe1e"
id: "542741a7fe1e79444ff298f742066bf8693137cc9b7db6fba7276a85d3e922b5"
slug: "full-document--the-clipboard"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1287, 1300]
token_estimate: 377
content_sha256: "cf4de4baf65be697136101a39e8923ab3604903661d5a3e84ca582004f9a33a2"
compacted: false
heading_path: ["About MacPaint...","The Clipboard"]
symbol: null
address: null
asset_path: null
---

## The Clipboard

The Clipboard holds whatever is cut or copied from a document. Its contents stay intact when the user changes documents, opens a desk accessory, or leaves the application. An application can show the contents of the Clipboard in a window and can choose whether to have the Clipboard window open or closed when the application starts up.

The Clipboard window looks like a document window. The user can see its contents but cannot edit them. In other respects, the Clipboard window behaves like any other window.

Every time the user performs a Copy on the current selection, a copy of the selection replaces the previous contents of the Clipboard. The previous contents of the Clipboard remain available in case the user chooses Undo.

The Clipboard is available to all applications that support Cut, Copy, and Paste. The user can see the Clipboard window by choosing Show Clipboard from the Edit menu. If the Clipboard window is already showing, the user can hide it by clicking the close box or choosing Hide Clipboard in the Edit menu. (Show Clipboard and Hide Clipboard are a single toggled item.)

Because the content of the Clipboard doesn't change when the user moves from one application to another, or when the user opens a desk accessory, the Clipboard is used for transferring data among compatible applications and desk accessories.

If the Clipboard file is moved from one disk to another, the contents move with it, replacing any existing Clipboard file on the target disk.