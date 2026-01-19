---
chunk_index: 4189
ref: "7a0f20c7a561"
id: "7a0f20c7a561f157070ccb9460b711ffe5ad443cec2b95d238a3b6c485d8f685"
slug: "full-document--net"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [3080, 3087]
token_estimate: 200
content_sha256: "1ffb6ad9346d23bdafeffac0bcd0d0edd4b5d28883e7e3f48de1cc43fea90d09"
compacted: false
heading_path: ["*The I nterface to the File System*","**Net**"]
symbol: null
address: null
asset_path: null
---

## **Net**

The Net folder gives the user access to file systems that are physically located on remote machines. The immediate folders under Net name the machines where the file systems are located. The next level of folders name the root folders of the file systems on those machines. For example, !Net/willow/mise is where the mise file system located on the willow computer would be mounted.

Net contains folders only if the user's computer is set up to be connected to other machines over a network.

All the folders in the root *(I)* folder, including Net, are physically located on the disk that the user's machine was booted from. If a user boots from a local hard disk, for example, NextLibrary and all its folders will be stored on the local disk. Remote folders are mounted only under Net.