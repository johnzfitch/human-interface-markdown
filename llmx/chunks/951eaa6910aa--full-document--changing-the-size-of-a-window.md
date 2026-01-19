---
chunk_index: 944
ref: "951eaa6910aa"
id: "951eaa6910aad3ff24fd3c7dcb5b1a78e0bf6d4906083be66d12fbea246bdd23"
slug: "full-document--changing-the-size-of-a-window"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1783, 1794]
token_estimate: 412
content_sha256: "3ee02f667850c7a141586be3816fd4cbf77a722f7b9975eae2e811abced5c6be"
compacted: false
heading_path: ["Windows","The Active Window","Moving a Window","Changing the Size of a Window"]
symbol: null
address: null
asset_path: null
---

#### Changing the Size of a Window

If a window has a size box in its bottom right corner, where the scroll bars come together, the user can change the size of the window—enlarging or reducing it to the desired size.

Dragging the size box attaches a dotted outline of the window to the pointer. The outline's top left corner stays fixed, while the bottom right corner follows the pointer. When the mouse button is released, the entire window is redrawn in the shape of the dotted outline.

If a window can be moved, but not resized, then the user ends up constantly moving windows on and off the screen. If the user moves the window off the right or bottom edge of the screen, the scroll bars are the first things to disappear. To scroll the window, the user must move the window back onto the screen again. If, on the other hand, the window can be resized, then the user can change its size instead of moving it off the screen, and still be able to scroll.

Resizing a window doesn't change the position of the top left corner of the window over the document or the appearance of the part of the view that's still showing; it changes only how much of the view is visible inside the window. One exception to this rule is a command such as Reduce to Fit in MacDraw, which changes the scaling of the view to fit the size of the window. If, after choosing this command, the user resizes the window, the application changes the scaling of the view.

Applications determine the minimum and maximum window size, which schould depend on the physical size of the display. If the tries to shrink the window below its minimum size, the attempt is ignored.