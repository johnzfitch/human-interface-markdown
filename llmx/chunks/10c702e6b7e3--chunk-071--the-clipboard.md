---
chunk_index: 1735
ref: "10c702e6b7e3"
id: "10c702e6b7e3ae4e9b71299880855ce3a4f556547771b440b0a1da7662da9c6c"
slug: "chunk-071--the-clipboard"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_071.md"
kind: "markdown"
lines: [18, 24]
token_estimate: 387
content_sha256: "1aeb05c743dd3f71ffa1fe2098debb9299a33f521de16e17ac2faabd9cf58146"
compacted: false
heading_path: ["The Clipboard"]
symbol: null
address: null
asset_path: null
---

#### The Clipboard  
The Clipboard holds whatever is cut or copied from a document. Its contents stay intact when the user changes documents, opens <sup>a</sup> desk accessory, or leaves the application. An application can show the contents of the Clipboard in <sup>a</sup> window and can choose whether to have the Clipboard window open or closed when the application starts up.  
The Clipboard window looks like a document window. The user can see its contents but cannot edit them. In other respects, the Clipboard window behaves like any other window.  
Every time the user performs a Copy on the current selection, a copy of the selection replaces the previous contents of the Clipboard. The previous contents of the Clipboard remain available in case the user chooses Undo.  
The Clipboard is available to all applications that support Cut, Copy, and Paste. The user can see the Clipboard window by choosing Show Clipboard from the Edit menu. If the Clipboard window is already showing, the user can hide it by clicking the close box or choosing Hide Clipboard from the Edit menu. (Show Clipboard and Hide Clipboard are a single toggled item.)  
Because the content of the Clipboard doesn't change when the user moves from one application to another, or when the user opens <sup>a</sup> desk accessory, the Clipboard is used for transferring data among compatible applications and desk accessories.  
If the Clipboard file is moved from one disk to another, the contents move with it, replacing any existing Clipboard file on the target disk.