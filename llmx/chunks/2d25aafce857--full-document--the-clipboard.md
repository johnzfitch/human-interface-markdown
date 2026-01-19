---
chunk_index: 924
ref: "2d25aafce857"
id: "2d25aafce85772bb2eb47f8e1fab3e62f49ce85a36897c68481561b31f27cbe0"
slug: "full-document--the-clipboard"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1562, 1575]
token_estimate: 398
content_sha256: "5b5a0b798f57d57d78a6cf37445e92e18412daf604230b03126c41a3d8a19ad4"
compacted: false
heading_path: ["Standard Menus","The Apple **Menu**","*Revert to Saved*","The Clipboard"]
symbol: null
address: null
asset_path: null
---

#### The Clipboard

The Clipboard holds whatever is cut or copied from a document. Its contents stay intact when the user changes documents, opens a desk accessory, or leaves the application. An application can show the contents of the Clipboard in a window and can choose whether to have the Clipboard window open or closed when the application starts up.

The Clipboard window looks like a document window. The user can see its contents but cannot edit them. In most other respects, the Clipboard window behaves just like any other window.

Every time the user performs a Copy on the current selection, a copy of the selection replaces the previous contents of the Clipboard. The previous contents of the Clipboard remain available in case the user chooses Undo.

Althought it appears to the user that there's only one Clipboard, each application can create its own. It is available to all applications that support Cut, Copy, and Paste. The user can see the Clipboard window by choosing Show Clipboard from the Edit menu. If the window is already showing, it's hidden by clicking the close box or choosing Hide Clipboard in the Edit menu. (Show Clipboard and Hide Clipboard are a single toggled item.)

Because the content of the Clipboard doesn't change when the user moves from one application to another, or when the user opens a desk accessory, the Clipboard is used for transferring data among compatible applications and desk accessories.

If the Clipboard file is moved from one disk to another, the contents move with it, replacing any existing Clipboard file on the target disk.