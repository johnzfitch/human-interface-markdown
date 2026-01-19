---
chunk_index: 3822
ref: "c39a2fd056fc"
id: "c39a2fd056fcd887ac0fc897c96465896d4cb176b1c8ef0e6948509ac7a1ade3"
slug: "chunk-178"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_178.md"
kind: "markdown"
lines: [1, 4]
token_estimate: 224
content_sha256: "b00a3c6e8f09f96960580cc86ff1c4a4d2004e266820ff5a9935da9484fc2d82"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 178 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 197 -->
The Net folder gives the user access to file systems that are physically located on remote machines. The immediate folders under Net name the machines where the file systems are located. The next level of folders name the root folders of the file systems on those machines. For example, !Net/willow/mise is where the mise file system located on the willow computer would be mounted.  
Net contains folders only if the user's computer is set up to be connected to other machines over a network.  
All the folders in the root *(I)* folder, including Net, are physically located on the disk that the user's machine was booted from. If a user boots from a local hard disk, for example, NextLibrary and all its folders will be stored on the local disk. Remote folders are mounted only under Net.