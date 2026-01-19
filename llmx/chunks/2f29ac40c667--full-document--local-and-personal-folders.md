---
chunk_index: 4188
ref: "2f29ac40c667"
id: "2f29ac40c667d9f07a143253c74c4e0945907b8707ff0dc679d773a61930d44f"
slug: "full-document--local-and-personal-folders"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [3072, 3079]
token_estimate: 237
content_sha256: "81584f5cd7e7ca005e987d4f74006d066a8d451bbf823537bc6b31a182572321"
compacted: false
heading_path: ["*The I nterface to the File System*","**Local and Personal Folders**"]
symbol: null
address: null
asset_path: null
---

## **Local and Personal Folders**

The four folders with a "Next" prefix can be matched by four identical folders with a "Local" prefix. Internally, these four folders should be organized like their "Next" counterparts. But instead of containing files supplied by NeXT, they should hold information and applications provided for all users at a local site. Any user who logs in to a machine, or boots from it over a network, has access to its "Local" folders. If you add a new font for all users of your network, for example, it would reside in lLoealLibrarylFonts.

"Local" folders are created as they're needed. They aren't included on the release disk.

Users can add unprefixed Library and Apps folders in their home folders to hold information and applications that they alone have access to. Users who develop utilities for their own use or purchase private copies of a word processor and spreadsheet, for example, should put them in -/ Apps.