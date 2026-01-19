---
chunk_index: 2760
ref: "fee7a930dbd1"
id: "fee7a930dbd1076cbe4fbc4f6b893c321e6876eb35a9c4933dae082a8ce54f2e"
slug: "full-document--scrolling-by-dragging-the-scroll-box"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2696, 2715]
token_estimate: 425
content_sha256: "66bb593c99d3789851a59006c11c9fb9e9febc904fbbfb53e9853151bcfbed95"
compacted: false
heading_path: ["Window Behaviors","Scrolling a Window","Scroll Bars","Scrolling by Dragging the Scroll Box"]
symbol: null
address: null
asset_path: null
---

#### Scrolling by Dragging the Scroll Box

The scroll box shows the position of the visible portion of the document in relationship to the whole document. If the scroll box is halfway between the top and bottom of the scroll bar, then what the user sees is about halfway through the document. To scroll the document, the user drags the scroll box.

To see the beginning of the document, the user drags the scroll box to the top of the scroll bar; to see the end, the user drags the scroll box to the bottom. This behavior allows the user to quickly move around in the document. The user can get from one end of a long document to the other faster by dragging the scroll box than by clicking in the gray area or pressing the scroll arrows. Figure 5-36 shows how a user scrolls by using the scroll box.

**Figure 5-36** Scrolling by dragging the scroll box

![](images/_page_188_Picture_4.jpeg)

![](images/_page_188_Picture_6.jpeg)

![](images/_page_188_Picture_8.jpeg)

If the user starts dragging the scroll box, then moves the pointer out of the scroll bar, the scroll box stops following the pointer and snaps back to its original position. The user can move the pointer out of the scroll bar region by a little more than the width of the scroll box before the scroll box snaps back. If the user then releases the mouse button, no scrolling occurs. But if the user, still holding down the mouse button, moves the pointer back into the scroll bar, the scroll box resumes its movement in the direction of the pointer. This type of tracking is standard behavior for controls in general, such as buttons, checkboxes, and radio buttons.

Window Behaviors **165**

![](images/_page_189_Picture_2.jpeg)