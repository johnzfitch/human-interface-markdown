---
chunk_index: 4011
ref: "358a7c3121c5"
id: "358a7c3121c5ed2cf53887d2285ad58c6d8c9c9b3ac52e90b28c27efeb48eb74"
slug: "full-document--sliding-from-object-to-object"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1031, 1040]
token_estimate: 364
content_sha256: "43820e437f9c40400293fbbc45ec488fc20c6ba884522a90efc1bd817e071589"
compacted: false
heading_path: ["*Introduction*","**Sliding from Object to Object**"]
symbol: null
address: null
asset_path: null
---

## **Sliding from Object to Object**

Sometimes, a group of closely related objects reacts to dragging as if the user clicked one of the objects. No matter which object in the group was under the cursor when the mouse button was pressed, the object under the cursor when the mouse button is released is the one that's chosen. (Normally, when an object isn't in a group, it's chosen only when the mouse button is both pressed and released while the cursor is over the object.)

For example, a user can choose a menu command by pressing the mouse button as the cursor points to one command and releasing it as it points to another. Users can similarly drag from one tool to another tool when they're displayed together in a palette, or from button to button in a set of radio buttons.

The grouped objects don't all have to be of the same type. For example, a user can drag from a button that controls a pop-up list through the list to make a selection, or from a menu command that controls a submenu into the submenu.

If the user can drag from one object to another in a group of objects, then this fact should be apparent from the way the objects are displayed. Usually, such objects are displayed in a single row or column, as close to each other as possible. For example, graphical radio buttons should be right up next to each other, to distinguish them from ordinary buttons. (Graphical radio buttons are discussed in detail in Chapter 7, "Controls.")