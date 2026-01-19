---
chunk_index: 267
ref: "52f75c9aa6ae"
id: "52f75c9aa6aefb290d8865c7e2f43bc4d4f32281e9a2c7eb7b07c7332580b3e3"
slug: "chunk-019"
path: "marker/1983 Lisa UI Guidelines/chunks/chunk_019.md"
kind: "markdown"
lines: [1, 7]
token_estimate: 277
content_sha256: "94fd806f936aa0570a0789a8b19dcf269dc410bfa4fe73b1620036fd42f51fb6"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 19 | Source: 1983 Lisa UI Guidelines.pdf | Est. Tokens: 263 -->
when the user sets aside an open document, the Desktop Manager deactivates it, and its window is shrunk back to the original icon. Just as with a deactivation, the state of the document remains unchanged, so that when the user opens it again, he can pick up where he left off.  
To set aside a document, the user chooses Set Aside from the File/Print menu. If the user double-clicks on the icon in the left side of the title bar, one of two things happens:  
- 1) If the document was on the desktop the last time she opened it, it is set aside.
- 2) If the document was in a container (disk or folder) the last time sne opened it, the Desktop Manager puts up an alert message, asking her whether sne wants the document to be set aside or put away. [This may go away.]  
Desktop Manager  
Details: When a document is set aside, the application does not post edits to the document's save file, so that if the user opens the document again and chooses Revert to Previous Version, the document reverts to the last version that he saved.