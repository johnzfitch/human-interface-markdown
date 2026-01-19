---
chunk_index: 3828
ref: "fb5d3cb228d7"
id: "fb5d3cb228d7f781959b965b54ad71b2ad07b901184a7269c4223247c375c6ae"
slug: "chunk-184"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_184.md"
kind: "markdown"
lines: [1, 5]
token_estimate: 307
content_sha256: "cd079c88bfc12ea552ad04d60dd05f229b8a6eed6f7864562d2d78efa8c68ff2"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 184 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 280 -->
An application should create a file package when it has a group of files that it needs to keep together. For example, if your application displays information that's stored in independent text files, or if it makes use of a private utility program, or if it just loads archived objects from Interface Builder ".nib" files, you may want to keep these auxiliary files in close proximity to the application executable file. A file package (with the ".app" file name extension) is the way to do it.  
Similarly, if your application creates documents that are split into more than one file-for example, if text is in one file and artwork in another-these files can also be grouped in a file package.  
File packages for documents should bear the same extension that's assigned to the application's document files. For example, if a word processor uses a file package to store a document that has artwork, then the file package's extension should be the same as if the document had no artwork and was thus in a single file.  
Opening and naming files within a document file package is entirely the application's responsibility.