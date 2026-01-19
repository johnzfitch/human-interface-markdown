---
chunk_index: 1389
ref: "6a95548f7f2e"
id: "6a95548f7f2e7566c24229b97979f4331cf60415dbdfb240915c0c31e6055ce5"
slug: "full-document--dragging"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1520, 1531]
token_estimate: 362
content_sha256: "9fcbdbf32930c0ebd68bd17936d1d20ed58c09a7f4755f19976f35cb2529245c"
compacted: false
heading_path: ["Dragging"]
symbol: null
address: null
asset_path: null
---

# Dragging

Dragging means pressing the mouse button, moving the mouse to a new position, and finally releasing the mouse button. Dragging can have different effects, depending on what's under the pointer when the mouse button is pressed. The uses of dragging include selecting blocks of text, choosing a menu item, selecting a range of objects, moving an icon or other object from one place to another, and shrinking or expanding an object.

Graphic objects can be moved by dragging. The application either moves the entire object, or attaches a dotted outline of the object to the pointer and moves the outline as the user moves the pointer. (When the user releases the mouse button, the application redraws the complete object at the new location.)

![](images/_page_105_Picture_0.jpeg)

Figure 50 Dragging with the mouse

An object being moved can be restricted to certain boundaries, such as the edges of a window. If the user moves the pointer outside the boundaries, the application stops drawing the dotted outline of the object. If the user releases the mouse button while the pointer is outside the boundaries, the object doesn't move. If, on the other hand, the user moves the pointer back within the boundaries again before releasing the mouse button, the outline is drawn again. Moving an object beyond the boundary of the window can also cause the window to scroll (autoscroll) or even move the object from one window into another.