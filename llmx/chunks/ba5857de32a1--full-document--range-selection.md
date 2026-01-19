---
chunk_index: 883
ref: "ba5857de32a1"
id: "ba5857de32a15ee6a905cca2b6951cf8ff11ead840d0484acfb65a07ce666969"
slug: "full-document--range-selection"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [916, 923]
token_estimate: 243
content_sha256: "0b471bbfb651845138f2e8116a4e06bb97c72c88bf16e86c4d15e3c7a674b716"
compacted: false
heading_path: ["**Types of Objects**","Selection in General","Selection by Clicking","Range Selection"]
symbol: null
address: null
asset_path: null
---

#### Range Selection

The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:

- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continually highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. (If possible, the view should scroll to allow extending the selection beyond one windowful.)
- 3. When the feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the active end of the range.