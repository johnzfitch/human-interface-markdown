---
chunk_index: 270
ref: "6655833e05ff"
id: "6655833e05ff883701ee6841b57623be4645debf9be65f814ec937db41cf40bb"
slug: "chunk-020--details"
path: "marker/1983 Lisa UI Guidelines/chunks/chunk_020.md"
kind: "markdown"
lines: [4, 5]
token_estimate: 75
content_sha256: "b038caca66ea0ca0e8ebbb14bb3ab2f267ba0f57a20393a32f0fb446dce7981d"
compacted: false
heading_path: ["Details:"]
symbol: null
address: null
asset_path: null
---

#### Details:  
Implementation: By default, an active document has two files associated with it: The Save file, written to only when the document is saved, and the Suspend file, which contains the document heap and which is swapped out from time to time. Saving the document deletes the Suspend file.