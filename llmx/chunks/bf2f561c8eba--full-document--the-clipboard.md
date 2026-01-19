---
chunk_index: 1981
ref: "bf2f561c8eba"
id: "bf2f561c8eba4131857bfd1036b68c29ecbbf86f4137ef475c02b19e778bdb76"
slug: "full-document--the-clipboard"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1759, 1772]
token_estimate: 386
content_sha256: "23c0a6a9886d801362d46fad0205c7d84f88360459a3aa0dd99a8e5e75ca8041"
compacted: false
heading_path: ["The Edit menu","The Clipboard"]
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