---
chunk_index: 2761
ref: "e72b60d5e689"
id: "e72b60d5e6893db69950e20d1c9e88d88cce1397b6b013394f786c71fca0b9e2"
slug: "full-document--automatic-scrolling"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2716, 2742]
token_estimate: 1055
content_sha256: "bc766589c591d91901a2b0a6549ebfa1edd2754a0db389df7a06ea0d3a4f1046"
compacted: false
heading_path: ["Window Behaviors","Scrolling a Window","Scroll Bars","Automatic Scrolling"]
symbol: null
address: null
asset_path: null
---

#### Automatic Scrolling

In all the discussions of scrolling behavior and appearance in the previous sections, the user controls scrolling behavior by deciding which control to use and how long to use it. Most of the time, the user should be in control. However, there are four cases where your application must scroll the document.

When your application performs an operation whose side effect is to make a new selection or move the insertion point, scroll the document to show the new selection.

For example, when the user searches for some text, your application locates the desired text. If this text appears in a part of the document that isn't currently visible, scroll the document to the location to show the selection. Another example might occur after the user pastes something. If the insertion point appears after the end of whatever was pasted, scroll the document until the selection and the new insertion point are visible. Figure 5-37 shows the effect of automatic scrolling.

**Figure 5-37** Automatic scrolling

![](images/_page_189_Picture_8.jpeg)

![](images/_page_189_Picture_9.jpeg)

- When the user enters information from the keyboard at the edge of a window, scroll the document automatically to incorporate and display the new information.
- The user's focus will be on the new information, so don't try to maintain the document's position and record the new information out of the user's view. Your application determines the distance to scroll. In general, a word processor scrolls one line of text, a database or spreadsheet scrolls one field. Graphics applications should scroll to display an entire object when possible. Otherwise, determine how quickly your application can redraw the window contents during scrolling and adjust the amount of scrolling to reduce the amount of flashing or redrawing that is necessary. Try to ensure that the scrolling is sufficiently fast that it allows users to see the information at a rate that's useful, but don't scroll so fast that people get lost.
- When the user moves the pointer past the edge of the window while holding down the mouse button to make an extended selection, scroll the document automatically in the direction the pointer moves. The rate of scrolling can be the same as if the user were pressing on the corresponding scroll arrow. In some cases, it makes sense to vary the scrolling speed so that it is faster as the user moves the pointer farther away from the window edge.
- Sometimes the user selects something, scrolls the document to a new location, and then tries to perform an operation on the selection. In this case, scroll the window so that the selection is showing before your application performs the operation. Showing the selection makes it clear to the user what is being changed.

Whenever your application scrolls a document automatically, avoid unnecessary scrolling. Users want to control the position of documents, so your application should move a document only as much as necessary. This means that if part of a selection is showing in the window after the user performs some operation, don't scroll at all. One exception to this rule is when the part of the selection that is hidden is more important than the part that is showing; then scroll to show the important part. For example, if a user has a large text selection, only the bottom of which is currently visible and the user types a character, your application must scroll to the location of the newly typed characters so they are visible.

If your application can scroll in one orientation to reveal the selection, don't scroll in both orientations. That is, if you can scroll vertically to show the selection, don't also scroll horizontally.

When you can show context on either side of a selection, it's useful to do so. It's also better to position a selection somewhere near the middle of a window than right up against a corner. When the selection is too large to show the entire selection in the window, it might be a good idea to show some context next to it rather than having the selection fill the window. For more information about document scrolling, see *Inside Macintosh: Macintosh Toolbox Essentials*.

Window Behaviors **167**