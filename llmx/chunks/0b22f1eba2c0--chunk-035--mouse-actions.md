---
chunk_index: 693
ref: "0b22f1eba2c0"
id: "0b22f1eba2c0788beff64446265279ee07febb41a1eb8dfa54314f820216e646"
slug: "chunk-035--mouse-actions"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_035.md"
kind: "markdown"
lines: [10, 19]
token_estimate: 889
content_sha256: "64f57b611e8691334fed98b7dc1f73163247bdccf5628a5d2c541fa0b7d2ee82"
compacted: false
heading_path: ["What About the Cursor? (a Digression)","Mouse Actions"]
symbol: null
address: null
asset_path: null
---

#### Mouse Actions  
Beyond moving the pointer, the basic mouse actions are clicking, pressing, and dragging.  
Clicking has two components: pushing down on the mouse button and then quickly releasing it while the mouse remains stationary (if the mouse moves, dragging—not just clicking—is what happens). Some uses of clicking: to select an object, to select an insertion point, to make a menu visible. The effect of clicking should be immediate and evident. If the function of the click is to initiate a command, the selection happens when the button is pressed, and the command is initiated when the button is released. Double clicking involves a second click that follows immediately after the end of a first click. Some uses of double clicking: to open an object, to select a larger object than one that can be selected by a single click. There's more about double clicking later in this chapter. Applications can also define triple clicking, but this is not recommended.  
**Pressing** means holding the mouse button down for a time while the mouse remains stationary. Pressing on the scroll bar's arrows, for example, causes scrolling until the user releases the mouse button. For certain kinds of objects, pressing on the object has the same effect as clicking it repeatedly. For example, *clicking* a scroll arrow causes a  
document to scroll one line; *pressing* on a scroll arrow causes the document to scroll continuously until the user releases the mouse button or reaches the end of the document.  
**Dragging** means pressing the mouse button, moving the mouse to a new position, and finally releasing the mouse button. Dragging can have different effects, depending on what's under the pointer when the mouse button is pressed. The uses of dragging include selecting blocks of text, choosing a menu item, selecting a range of objects, moving an object from one place to another, and shrinking or expanding an object.  
Some objects, especially graphic objects, can be moved by dragging. The application either moves the entire object, or attaches a dotted outline of the object to the pointer and moves the outline as the user moves the pointer (when the user releases the mouse button, the application redraws the complete object at the new location).  
An object being moved can be restricted to certain boundaries, such as the edges of a window. If the user moves the pointer outside the boundaries, the application stops drawing the dotted outline of the object. If the user releases the mouse button while the pointer is outside the boundaries, the object doesn't move. If, on the other hand, the user moves the pointer back within the boundaries again before releasing the mouse button, the outline is drawn again.  
In general, moving the mouse changes nothing except the location, and possibly the shape, of the pointer. (Pointer shape is discussed elsewhere in this book.) Pressing the mouse button indicates the intention to do something, and releasing the button completes the action. Pressing by itself should have no effect except in well-defined areas, such as scroll arrows, where it has the same effect as repeated clicking.  
Mouse-ahead (analogous to the keyboard's typeahead) saves, in a memory buffer, any mouse actions the user performs when the application isn't ready to process them. The application can then carry out these stored processes when it has time. Alternatively, the application can choose to ignore saved-up mouse actions, but should do so only to protect the user from possibly damaging consequences.