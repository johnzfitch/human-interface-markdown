---
chunk_index: 298
ref: "3fa270b66dee"
id: "3fa270b66dee49dd358fbcd1f0596557fe70a58a365a8e1ab25b4f16eb979af1"
slug: "full-document--5-2-3-set-aside"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [249, 261]
token_estimate: 262
content_sha256: "85a514f915bafd28032629280e6a9acb884921da2ee4802678770285258dcc0f"
compacted: false
heading_path: ["Chapter 5 Desktop Manager","5.2.3 Set Aside"]
symbol: null
address: null
asset_path: null
---

## 5.2.3 Set Aside

when the user sets aside an open document, the Desktop Manager deactivates it, and its window is shrunk back to the original icon. Just as with a deactivation, the state of the document remains unchanged, so that when the user opens it again, he can pick up where he left off.

To set aside a document, the user chooses Set Aside from the File/Print menu. If the user double-clicks on the icon in the left side of the title bar, one of two things happens:

- 1) If the document was on the desktop the last time she opened it, it is set aside.
- 2) If the document was in a container (disk or folder) the last time sne opened it, the Desktop Manager puts up an alert message, asking her whether sne wants the document to be set aside or put away. [This may go away.]

Desktop Manager

Details: When a document is set aside, the application does not post edits to the document's save file, so that if the user opens the document again and chooses Revert to Previous Version, the document reverts to the last version that he saved.