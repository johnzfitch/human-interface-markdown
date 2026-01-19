---
chunk_index: 407
ref: "cb52e5554dfe"
id: "cb52e5554dfe17721a4a083b2401725178b18559b2faaa6a1469b6060a776276"
slug: "chunk-076"
path: "marker/1985 Apple II Human Interface Guidelines/chunks/chunk_076.md"
kind: "markdown"
lines: [1, 6]
token_estimate: 502
content_sha256: "1a41d1e36dc25479274353152543e69c530a9ee940aba0397a047d9178da2e94"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 76 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 478 -->
If a window has a size or grow box in its bottom right corner, where the scroll bars come together, the user can change (grow) the size of the window—enlarging or reducing it to the desired size.  
Dragging the size box attaches a dotted outline of the window to the pointer. The outline's top left corner stays fixed, while the bottom right corner follows the pointer. When the mouse button is released, the entire window is redrawn in the shape of the dotted outline. The standard keyboard shortcut for growing a window is Open-Apple-G. The user can then use the cursor keys for growing or shrinking the window. The user exits by pressing ESC to cancel, RETURN to accept the new size, or any other valid Open-Apple combination to accept and move on.  
Moving windows and growing them go hand in hand. If a window can be moved, but not shrunk or grown, then the user ends up constantly dragging windows on and off the screen. The reason for this is that if the user drags the window off the right or bottom edge of the screen, the scroll bars are the first thing to disappear. To scroll the window, the user must move the window back onto the screen again. If, on the other hand, the window can be resized, then the user can change its size instead of dragging it off the screen, and will still be able to scroll.  
Growing a window doesn't change the position of the top left corner of the window over the document or the appearance of the part of the view that's still showing; it changes only how much of the view is visible inside the window. One exception to this rule is a command such as Reduce to Fit in MacDraw, which changes the scaling of the view to fit the size of the window. If, after choosing this command, the user resizes the window, the application changes the scaling of the view.  
The application can define a minimum window size. Any attempt to shrink the window below this size is ignored.