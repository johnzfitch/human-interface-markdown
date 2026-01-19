---
chunk_index: 2328
ref: "6fde53352150"
id: "6fde533521504417789872ab0b7fb65b665ad49b278ec61335fc333d49b4d85c"
slug: "chunk-125--scrolling-with-the-scroll-arrows"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_125.md"
kind: "markdown"
lines: [32, 39]
token_estimate: 354
content_sha256: "7a18056d9eafe04fc3f21801373439f7184a3d44ddf817cf5e9f36149457a752"
compacted: false
heading_path: ["Scroll Bars","Scrolling With the Scroll Arrows"]
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