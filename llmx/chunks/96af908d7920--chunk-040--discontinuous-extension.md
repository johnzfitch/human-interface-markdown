---
chunk_index: 3621
ref: "96af908d7920"
id: "96af908d792011410bd5cffeac2cab67eabac7a0eea3faefde1c72bd480cee83"
slug: "chunk-040--discontinuous-extension"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_040.md"
kind: "markdown"
lines: [11, 19]
token_estimate: 365
content_sha256: "41357aaa102d1693093733aa72e290e081e586cac59a68221655c8f28bb76bad"
compacted: false
heading_path: ["**Extending the Selection**","**Continuous Extension**","**Discontinuous Extension**"]
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