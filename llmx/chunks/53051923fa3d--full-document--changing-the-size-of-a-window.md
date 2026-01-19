---
chunk_index: 1317
ref: "53051923fa3d"
id: "53051923fa3dce7306d663cd77490e167973dfb755b0f22a809bac2ab86a75eb"
slug: "full-document--changing-the-size-of-a-window"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [711, 722]
token_estimate: 399
content_sha256: "690757f086db6014bcd0ec6e691ce00bd2e27641aa08e6b68d06fae3183968b7"
compacted: false
heading_path: ["Changing the size of a window"]
symbol: null
address: null
asset_path: null
---

# Changing the size of a window

If a window has a size box in its bottom right corner, the user can change the size of the window—enlarging or reducing it to the desired size.

Dragging the size box attaches a dotted outline of the window to the pointer. The outline's upper-left corner stays fixed, while the lower-right corner follows the pointer. When the mouse button is released, the window is redrawn in the shape of the dotted outline.

If a window can be moved, but not resized, then the user ends up constantly moving windows on and off the screen. If the user moves the window off the right or bottom edge of the screen, the scroll bars are the first things to disappear. To scroll the window, the user must move the window back onto the screen again. If, on the other hand, the window can be resized, then the user can change its size instead of moving it off the screen, and will still be able to scroll.

Resizing a window doesn't change the position of the upper-left comer of the window or the appearance of the part of the view that's still showing; it changes only how much of the view is visible inside the window. One exception to this rule is a command such as MacDraw's "Reduce to Fit," which changes the scaling of the view to fit the size of the window. If, after choosing this command, the user resizes the window, the application changes the scaling of the view.

Applications determine the minimum and maximum window size, which should depend on the physical size of the display. If the user tries to shrink the window below its minimum size, the attempt is ignored.