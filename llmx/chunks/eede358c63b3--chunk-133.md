---
chunk_index: 2344
ref: "eede358c63b3"
id: "eede358c63b3ebd9f77af19b9b34a504d3047d60a4c395c428751b88ec1e01c4"
slug: "chunk-133"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_133.md"
kind: "markdown"
lines: [1, 5]
token_estimate: 252
content_sha256: "ba6570c32914759cf3dd69d8a9e6b52551790d39b06a29b71b7bef67012ff2af"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 133 | Source: 1992 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 498 -->
Movable modal dialog boxes should respond like modal dialog boxes in most ways. (See the section "Modal Dialog Boxes" on page 188 for a discussion of modal dialog boxes.) You must make certain that the dialog box is modal within your application. That is, the user should not be able to switch to another of your application's windows while the dialog box is active.  
For movable modal dialog boxes, there are certain behaviors you need to support. Allow your application to run in the background when you display a movable modal dialog box. For example, System 7 uses movable modal dialog boxes to show that an application is busy with a time-consuming operation, yet a user can still switch the application to the background. Figure 6-10 shows a movable modal dialog box displayed by the Finder when it is copying files.  
**Figure 6-10** A Finder movable modal dialog box  
![](images/_page_210_Picture_8.jpeg)