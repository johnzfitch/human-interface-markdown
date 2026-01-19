---
chunk_index: 3651
ref: "407ca2a82cba"
id: "407ca2a82cba4099172c6f31d0f978a5dfb4e68f1f8860a7633eed2b34a68b08"
slug: "chunk-064"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_064.md"
kind: "markdown"
lines: [1, 3]
token_estimate: 159
content_sha256: "fe4ed5cb6f9899e2fac38cb92a822efd38e8796eda91141b57387da94399e3e9"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 64 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 133 -->
Sometimes an application implements selection for an area but doesn't implement discontinuous selection. In this case, the application should make the Shift key act like the Alternate key during selection, so that both keys cause continuous selection.  
For example, discontinuous selection is not implemented in the Application Kit Text object, so both Shift-clicking and Alternate-clicking extend the selection continuously. This saves the user from making errors due to pressing the wrong key when trying to extend the selection.