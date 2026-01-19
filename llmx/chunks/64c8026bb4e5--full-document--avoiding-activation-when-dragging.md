---
chunk_index: 4061
ref: "64c8026bb4e5"
id: "64c8026bb4e5112002bc6e24784aa2b9bc19819d8e9a0ace617fd87ce3b16966"
slug: "full-document--avoiding-activation-when-dragging"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1514, 1523]
token_estimate: 514
content_sha256: "0e8f7200f416f47df606717d636a51ed86f09e743741632b794162a2f4c6ddee"
compacted: false
heading_path: ["The Window Interface to Applications","**Avoiding Activation when Dragging**"]
symbol: null
address: null
asset_path: null
---

## **Avoiding Activation when Dragging**

When a user drags an object such as a color or file between two applications, both the area that originally contains the object (the source) and the area that the object is being dragged to (the destination) need to be visible. Sometimes the user needs to move the windows of one or both applications to make this true. Once the user starts to drag the object, it can be inconvenient for the applications' windows to change their ordering, since that can cause the destination to be covered. But if the source's application isn't active when the user starts dragging, the standard response would be to activate it, which would bring the application's windows forward and perhaps cover the destination.

To avoid covering the destination, an exception to the standard activation behavior is necessary: When a user drags an object from one application to another, the source's application should not become active as a result of the dragging operation. However, the source's application should activate as usual when the user clicks anywhere in the source's window or begins a drag anywhere in the window except the source area.

Avoiding activation when dragging objects is fairly simple to implement. First,each View that contains draggable objects shouldoverride **acceptsFirstMouse** so that it returns YES. This enables the View to receive events whether or not its window is the key window. Next, the View should override the **shouldDelayWindowOrderingForEvent:**  method so that it returns YES when the passed mouse-down event occurred over a draggable object. (The **shouldDelayWindowOrderingForEvent:** message is sent just before the **mouseDown:** message for the event.)

That's all you have to do if you use the dragging system. The dragging system automatically calls the **preventWindowOrdering** method (which prevents the window's application from being activated) if the object is dragged. Unless the **preventWiridowOrdering** method is called, the window's application is activated, as usual.