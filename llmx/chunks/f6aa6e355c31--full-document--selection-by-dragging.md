---
chunk_index: 2888
ref: "f6aa6e355c31"
id: "f6aa6e355c31b2b8912b9a7399e472756a612a3d53531e5cc6589861d50d6c38"
slug: "full-document--selection-by-dragging"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4512, 4519]
token_estimate: 248
content_sha256: "b9932a15a67bba10a819efd285a27ab6cf17a5ede569df27f0f2de1705aee29e"
compacted: false
heading_path: ["Selecting","Selection Methods","Selection by Clicking","Selection by Dragging"]
symbol: null
address: null
asset_path: null
---

#### Selection by Dragging

The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:

- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the mouse button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continuously highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. If appropriate, the view should scroll to allow extending the selection beyond one window.
- 3. When visual feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the **active end** of the range.