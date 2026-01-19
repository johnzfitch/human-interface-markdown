---
chunk_index: 779
ref: "cf393b4f3e06"
id: "cf393b4f3e06a565e0c14271788e013141d960c20d7bede8984834619922ddd5"
slug: "chunk-068--automatic-scrolling"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_068.md"
kind: "markdown"
lines: [11, 20]
token_estimate: 621
content_sha256: "3709fb064aa6109850ec7eedefa005c504ee30e1a6ed482420f0b42fe703fd95"
compacted: false
heading_path: ["Scrolling by Windowful","Scrolling by Dragging the Scroll Box","**Automatic Scrolling**"]
symbol: null
address: null
asset_path: null
---

#### **Automatic Scrolling**  
There are three instances when the application, rather than the user, scrolls the document. These instances involve some potentially sticky problems about how to position the document within the window after scrolling.  
- The first case is when the user moves the pointer out of the window while either selecting by dragging or while moving a selection with the mouse or with arrow keys. The window keeps up with the selection by scrolling automatically in the direction the pointer has been moved. The rate of scrolling is the same as if the user were pressing on the corresponding scroll arrow or arrows.
- The second case is when the user performs an operation on a selection that isn't currently showing in the window. When this happens, it's usually because the user has scrolled the document after making a selection. In this case, the application scrolls the window so that the selection is showing before performing the operation.
- The third case is when the application performs an operation whose side effect is to make a new selection or move the insertion point. An example is a search operation, after which the object of the search is selected. If this object isn't showing in the window, the application must scroll the document to show it. Another example: After a paste operation, the insertion point is after the end of the thing that was pasted.  
The second and third cases present the same problem: Where should the selection be positioned within the window after scrolling? The primary rule is that the application should avoid unnecessary scrolling. Users prefer to retain control over the positioning of a document. The following guidelines should be helpful:  
- If part of the new selection is already showing in the window, don't scroll at all. An exception to this rule is when the part of the selection that isn't showing is more important than the part that is showing.
- If scrolling in *one* orientation (either horizontal or vertical) is enough to reveal the selection, don't scroll in both orientations.
- If the selection is smaller than the window, position the selection so that some of its context is showing on each side. It's better to put the selection somewhere near the middle of the window than right up against the corner.
- Even if the selection is too large to show in the window, it might be preferable to show some context rather than to try to fit as much as possible of the selection in the window.