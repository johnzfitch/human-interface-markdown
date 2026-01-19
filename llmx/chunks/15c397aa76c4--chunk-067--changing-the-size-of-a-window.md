---
chunk_index: 772
ref: "15c397aa76c4"
id: "15c397aa76c4689010dcdeba10851bb4dcd9b090b256933bfe0db8158b76ff23"
slug: "chunk-067--changing-the-size-of-a-window"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_067.md"
kind: "markdown"
lines: [12, 17]
token_estimate: 413
content_sha256: "2b27524b15b801cf28cfdffe0fcc609638d4e4523559747790b05ce76e8ebd25"
compacted: false
heading_path: ["Moving a Window","Changing the Size of a Window"]
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