---
chunk_index: 526
ref: "5d0d56041280"
id: "5d0d56041280a5ae5520d2d89d1ead431a319573f2326b28d98117f5d103ecb4"
slug: "full-document--mouse-actions"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1167, 1196]
token_estimate: 695
content_sha256: "1afcc5d3211df79d9252b65ad42bbf5f77fcf35e6afed9ceeac4a67e728add73"
compacted: false
heading_path: ["THE MOUSE","Mouse Actions"]
symbol: null
address: null
asset_path: null
---

### Mouse Actions

The three basic mouse actions are:

- <u>clicking</u>: positioning the pointer with the mouse, then briefly pressing and releasing the mouse button without moving the mouse
- pressing: positioning the pointer with the mouse, then holding down the mouse button without moving the mouse
- <u>dragging</u>: positioning the pointer with the mouse, holding down the mouse button, moving the mouse to a new position, and releasing the button

The Mouse Toolkits can provide "mouse-ahead"; that is, any mouse actions the user performs when the application isn't ready to process them are saved in a buffer and can be processed at the application's convenience. The application can then choose to ignore saved-up mouse actions, but should do so only to protect the user from possibly damaging consequences.

Clicking something with the mouse performs an instantaneous action, such as selecting a location within the user's document or activating an object.

For certain kinds of objects, pressing on the object has the same effect as clicking it repeatedly. For example, clicking a scroll arrow causes a document to scroll one line; pressing on a scroll arrow causes the document to scroll repeatedly until the mouse button is released or the end of the document is reached.

Dragging can have different effects, depending on what's under the pointer when the mouse button is pressed. The uses of dragging include choosing a menu item, selecting a range of objects, moving an object from one place to another, and shrinking or expanding an object.

Some objects, especially graphic objects, can be moved by dragging. In this case, the application attaches a dotted outline of the object to the pointer and redraws the outline continually as the user moves the pointer. When the user releases the mouse button, the application redraws the complete object at the new location.

An object being moved can be restricted to certain boundaries, such as the edges of a window frame. If the user moves the pointer outside of the boundaries, the application stops drawing the dotted outline of the object. If the user releases the mouse button while the pointer is outside of the boundaries, the object isn't moved. If, on the other hand, the user moves the pointer back within the boundaries again before releasing the mouse button, the outline is drawn again.

In general, moving the mouse changes nothing except the location, and possibly the shape, of the pointer. Pressing the mouse button indicates the intention to do something, and releasing the button

1/15/85 Tognazzini

/INTF/MOUSE

THE MOUSE 69

completes the action. Pressing by itself should have no effect except in well-defined areas, such as scroll arrows, where it has the same effect as repeated clicking.