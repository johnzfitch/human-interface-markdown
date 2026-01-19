---
chunk_index: 3650
ref: "b77afd5efb18"
id: "b77afd5efb18e3c0e206df766549661749d0911debfeff6cb491fbada5d4c70d"
slug: "chunk-063"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_063.md"
kind: "markdown"
lines: [1, 5]
token_estimate: 238
content_sha256: "51237b3ccee1b123b75cb59bad7291d46e6c0148a72b8a58762d4c3a33b9e245"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 63 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 211 -->
If your application has editable text or allows selection of multiple custom objects, you need to read this section. In particl\lar, even if your application uses the Text object for its editable text areas, you still need to implement the modifier-arrow combinations described in "Implementing the Modified Arro~ Keys."  
When implementing selection, make sure that your application never moves the selection out of the user's view. If necessary, the display must scroll to make the new selection visible. Of course, the user can choose to move the selection out of view, using a scroller. But as soon as the user makes a new selection, such as by pressing an arrow key, the selection should scroll back into view.  
**Programming Note: Hiding the Cursor**  
To temporarily hide the cursor, use the single-operator function **PSobscurecursorO.**