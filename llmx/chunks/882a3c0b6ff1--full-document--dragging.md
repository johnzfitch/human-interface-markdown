---
chunk_index: 2005
ref: "882a3c0b6ff1"
id: "882a3c0b6ff1d400e833f96294a390c06c34ddbe3266f04da06ead888b877925"
slug: "full-document--dragging"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2041, 2083]
token_estimate: 429
content_sha256: "4456f24c9f9561f82a5f1bcd5440910a87e30895fe2aa0c450aabbfb329f005a"
compacted: false
heading_path: ["Cursors, pointers, and insertion points","Percentage Complete:","Mouse actions","Dragging"]
symbol: null
address: null
asset_path: null
---

#### Dragging

Dragging means pressing the mouse button, moving the mouse to a new position, and finally releasing the mouse button (Figure 3-50). Dragging can have different effects, depending on what's under the pointer when the mouse button is pressed. The uses of dragging include selecting blocks of text, choosing a menu item, selecting a range of objects, moving an icon or other object from one place to another, and shrinking or expanding an object.

Graphic objects can be moved by dragging. The application either moves the entire object, or attaches a dotted outline of the object to the pointer and moves the outline as the user moves the pointer. When the user releases the mouse button, the application redraws the complete object at the new location.

1. Pointer over icon to be dragged

2. Click to select

3. Drag outline to right

4. Release button

System folder

System folder

System folder

System folder

System folder

System folder

System folder

System folder

System folder

System folder

System folder

System folder

Figure 3-50
Dragging with the mouse

An object being moved can be restricted to certain boundaries, such as the edges of a window. If the user moves the pointer outside the boundaries, the application stops drawing the dotted outline of the object. If the user releases the mouse button while the pointer is outside the boundaries, the object doesn't move. If, on the other hand, the user moves the pointer back within the boundaries before releasing the mouse button, the outline is redrawn in the new location. Moving an object beyond the boundary of the window can also cause the window to scroll (autoscroll) or even move the object from one window into another.