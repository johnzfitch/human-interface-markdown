<!-- Chunk 71 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 1390 -->
There are two important principles behind the Edit menu:  
- Anything the user can do, the user can also undo.
- Data can easily be moved from one part of <sup>a</sup> document to another part, from one document to another, and even between documents that are created by different applications or desk accessories. The Clipboard, a holding area for text or graphics, makes this possible.  
The Edit menu allows access to the operations that cut, copy, and paste selections, as well as to Undo, Select All, and Show Clipboard. You can add other items to the Edit menu if your application requires them—and if they're related to the standard items already there.  
All applications should support Undo, Cut, and Paste. This requires that the first five lines in the Edit menu be exactly as shown in Figure 3-36: Undo followed by <sup>a</sup> dotted line, then Cut, Copy, Paste, and Clear. Consistency in this menu is important even if your application doesn't itself make use of Undo, Cut, and Paste—these features are available to desk accessories only through the Edit menu.  
| U2J           |      |
|---------------|------|
| Undo          | 362  |
| Cut           | 3€H  |
| Copy          | 3€C  |
| Paste         | sen  |
| Clear         |      |
| Select<br>All |      |
|               |      |
| Show<br>Clipb | Dard |  
Figure 3-36 Standard Edit menu  
#### The Clipboard  
The Clipboard holds whatever is cut or copied from a document. Its contents stay intact when the user changes documents, opens <sup>a</sup> desk accessory, or leaves the application. An application can show the contents of the Clipboard in <sup>a</sup> window and can choose whether to have the Clipboard window open or closed when the application starts up.  
The Clipboard window looks like a document window. The user can see its contents but cannot edit them. In other respects, the Clipboard window behaves like any other window.  
Every time the user performs a Copy on the current selection, a copy of the selection replaces the previous contents of the Clipboard. The previous contents of the Clipboard remain available in case the user chooses Undo.  
The Clipboard is available to all applications that support Cut, Copy, and Paste. The user can see the Clipboard window by choosing Show Clipboard from the Edit menu. If the Clipboard window is already showing, the user can hide it by clicking the close box or choosing Hide Clipboard from the Edit menu. (Show Clipboard and Hide Clipboard are a single toggled item.)  
Because the content of the Clipboard doesn't change when the user moves from one application to another, or when the user opens <sup>a</sup> desk accessory, the Clipboard is used for transferring data among compatible applications and desk accessories.  
If the Clipboard file is moved from one disk to another, the contents move with it, replacing any existing Clipboard file on the target disk.  
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
#### Cut  
The user chooses Cut either to delete the current selection or to move it. A move is eventually completed by choosing Paste.  
When the user chooses Cut, the application removes the current selection from the document and puts it in the Clipboard, replacing the Clipboard's previous contents. The place where the selection used to be becomes the new selection; the visual implications of this vary among applications. For example, in text, the new selection is an insertion point; in an array, it's an empty but highlighted cell. If the user chooses Paste immediately after choosing Cut, the document isjust as it was before the Cut.  
The Apple-X key combination is reserved as a keyboard substitute for the Cut operation in the Edit menu and should be used for no other purpose.