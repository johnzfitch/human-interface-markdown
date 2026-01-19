---
chunk_index: 547
ref: "5c12ae314a9c"
id: "5c12ae314a9c92ce94c039eb5d8bc0f5b780c14f681ddd5c54ec8c3f3cb57faa"
slug: "full-document--changing-the-size-of-a-window"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1467, 1478]
token_estimate: 487
content_sha256: "76269207d9b8bc86a4b2c68c2900f7cb19935889a158c97f33a5655b8eee166e"
compacted: false
heading_path: ["Moving (Dragging) a Window","Changing the Size of a Window"]
symbol: null
address: null
asset_path: null
---

### Changing the Size of a Window

If a window has a size or grow box in its bottom right corner, where the scroll bars come together, the user can change (grow) the size of the window—enlarging or reducing it to the desired size.

Dragging the size box attaches a dotted outline of the window to the pointer. The outline's top left corner stays fixed, while the bottom right corner follows the pointer. When the mouse button is released, the entire window is redrawn in the shape of the dotted outline. The standard keyboard shortcut for growing a window is Open-Apple-G. The user can then use the cursor keys for growing or shrinking the window. The user exits by pressing ESC to cancel, RETURN to accept the new size, or any other valid Open-Apple combination to accept and move on.

Moving windows and growing them go hand in hand. If a window can be moved, but not shrunk or grown, then the user ends up constantly dragging windows on and off the screen. The reason for this is that if the user drags the window off the right or bottom edge of the screen, the scroll bars are the first thing to disappear. To scroll the window, the user must move the window back onto the screen again. If, on the other hand, the window can be resized, then the user can change its size instead of dragging it off the screen, and will still be able to scroll.

Growing a window doesn't change the position of the top left corner of the window over the document or the appearance of the part of the view that's still showing; it changes only how much of the view is visible inside the window. One exception to this rule is a command such as Reduce to Fit in MacDraw, which changes the scaling of the view to fit the size of the window. If, after choosing this command, the user resizes the window, the application changes the scaling of the view.

The application can define a minimum window size. Any attempt to shrink the window below this size is ignored.