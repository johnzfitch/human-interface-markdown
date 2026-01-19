---
chunk_index: 4053
ref: "57d350420368"
id: "57d350420368c3bb6bb1d6c2de6e78372fa43c242dc76925b17acadb7c5c7a2c"
slug: "full-document--programming-note-implementing-titles-of-docu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1450, 1457]
token_estimate: 92
content_sha256: "a767b468f944f0776449d62f18ca251deb04c375c454f8e1207cccec71bfaf9d"
compacted: false
heading_path: ["The Window Interface to Applications","**Choosing a Title**","**Programming Note: Implementing Titles of Document Windows**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Implementing Titles of Document Windows**

You should use the **setTitleAsFilename**: method of the Window class to set the title of a document window. For example, to produce the window title

jobRecords — /Net/machine/home/records

you should send a **setTitleAsFilename**: message with the argument "/Net/machine/home/records/jobRecords".