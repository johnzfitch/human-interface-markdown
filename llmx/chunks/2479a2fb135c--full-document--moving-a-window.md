---
chunk_index: 2754
ref: "2479a2fb135c"
id: "2479a2fb135ceffa0930f2fef6239774ca714c073eac58a1ac1a264fea9b6e15"
slug: "full-document--moving-a-window"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2566, 2579]
token_estimate: 248
content_sha256: "f9100a7f2fa91578aa0c7b3779c038b09838cd8157853ee6c94bb98850e89e78"
compacted: false
heading_path: ["Window Behaviors","Moving a Window"]
symbol: null
address: null
asset_path: null
---

## Moving a Window

The user moves a window by dragging its title bar. As the user drags, a dotted outline of the window moves with the pointer until the user releases the mouse button. At the release of the button, the full window and its contents appear at the new location. Moving a window doesn't affect the appearance of the document within the window. Figure 5-24 shows how a moving window looks to users.

**Figure 5-24** Moving a window

![](images/_page_178_Picture_3.jpeg)

The act of moving an inactive window makes it active. If a user presses the Command key while dragging a window, the window does not become active. The window moves in the same plane (doesn't change stacking order if there are multiple windows within the same application) and remains inactive.

Your application should never allow users to move a window to a position from which they cannot reposition it. For example, don't allow users to move windows completely off the screen.

Window Behaviors **155**