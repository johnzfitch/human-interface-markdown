---
chunk_index: 4195
ref: "b4626d4b157a"
id: "b4626d4b157ad39f2d409e6a4547fd2960aabf09c2dee684ef8a3a8bf62a99ea"
slug: "full-document--using-file-packages"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [3144, 3153]
token_estimate: 287
content_sha256: "6a98a3551bd2f32b2348b1a07b5e8a665fb5a9f493894fbc8fdc8cf69025b43d"
compacted: false
heading_path: ["*The I nterface to the File System*","**Using File Packages**"]
symbol: null
address: null
asset_path: null
---

## **Using File Packages**

An application should create a file package when it has a group of files that it needs to keep together. For example, if your application displays information that's stored in independent text files, or if it makes use of a private utility program, or if it just loads archived objects from Interface Builder ".nib" files, you may want to keep these auxiliary files in close proximity to the application executable file. A file package (with the ".app" file name extension) is the way to do it.

Similarly, if your application creates documents that are split into more than one file-for example, if text is in one file and artwork in another-these files can also be grouped in a file package.

File packages for documents should bear the same extension that's assigned to the application's document files. For example, if a word processor uses a file package to store a document that has artwork, then the file package's extension should be the same as if the document had no artwork and was thus in a single file.

Opening and naming files within a document file package is entirely the application's responsibility.