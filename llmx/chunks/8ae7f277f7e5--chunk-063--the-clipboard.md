---
chunk_index: 752
ref: "8ae7f277f7e5"
id: "8ae7f277f7e5f947e0701ed98f9974f3a7e59ba93fe111215b07d49699118cdb"
slug: "chunk-063--the-clipboard"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_063.md"
kind: "markdown"
lines: [33, 39]
token_estimate: 399
content_sha256: "16098c48b2e63cb9b69981c253e2d467c0fa6780c96b0d68b60c93611f657a32"
compacted: false
heading_path: ["*Page Setup*","Print","Quit","The Clipboard"]
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