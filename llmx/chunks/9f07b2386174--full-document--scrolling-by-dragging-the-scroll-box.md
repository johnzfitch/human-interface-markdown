---
chunk_index: 1322
ref: "9f07b2386174"
id: "9f07b2386174fffc98eeac028ee4ec0f37976c602f7628d6229e28a48e797c54"
slug: "full-document--scrolling-by-dragging-the-scroll-box"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [775, 784]
token_estimate: 361
content_sha256: "114108472288a8911f71c4b9f7f776044b32d26f2454d242ad7a180feee68154"
compacted: false
heading_path: ["Scrolling by windowful","Scrolling by dragging the scroll box"]
symbol: null
address: null
asset_path: null
---

## Scrolling by dragging the scroll box

The scroll box shows the relative position, within the whole document, of the portion of the document now visible in the window. (This has nothing to do with the position of the pointer, which can be outside the window; or of the insertion point, which can be anywhere in the document.) If the scroll box is half way between the top and the bottom of the scroll bar, then the visible portion of the document is half way between the top and the bottom of the document. To scroll the document, the user drags the scroll box. For example, to see the beginning of the document, the user drags the scroll box to the top of the scroll bar.

If the user starts dragging the scroll box, and then moves the pointer a certain distance outside the scroll bar, the scroll box stops following the pointer and snaps back to its original position. If the user then releases the mouse button, no scrolling occurs. But if the user, still holding down the mouse button, moves the pointer back *into* the scroll bar, the scroll box again begins to move up and down with the pointer.

If a document has a fixed size, and the user scrolls to the right or bottom edge of the document, the application displays a light gray background between the edge of the document and the window frame.

Some applications put the page number inside the scroll box so that the user can see the page number change as the document scrolls.