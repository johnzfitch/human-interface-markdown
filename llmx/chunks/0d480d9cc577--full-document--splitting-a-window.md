---
chunk_index: 952
ref: "0d480d9cc577"
id: "0d480d9cc5773d91dc0915eb3f4122cf49e154bc01aaf3fd4affa1290bb2ad60"
slug: "full-document--splitting-a-window"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1878, 1897]
token_estimate: 494
content_sha256: "5a36d1b9c8c6974562c64ffb066c7f2b80a926e4fcc012745c815603167dbb93"
compacted: false
heading_path: ["Windows","The Active Window","Scrolling With the Scroll Arrows","Splitting a Window"]
symbol: null
address: null
asset_path: null
---

#### Splitting a Window

Sometimes users want to see (and work on) two separate parts of a document simultaneously. They can do this by splitting the window into independently scrollable panes.

Applications that support splitting a window into panes place split bars at the top of the vertical scroll bar and to the left of the horizontal one. Pressing a split bar attaches it to the pointer. Dragging the split bar positions it anywhere along the scroll bar. Releasing the mouse button creates a new split bar at that location and splits the window there, and divides the appropriate scroll bar into separate scroll bars for each pane.

![](images/_page_86_Picture_1.jpeg)

Figure 43. Types of Split Windows

After a split, the document looks the same, except for the split line lying across it. But there are now separate scroll bars for each pane. The panes are still scrolled together in the orientation of the split, but can be scrolled independently in the other orientation. For example, if the split is vertical, then vertical scrolling (using the scroll bar along the right of the window) is still synchronous; horizontal scrolling is controlled separately for each pane, using the two scroll bars along the bottom of the window.

![](images/_page_87_Figure_1.jpeg)

Figure 44. Scrolling a Split Window

To remove a split (to return the window to a single pane), the user drags the split bar to either end of the scroll bar.

Even though there can be multiple panes, there can still be only one selection (the highlighted selection may appear in all of the panes, in none of the panes, or in any number in between). If a change is made in one pane, the change is reflected in all panes where that portion of the document is visible. If the application has to scroll automatically to show the selection, the pane that should be scrolled is the last one the user clicked in. If the selection is already showing in one of the panes, no automatic scrolling takes place.