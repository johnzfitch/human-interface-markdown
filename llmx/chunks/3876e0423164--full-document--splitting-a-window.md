---
chunk_index: 551
ref: "3876e0423164"
id: "3876e04231641a13fb064c735c00bd8bfb0789f61c192b11fcba3cd09f624377"
slug: "full-document--splitting-a-window"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1536, 1559]
token_estimate: 510
content_sha256: "c1b6e03f808597f192d282fd286fbf64757460d6de1a2b75250e11c305fd3ce4"
compacted: false
heading_path: ["Automatic Scrolling","Splitting a Window"]
symbol: null
address: null
asset_path: null
---

### Splitting a Window

Sometimes it's desirable to be able to see disjoint parts of a document simultaneously. Applications that accommodate such a capability allow the window to be split into independently scrollable panes.

Applications that support splitting a window into panes place split bars at the top of the vertical scroll bar and to the left of the horizontal one. Pressing a split bar attaches it to the pointer. Dragging the split bar positions it anywhere along the scroll bar; releasing the mouse button moves the split bar to a new position, splits the window at that location, and divides the appropriate scroll bar (horizontal or vertical) into separate scroll bars for each pane. Figure 13 shows the ways a window can be split.

![](images/_page_101_Picture_10.jpeg)

Figure 13. Types of Split Windows

1/15/85 Tognazzini

After a split, the document appears the same, except for the split line lying across it. But there are now separate scroll bars for each pane. The panes are still scrolled together in the orientation of the split, but can be scrolled independently in the other orientation. For example, if the split is horizontal, then horizontal scrolling (using the scroll bar along the bottom of the window), is still synchronous. Vertical scrolling is controlled separately for each pane, using the two scroll bars along the right of the window. This is shown in Figure 14.

![](images/_page_102_Figure_3.jpeg)

The panes scroll independently in the horizontal orientation

Figure 14. Scrolling a Split Window

To remove a split, the user drags the split bar to the bottom or the right of the window.

The number of views in a document doesn't alter the number of selections per document: that is, one. The active selection appears highlighted in all views that show it. If the application has to scroll automatically to show the selection, the pane that should be scrolled is the last one that the user clicked in. If the selection is already showing in one of the panes, no automatic scrolling takes place.