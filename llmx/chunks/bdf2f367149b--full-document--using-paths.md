---
chunk_index: 4193
ref: "bdf2f367149b"
id: "bdf2f367149b4d9f0a75ad9161d48ead7861adaad2552eb1aed0339fbdcdfffe"
slug: "full-document--using-paths"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [3118, 3121]
token_estimate: 111
content_sha256: "69d6d607afae33840aef4079b867c84980cb8981ce2e777fe6a63109944a1f6b"
compacted: false
heading_path: ["*The I nterface to the File System*","**Using Paths**"]
symbol: null
address: null
asset_path: null
---

## **Using Paths**

If your application needs to look up data that could be in several places on the system, it should use an ordered path similar to the one used by the Workspace Manager. For example, if an application requires a particular template file that might be supplied either by the user or by the system administrator, it should search for it first in a folder under .... !Library, and then in the same folder under !LocaILibrary.