---
chunk_index: 1940
ref: "acba53357243"
id: "acba53357243113ec8c78e5bc1424205d09d238026c4c6c95ca4eb9dcd1b4e83"
slug: "full-document--scrolling-by-dragging-the-scroll-box"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1232, 1241]
token_estimate: 377
content_sha256: "2cdc4625b2dab94eb4c9ccb5d7a5ad90f7851cd27e05305d3a2f962ef12765c1"
compacted: false
heading_path: ["Scrolling by dragging the scroll box"]
symbol: null
address: null
asset_path: null
---

# Scrolling by dragging the scroll box

The scroll box shows the relative position, within the whole document, of the portion of the document visible in the window. (The position of the scroll box has nothing to do with the position of the pointer, which can be outside the window; or with the position of the insertion point, which can be anywhere in the document.) If the scroll box ishalfway between the top and the bottom of the scroll bar, then the visible portion of the document is halfway between the top and the bottom of the document. To scroll the document, the user drags the scroll box. For example, to see the beginning of the document, the user drags the scroll box to the top of the scroll bar.

If the user starts dragging the scroll box, and then moves the pointer a certain distance outside the scroll bar, the scroll box stops following the pointer and snaps back to its original position. If the user then releases the mouse button, no scrolling occurs. But if the user, still holding down the mouse button, moves the pointer back into the scroll bar, the scroll box again begins to move up or down with the pointer.

If a document has a fixed size (as in MacDraw, for example), and the user scrolls to the right or bottom edge of the document, the application can display a light gray background between the edge of the document and the window frame.

Some applications put the page number inside the scroll box so that the user can see the page number change as the document scrolls.