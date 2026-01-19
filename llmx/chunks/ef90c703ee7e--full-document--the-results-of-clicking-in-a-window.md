---
chunk_index: 4046
ref: "ef90c703ee7e"
id: "ef90c703ee7ed19cc071b351a56f8ca1887cb2c9b9ce3479b1a09c2710c802b3"
slug: "full-document--the-results-of-clicking-in-a-window"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1390, 1402]
token_estimate: 319
content_sha256: "3acb8f2480c06c247b0d31cb1d34846bba376ca34f0c313e0f4c6db803ac426f"
compacted: false
heading_path: ["The Window Interface to Applications","**The Results of Clicking in a Window**"]
symbol: null
address: null
asset_path: null
---

## **The Results of Clicking in a Window**

Clicking in a window has two separate, but related, results:

- The window usually becomes the key window (and usually also the main window), and its application is activated. Standard windows always become the key window when clicked, but panels might not, as described in Chapter 5.
- The window comes to the front of its tier.

The first is a change in the window's status, the second in its position on-screen.

Both results are required to make the window available to the user to work in. The window needs to be reordered in front of other windows so that its contents aren't covered. It also must become the key window for the user to be able to type in it and for it to receive menu commands. For a window to become the key window, its application must be activated.

In NeXTSTEP, however, these two results of a mouse click, while logically related, are not inseparable. If the click is in the window's title bar and is modified by the Alternate key, it brings the window to the front, but doesn't make it the key window or activate its application. Alternate-clicking in the title bar thus lets users rearrange and reorder windows on the screen without changing the current key window, main window, or active application.