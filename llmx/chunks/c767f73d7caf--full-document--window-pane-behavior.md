---
chunk_index: 2764
ref: "c767f73d7caf"
id: "c767f73d7caf80c5690a31d2c17675480b2078103e4544e3906d219c587b80fc"
slug: "full-document--window-pane-behavior"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2793, 2808]
token_estimate: 537
content_sha256: "e80161d6e57e92a113cbd29086e324854069e8e07ab6afc7f9513beb8302ff92"
compacted: false
heading_path: ["Window Behaviors","Splitting a Window","Window Pane Behavior"]
symbol: null
address: null
asset_path: null
---

#### Window Pane Behavior

When you implement window splitting capabilities, place the split bar at the top of the vertical scroll bar or to the left of the horizontal scroll bar, or in both positions if you support both types of splits. The user can drag the split bar anywhere along the scroll bar. Implement an outline of the split line to follow the pointer so that the user can tell where the new pane will appear. (This is similar to the outline of a scroll box being moved.) Releasing the mouse button splits the window into panes there, and divides the appropriate scroll bar into separate scroll bars for each pane.

After a single split, there are separate scroll bars for each pane. Usually the panes scroll independently in the orientation opposite of the split. That is, if the split is horizontal, the vertical scrolling is controlled separately for each pane using the two scroll bars along the right of the window. The horizontal scrolling is still synchronous, or locked, using the scroll bar along the bottom of the window. Figure 5-42 shows how window panes scroll, independently or together.

**Figure 5-42** Independent and locked scrolling of window panes

![](images/_page_195_Figure_7.jpeg)

When the user splits a window, any part of the window's contents obscured by the split line or scroll bar should move down so that it is visible. For example, if the user drags a split bar to create a horizontal split, the window's contents that would have disappeared underneath the split line should scroll down by the height of the split line, plus some additional space.

The user can make a selection in one pane, and where the same data appears in another pane, the user can Shift-click to extend the selection. See the section "Editing Text" beginning on page 300 in Chapter 10, "Behaviors," for more information on selecting text. The user should also be able to drag to extend a selection and have the pane scroll automatically as an entire window would.

Your application should save and restore the location of split lines and the content of window panes whenever the user closes a document that is divided into panes.