---
chunk_index: 1982
ref: "2d0ffecc4d21"
id: "2d0ffecc4d21cc89a6516b417b564111ecc98e4c837cefa130039572b30e8232"
slug: "full-document--undo"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1773, 1792]
token_estimate: 462
content_sha256: "10776505b2b1cf74f924ee7c876180531b13ab6df3e53ffd3b4fe158c95b6fe4"
compacted: false
heading_path: ["The Edit menu","The Clipboard","Undo"]
symbol: null
address: null
asset_path: null
---

#### Undo

The Undo menu item reverses the effect of the previous operation. Not all operations can be undone. The application determines which operations can be undone. The general rule is that operations that change the contents of the document can be undone, whereas operations that don't change the contents of the document cannot be undone.

Most menu items (whether chosen from the menu or by <sup>a</sup> keyboard equivalent) can be undone. A typing sequence (any sequence of characters typed from the keyboard or numeric keypad, including Backspace, Return, and Tab, but not including keyboard equivalents of menu items) can also be undone.

Operations that can't be undone include selecting, scrolling, and splitting the window or changing a window's size or location. None of these operations interrupts a typing sequence. For example, if the user types a few characters and then scrolls the document, an Undo operation doesn't undo the scrolling but does undo the typing. Whenever the location affected by the Undo operation isn't currently showing on the screen, the application should scroll the document so the user can see the effect of the Undo.

The actual wording of the Undo line, as it appears in the Edit menu, is Undo Typing or Undo Cut—whatever the last undoable operation was. If the last operation can't be undone, the line reads simply Undo and is dimmed to indicate that it's disabled.

Figure 3-37 illustrates Undo and Redo in an Edit menu.

![](images/_page_95_Picture_6.jpeg)

Figure 3-37 Undo and Redo inan Edit menu

If the last operation was Undo, the menu item is Redo xxx, where xxx is the operation that was undone. If the user chooses Redo, the Undo is undone.

The Apple-Z key combination is reserved as <sup>a</sup> keyboard substitute for Undo/Redo in the Edit menu and should be used for no other purpose.