---
chunk_index: 3666
ref: "ca0ce89ce089"
id: "ca0ce89ce08974ea11d40f014619e51906b5423f63cfe1adf9d3d2bb60a01529"
slug: "chunk-077"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_077.md"
kind: "markdown"
lines: [1, 7]
token_estimate: 304
content_sha256: "a6c4d7cbbc50115f24e4d275dd062041e95918ea46b8aea06b6b4de91e1269df"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 77 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 371 -->
The close button removes a window from the screen. What this means depends on the type of window:  
Menus and panels  
A menu that's closed is removed from the screen, but the user retains a way to retrieve it quickly through a command in another menu. Panels that are closed are retrievable in the same way. (See Chapter 6 for more information on menus.)  
When a panel that was closed is returned to the screen, it assumes its former size and location, and it retains its former state. From the user's point of view, and programmatically, it's the same panel that was closed.  
Standard windows  
Closing a standard window usually removes it from the application as well as from the screen. From the user's point of view, the same window can't necessarily be made visible again. The application might create a new window with the same title and a similar display, but there might be differences. The selection might not be preserved, and the new window won't necessarily be located in the same place or have the same shape as the old one, especially if the user had moved or resized the window that was closed.