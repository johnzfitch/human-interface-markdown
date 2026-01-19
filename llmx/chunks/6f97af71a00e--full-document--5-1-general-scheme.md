---
chunk_index: 293
ref: "6f97af71a00e"
id: "6f97af71a00eed053941423e920e481a5cb1c7eab8ebade5a7630378d5614b07"
slug: "full-document--5-1-general-scheme"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [185, 190]
token_estimate: 176
content_sha256: "078c00ecf7cf27edfefe0eaf25bb1156df5185890a268a2e781daca4b62f07cc"
compacted: false
heading_path: ["Chapter 5 Desktop Manager","5.1 General scheme"]
symbol: null
address: null
asset_path: null
---

## 5.1 General scheme

Some applications limit the size of a document to one whose contents can be kept in memory at the same time (for example, LisaCalc). In these applications, any changes the user makes to the document are kept in memory. When the user saves the document, the changes are made to the document on the disk. If the user chooses Revert to Previous Version, the changes are nullified.

In other applications, the user can create documents that are too large to fit into memory (for example, LisaList). In this case, the application keeps a file containing the changes to the document. When the user saves the document, the application updates it based on the material in the change file.