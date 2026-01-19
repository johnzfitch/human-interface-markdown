---
chunk_index: 3686
ref: "099fa0eb5033"
id: "099fa0eb503332dc6f0670021c5a292b371c4b1b6c4d811abc82f3bdb5b6aa9c"
slug: "chunk-088--programming-note-implementing-titles-of-docu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_088.md"
kind: "markdown"
lines: [5, 8]
token_estimate: 93
content_sha256: "006dedb874439c61ad6f8357e130d754c394951929e6db210cca4566ec5bc43e"
compacted: false
heading_path: ["**Programming Note: Implementing Titles of Document Windows**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Implementing Titles of Document Windows**  
You should use the **setTitleAsFilename**: method of the Window class to set the title of a document window. For example, to produce the window title  
jobRecords — /Net/machine/home/records  
you should send a **setTitleAsFilename**: message with the argument "/Net/machine/home/records/jobRecords".