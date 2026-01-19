---
chunk_index: 2759
ref: "59b58aa2c012"
id: "59b58aa2c012685dc5f933be24688a04de39de1ab0454355066cb7cbdafaacdb"
slug: "full-document--scrolling-with-the-gray-area"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2682, 2695]
token_estimate: 290
content_sha256: "e7d9058dfd00f225c0c1225d0bf55f45a0ffff4c0298edecfad92483c8f19ece"
compacted: false
heading_path: ["Window Behaviors","Scrolling a Window","Scroll Bars","Scrolling With the Gray Area"]
symbol: null
address: null
asset_path: null
---

#### Scrolling With the Gray Area

Clicking in the gray area of the scroll bar advances the document by a windowful. The scroll box and the document view move toward the location where the user clicked. For example, when the user clicks in the area below the scroll box, the document view moves to the next windowful toward the bottom of the document. Figure 5-35 shows how a user scrolls by clicking in the gray area.

**Figure 5-35** Scrolling by clicking in the gray area

![](images/_page_187_Picture_5.jpeg)

![](images/_page_187_Picture_7.jpeg)

Pressing in the gray area causes the display of consecutive windowfuls of the document, until the user releases the mouse button, or until the location of the scroll box catches up to the location of the pointer. A windowful equals the height or width of the window, minus at least one unit of overlap to maintain the user's context. This unit of overlap is the same measurement determined for scroll arrow movement. By retaining this unit of information, you provide a reference point for the user.

On keyboards with function keys, the Page Up and Page Down keys also move the document view by a windowful.