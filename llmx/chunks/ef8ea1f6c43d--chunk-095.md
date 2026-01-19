---
chunk_index: 3694
ref: "ef8ea1f6c43d"
id: "ef8ea1f6c43d322fef10d63ff2e52a013c718d0442188161e4a52824c48875e1"
slug: "chunk-095"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_095.md"
kind: "markdown"
lines: [1, 5]
token_estimate: 530
content_sha256: "b3ab275ef22576ccbb42b82258d4aa469bd18b7494a51bb1179a3f1e549e9566"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 95 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 503 -->
When a user drags an object such as a color or file between two applications, both the area that originally contains the object (the source) and the area that the object is being dragged to (the destination) need to be visible. Sometimes the user needs to move the windows of one or both applications to make this true. Once the user starts to drag the object, it can be inconvenient for the applications' windows to change their ordering, since that can cause the destination to be covered. But if the source's application isn't active when the user starts dragging, the standard response would be to activate it, which would bring the application's windows forward and perhaps cover the destination.  
To avoid covering the destination, an exception to the standard activation behavior is necessary: When a user drags an object from one application to another, the source's application should not become active as a result of the dragging operation. However, the source's application should activate as usual when the user clicks anywhere in the source's window or begins a drag anywhere in the window except the source area.  
Avoiding activation when dragging objects is fairly simple to implement. First,each View that contains draggable objects shouldoverride **acceptsFirstMouse** so that it returns YES. This enables the View to receive events whether or not its window is the key window. Next, the View should override the **shouldDelayWindowOrderingForEvent:**  method so that it returns YES when the passed mouse-down event occurred over a draggable object. (The **shouldDelayWindowOrderingForEvent:** message is sent just before the **mouseDown:** message for the event.)  
That's all you have to do if you use the dragging system. The dragging system automatically calls the **preventWindowOrdering** method (which prevents the window's application from being activated) if the object is dragged. Unless the **preventWiridowOrdering** method is called, the window's application is activated, as usual.