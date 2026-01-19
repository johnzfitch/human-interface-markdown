---
chunk_index: 302
ref: "b0b68198058c"
id: "b0b68198058c2503b7801cf08eebf6e432494458cdd4f8c68ce657f48b7f767d"
slug: "full-document--5-25-save-put-away"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [274, 285]
token_estimate: 340
content_sha256: "d8e8c294b1766de4170186f3b59294be63cd65603166531e00c1637f7087e0c5"
compacted: false
heading_path: ["Chapter 5 Desktop Manager","5.25 Save & Put Away"]
symbol: null
address: null
asset_path: null
---

## 5.25 Save & Put Away

Save & Put Away can happen in one of three ways:

- 1) If the window is open, and the user chooses Save & Put Away, the Desktop Manager deactivates the document, saves it contents, and returns its icon to the location of its ghost. It then returns the icon to the container it was in most recently.
- 2) If the user has set aside the document on the desktop, and then chooses Save & Put Away, the Desktop Manager saves the contents of the document on the container it was in most recently.
- 3) If the user has set aside the document on the desktop, and he moves its icon to a container, the Desktop Manager saves the contents of the document on that container.

Details: Some tools (eg LisaCalc and LisaList) must do some end processing and consistency checks before a document can be put away. If the document is put away when its window is closed, the Desktop Hanager issues an alert message talling the user that the document must be put away when it is open. The application also issues an alert message if the there are I/O errors or not enough disk space.

Implementation: An application keeps a flag called "fCanPutBack" [???] to indicate whether putting away the document could cause invalid data. If this flag is false, then the Desktop Hamager puts up an alert nessage; otherwise, it puts away the document as instructed.