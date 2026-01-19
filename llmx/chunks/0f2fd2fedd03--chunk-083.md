---
chunk_index: 3679
ref: "0f2fd2fedd03"
id: "0f2fd2fedd0396950fdde4126638f340b17bebf6b30e5f62218ba3e9eb73efdd"
slug: "chunk-083"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_083.md"
kind: "markdown"
lines: [1, 7]
token_estimate: 335
content_sha256: "a64a570275458cec7221b1f73491cb3f83367824d50183e573941b5f3f6d87a4"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 83 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 308 -->
Clicking in a window has two separate, but related, results:  
- The window usually becomes the key window (and usually also the main window), and its application is activated. Standard windows always become the key window when clicked, but panels might not, as described in Chapter 5.
- The window comes to the front of its tier.  
The first is a change in the window's status, the second in its position on-screen.  
Both results are required to make the window available to the user to work in. The window needs to be reordered in front of other windows so that its contents aren't covered. It also must become the key window for the user to be able to type in it and for it to receive menu commands. For a window to become the key window, its application must be activated.  
In NeXTSTEP, however, these two results of a mouse click, while logically related, are not inseparable. If the click is in the window's title bar and is modified by the Alternate key, it brings the window to the front, but doesn't make it the key window or activate its application. Alternate-clicking in the title bar thus lets users rearrange and reorder windows on the screen without changing the current key window, main window, or active application.