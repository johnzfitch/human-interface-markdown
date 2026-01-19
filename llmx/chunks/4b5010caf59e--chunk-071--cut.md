---
chunk_index: 1737
ref: "4b5010caf59e"
id: "4b5010caf59ef21b03cdac3b0fa0eecd1038b9867d98a9f2c6551371595b665e"
slug: "chunk-071--cut"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_071.md"
kind: "markdown"
lines: [35, 38]
token_estimate: 198
content_sha256: "bd8b3f236a6f896cf84fd2a9176da91870a43c1032cef1ce161c55ee39d71385"
compacted: false
heading_path: ["The Clipboard","Undo","Cut"]
symbol: null
address: null
asset_path: null
---

#### Cut  
The user chooses Cut either to delete the current selection or to move it. A move is eventually completed by choosing Paste.  
When the user chooses Cut, the application removes the current selection from the document and puts it in the Clipboard, replacing the Clipboard's previous contents. The place where the selection used to be becomes the new selection; the visual implications of this vary among applications. For example, in text, the new selection is an insertion point; in an array, it's an empty but highlighted cell. If the user chooses Paste immediately after choosing Cut, the document isjust as it was before the Cut.  
The Apple-X key combination is reserved as a keyboard substitute for the Cut operation in the Edit menu and should be used for no other purpose.