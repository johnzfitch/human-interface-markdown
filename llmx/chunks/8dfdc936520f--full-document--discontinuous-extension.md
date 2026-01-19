---
chunk_index: 3988
ref: "8dfdc936520f"
id: "8dfdc936520f895f819cce836a31807e4f23fbe398cdaf7b5829309eae297a4a"
slug: "full-document--discontinuous-extension"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [761, 777]
token_estimate: 363
content_sha256: "cb0f9dc7aa43385688f5189404846c41741d8b4b1155c9c071c7947415031ee6"
compacted: false
heading_path: ["*Introduction*","**Clicking to Select**","**Multiple-Clicking to Select**","**Discontinuous Extension**"]
symbol: null
address: null
asset_path: null
---

#### **Discontinuous Extension**

The Shift key lets users add to, or subtract from, the current selection. Additions don't have to be continuations of the current selection, so discontinuous selections can result.

**Note:** Discontinuous selection is common for editable graphics, icons, and items arranged in a list. It usually isn't implemented for normal text.

To add to the selection, the user clicks and drags as usual while holding the Shift key down. New material is selected, but the previous selection also remains. This is illustrated in the middle column of the following figure.

![](images/_page_42_Picture_4.jpeg)

To subtract from the selection, the user holds the Shift key down while clicking or dragging over the current selection. Shift-clicking and Shift-dragging deselect material that's already been selected. While keeping the Shift key down, the user can first select material, then deselect it, then select it again.

Shift-dragging either selects or deselects; it never does both. Which it does depends on the item under the cursor when the mouse button goes down:

- If the item isn't currently part of the selection, Shift-dragging serves to select it and everything the user drags over. It won't deselect material that happens already to be selected.
- If the item is currently selected, Shift-dragging deselects it and any other selected material that's dragged over. It won't add unselected material to the selection.