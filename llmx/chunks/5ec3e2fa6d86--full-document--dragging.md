---
chunk_index: 2856
ref: "5ec3e2fa6d86"
id: "5ec3e2fa6d861f3433c81ec36cfdd739ea4b4dbd9adbccf08291fb6ef6bee7fc"
slug: "full-document--dragging"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4216, 4227]
token_estimate: 390
content_sha256: "a8cac34ec04bc7f898613ba1cd6684f923d3cda221946fb5dcd3425b0fc839d6"
compacted: false
heading_path: ["Mouse Actions","Dragging"]
symbol: null
address: null
asset_path: null
---

## Dragging

Dragging means pressing the mouse button, moving the mouse to a new position, and then releasing the mouse button. Dragging can have different effects depending on what's under the pointer when the mouse button is pressed. The uses of dragging include selecting blocks of text, choosing a menu item, selecting a range of objects, moving an icon or other object from one place to another, and shrinking or expanding an object.

Graphic objects can be moved by dragging. The application either moves the entire object or attaches a dotted outline of the object to the pointer and moves the outline as the user moves the pointer. When the user releases the mouse button, the application redraws the complete object at the new location. Figure 10-7 shows the process of moving an object by dragging.

**Figure 10-7** Dragging to move an object

![](images/_page_297_Figure_6.jpeg)

Your application can restrict an object from being moved past certain boundaries, such as the edges of a window. If the user moves the pointer outside the boundaries, the application stops drawing the dotted outline of the object. If the user releases the mouse button while the pointer is outside the boundaries, the object doesn't move. However, if the user moves the pointer back within the boundaries before releasing the mouse button, the object appears in the new location. If the user moves the object beyond the boundary of a window, your application can also scroll the document (using automatic scrolling) or even move the object from one window to another.