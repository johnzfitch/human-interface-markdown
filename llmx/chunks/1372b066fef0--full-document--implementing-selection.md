---
chunk_index: 4017
ref: "1372b066fef0"
id: "1372b066fef074500e9c1ee94969610208e5f7fe674ea0c33fc8e082fe9247c3"
slug: "full-document--implementing-selection"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1088, 1097]
token_estimate: 219
content_sha256: "c10d8496e4604060bfa64b1001c206aa89d6445c043365af97a629a461c56c93"
compacted: false
heading_path: ["*Introduction*","**Implementing Selection**"]
symbol: null
address: null
asset_path: null
---

## **Implementing Selection**

If your application has editable text or allows selection of multiple custom objects, you need to read this section. In particl\lar, even if your application uses the Text object for its editable text areas, you still need to implement the modifier-arrow combinations described in "Implementing the Modified Arro~ Keys."

When implementing selection, make sure that your application never moves the selection out of the user's view. If necessary, the display must scroll to make the new selection visible. Of course, the user can choose to move the selection out of view, using a scroller. But as soon as the user makes a new selection, such as by pressing an arrow key, the selection should scroll back into view.

**Programming Note: Hiding the Cursor** 

To temporarily hide the cursor, use the single-operator function **PSobscurecursorO.**