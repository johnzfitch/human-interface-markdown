---
chunk_index: 2758
ref: "c562773cd9a1"
id: "c562773cd9a130ace8bd7cadd42bf666840a73bab480b14fee0a7cbbf84b57f8"
slug: "full-document--scrolling-with-the-scroll-arrows"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2666, 2681]
token_estimate: 353
content_sha256: "842f00c1ae2b03b0e383f706abffda0959bad72b41ac582af8eebff6a2530c67"
compacted: false
heading_path: ["Window Behaviors","Scrolling a Window","Scroll Bars","Scrolling With the Scroll Arrows"]
symbol: null
address: null
asset_path: null
---

#### Scrolling With the Scroll Arrows

When the user clicks or presses one of the scroll arrows, more of the document in the direction of the scroll arrow appears, so the document seems to move in the opposite direction. Clicking the arrow means, "Show me more of the document that's hidden in this direction." When the user clicks the bottom scroll arrow, for example, the document moves up, bringing what was just below the window into view. Pressing the scroll arrow causes continuous movement in the appropriate direction. Figure 5-34 shows the change in a document when a user scrolls by clicking a scroll arrow.

**Figure 5-34** Scrolling by clicking a scroll arrow

![](images/_page_186_Picture_5.jpeg)

![](images/_page_186_Picture_7.jpeg)

The scroll box moves in the direction of the arrow being clicked. It continues to represent the approximate position of the visible part of the document in comparison to the whole document.

Each click in a scroll arrow causes movement of the content a distance of one unit in the chosen direction. Your application determines what one unit equals. For example, a word processor would move one line of text for each click in the arrow. A spreadsheet would move one row or one column depending on the direction of the arrow. To ensure smooth scrolling effects, it's usually best to specify units of the same size throughout a document.

Window Behaviors **163**