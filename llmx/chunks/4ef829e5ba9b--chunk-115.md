---
chunk_index: 3724
ref: "4ef829e5ba9b"
id: "4ef829e5ba9baee02e558947ad4c3bfa6c73fa35f7f402e0787abbd1c3e8213d"
slug: "chunk-115"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_115.md"
kind: "markdown"
lines: [1, 7]
token_estimate: 293
content_sha256: "592d33f9f55f8a249671eb5b92351d056c79401dfca250940a6468297526e710"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 115 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 266 -->
When the user closes a document that has been edited but not saved, the application must bring up a Close panel giving the user an opportunity to cancel the operation, save the document before closing, or confirm that it should be closed without saving. This attention panel should have at least these three buttons:  
Cancel Don't Save Save  
Save is the default option because many users don't think of closing a document and saving the most recent changes to it as separate operations-for many, closing implies saving.  
If closing a document or window has consequences other than that unsaved changes would be lost, the application must still bring up a Close panel informing the user. For example, when the user closes a terminal emulation window, the application should notify the user that closing the window will cause the running command to be terminated. If the panel can't offer the user any way of avoiding the side effects, it should have these buttons:  
Cancel Close Anyway  
**Note:** Do *not* bring up a Close panel unless work is about to be lost.