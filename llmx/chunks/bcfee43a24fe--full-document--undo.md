---
chunk_index: 925
ref: "bcfee43a24fe"
id: "bcfee43a24fed35f0f690ead77979756f9a8000a8e9ea98688b14465284f6106"
slug: "full-document--undo"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1576, 1604]
token_estimate: 522
content_sha256: "b712497d26a3a11c5d5b6c8599f804de765c01bbff7012e9de4fe1c1f551559e"
compacted: false
heading_path: ["Standard Menus","The Apple **Menu**","*Revert to Saved*","Undo"]
symbol: null
address: null
asset_path: null
---

#### Undo

The Undo menu item reverses the effect of the previous operation. Not all operations can be undone. The application determines *which* operations can be undone. The general rule is that operations that change the contents of the document can be undone, whereas operations that don't change the contents of the document cannot be undone.

Most menu items (whether chosen from the menu or by a keyboard equivalent) can be undone. A typing sequence (any sequence of characters typed from the keyboard or numeric keypad, including Backspace, Return, and Tab, but *not* including keyboard equivalents of menu items) can also be undone.

Operations that can't be undone include selecting, scrolling, and splitting the window or changing a window's size or location. None of these operations interrupts a typing sequence. For example, if the user types a few characters and then scrolls the document, an Undo operation doesn't undo the scrolling but *does* undo the typing. Whenever the location affected by the Undo operation isn't currently showing on the screen, the application should scroll the document so the user can see the effect of the Undo.

The actual wording of the Undo line, as it appears in the Edit menu, is *Undo Typing* or *Undo Cut*—whatever the last undoable operation was. If the last operation can't be undone, the line reads simply *Undo* and is dimmed to indicate that it's disabled.

| Edit<br>Vndo Typing #2 |    |  |
|------------------------|----|--|
| Cut                    | жн |  |
| Сору                   | ₩C |  |
| Paste                  | ₩U |  |
| Clear                  |    |  |
| Select All             |    |  |
| Show Clipboard         |    |  |

Figure 31. Undo in an Edit Menu

If the last operation was Undo, the menu item is *Redo xxx*, where *xxx* is the operation that was undone. If this item is chosen, the Undo is undone.

![](images/_page_71_Picture_1.jpeg)

Figure 32. Redo in an Edit Menu

The Apple-Z key combination is reserved as a keyboard substitute for Undo/Redo in the Edit menu and should be used for no other purpose.