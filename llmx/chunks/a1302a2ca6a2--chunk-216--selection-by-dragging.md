---
chunk_index: 2458
ref: "a1302a2ca6a2"
id: "a1302a2ca6a2ac42fab18c5353aad70f0987a4e4a4c5ebf617bbb43f77a181ce"
slug: "chunk-216--selection-by-dragging"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_216.md"
kind: "markdown"
lines: [7, 11]
token_estimate: 248
content_sha256: "2db287b998c4ab9dc986fea99db1e6a1b2cb1cb9ea726fccb5df7f83e56e9e32"
compacted: false
heading_path: ["Selection by Clicking","Selection by Dragging"]
symbol: null
address: null
asset_path: null
---

#### Selection by Dragging  
The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:  
- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the mouse button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continuously highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. If appropriate, the view should scroll to allow extending the selection beyond one window.
- 3. When visual feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the **active end** of the range.