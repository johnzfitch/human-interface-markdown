---
chunk_index: 1935
ref: "bf884093528f"
id: "bf884093528fd8773ee7a2dd8b840417234ed22d08033b45e9a7f7d22d7edf45"
slug: "full-document--changing-the-size-of-a-window"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1170, 1181]
token_estimate: 412
content_sha256: "3133b57dc24f1b3bb0623af166bd2609c22ce95935b72dae5146df0e0f6bce40"
compacted: false
heading_path: ["Changing the size of a window"]
symbol: null
address: null
asset_path: null
---

# Changing the size of a window

If <sup>a</sup> window has <sup>a</sup> size box in its lower-right corner, the user can change the size of the window—enlarging or reducing it to the desired size.

Dragging the size box attaches <sup>a</sup> dotted outline of the window to the pointer. The outline's upper-left corner stays fixed, while the lower-right corner follows the pointer. When the mouse button is released, the window is redrawn in the shape of the dotted outline.

If a window can be moved, but not resized, then the user ends up constantly moving windows on and off the screen. If the user moves the window off the right or bottom edge of the screen, the scroll bars are the first things to disappear. To scroll the window, the user must move the window back onto the screen again. If, on the other hand, the window can be resized, then the user can change its size instead of moving it off the screen, and will still be able to scroll.

Resizing <sup>a</sup> window doesn't change the position of the upper-left corner of the window or the appearance of the part of the view that's still showing; itchanges only how much of the view is visible inside the window. One exception to this rule is <sup>a</sup> command such as Reduce to Fit (in MacDraw), which changes the scaling of the view to fit the size of the window. If, after choosing this command, the user resizes the window, the application changes the scaling of the view.

Applications determine the minimum and maximum window size, which should depend on the physical size of the display. If the user tries to shrink the window below its minimum size, the attempt is ignored.