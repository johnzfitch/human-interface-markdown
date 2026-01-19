---
chunk_index: 1367
ref: "fcb9018a889a"
id: "fcb9018a889ab0baa166146360128ef8e3e97642df5aff154d3a49c6adb2c64f"
slug: "full-document--undo"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1301, 1320]
token_estimate: 419
content_sha256: "a8c3e1a7e5d7ce3b4c4eaa12c96d306d00384ce0ff238bfe21cd9a798ba759c9"
compacted: false
heading_path: ["About MacPaint...","The Clipboard","Undo"]
symbol: null
address: null
asset_path: null
---

#### Undo

The Undo menu item reverses the effect of the previous operation. Not all operations can be undone. The application determines which operations can be undone. The general rule is that operations that change the contents of the document can be undone, whereas operations that don't change the contents of the document cannot be undone.

Most menu items (whether chosen from the menu or by a keyboard equivalent) can be undone. A typing sequence (any sequence of characters typed from the keyboard or numeric keypad, including Backspace, Return, and Tab, but *not* including keyboard equivalents of menu items) can also be undone.

Operations that can't be undone include selecting, scrolling, and splitting the window or changing a window's size or location. None of these operations interrupts a typing sequence. For example, if the user types a few characters and then scrolls the document, an Undo operation doesn't undo the scrolling but *does* undo the typing. Whenever the location affected by the Undo operation isn't currently showing on the screen, the application should scroll the document so the user can see the effect of the Undo.

The actual wording of the Undo line, as it appears in the Edit menu, is *Undo Typing* or *Undo Cut*—whatever the last undoable operation was. If the last operation can't be undone, the line reads simply *Undo* and is dimmed to indicate that it's disabled.

Figure 40 illustrates Undo and Redo in an Edit menu.

80

![](images/_page_90_Figure_0.jpeg)

Undo and Redoin an Edit menu

The Apple-Z key combination is reserved as a keyboard substitute for Undo/Redo in the Edit menu and should be used for no other purpose.