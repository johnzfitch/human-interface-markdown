<!-- Chunk 63 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 3254 -->
Revert to Saved discards all changes made to the active documentsince the last time it was saved or opened. The document on disk is reopened. Before all this happens, an alert box is used to confmn that this is what the user wants. (This follows the principles that users be allowed to make informed decisions and change their minds.)  
![](images/_page_67_Picture_7.jpeg)  
**Figure** 27. A Revert to Saved Dialog Box  
#### *Page Setup*  
Page Setup lets the user specify printing parameters such as the paper size and printing orientation (different applications will provide different option as needed). These parameters are saved with the document when the document is saved.  
![](images/_page_68_Figure_1.jpeg)  
Figure 28. A Page Setup Dialog Box  
#### Print  
This lets the user specify various parameters, such as print quality and number of copies, and then prints the document. The parameters apply only to the current printing operation and are not saved with the document.  
![](images/_page_68_Figure_5.jpeg)  
Figure 29. A Print Dialog Box  
#### Quit  
This menu item lets the user leave the application and return to the Finder. If any open documents have been changed since the last time they were saved, the application presents the same alert box as for Close, once for each open document. If more than one document is open, applications should display, in the alert box, the name of each open document.  
#### The Edit Menu  
There are two important principles behind the Edit menu:  
- Anything the user can do, the user can also undo.
- Data can easily be moved from one part of a document to another part, from one document to another, and even between documents that are created by different  
applications or desk accessories. A system file called the Clipboard (a holding area for text or graphics) makes this possible.  
The Edit menu allows access to the operations that delete, move, and copy objects, as well as Undo, Select All, and Show Clipboard. You can add other items to the Edit menu if your application requires them—and if they're related to the standard items already there.  
All applications should support Undo and cut and paste. This requires that the first five lines in the Edit menu must be exactly as shown in Figure 30: Undo followed by a dotted line, then Cut, Copy, Paste, and Clear. This is important even if your application doesn't itself make use of undo and cut and paste—those features are available to desk accessories only through the Edit menu.  
| Edit           |      |  |  |
|----------------|------|--|--|
| Undo (lest)    | ₩Z   |  |  |
| 01             | 0011 |  |  |
| Cut            | *H   |  |  |
| Copy           | ₩C   |  |  |
| Paste          | ₩U   |  |  |
| Clear          |      |  |  |
| Select All     |      |  |  |
| Show Clipboard |      |  |  |  
Figure 30. Standard Edit Menu  
#### The Clipboard  
The Clipboard holds whatever is cut or copied from a document. Its contents stay intact when the user changes documents, opens a desk accessory, or leaves the application. An application can show the contents of the Clipboard in a window and can choose whether to have the Clipboard window open or closed when the application starts up.  
The Clipboard window looks like a document window. The user can see its contents but cannot edit them. In most other respects, the Clipboard window behaves just like any other window.  
Every time the user performs a Copy on the current selection, a copy of the selection replaces the previous contents of the Clipboard. The previous contents of the Clipboard remain available in case the user chooses Undo.  
Althought it appears to the user that there's only one Clipboard, each application can create its own. It is available to all applications that support Cut, Copy, and Paste. The user can see the Clipboard window by choosing Show Clipboard from the Edit menu. If the window is already showing, it's hidden by clicking the close box or choosing Hide Clipboard in the Edit menu. (Show Clipboard and Hide Clipboard are a single toggled item.)  
Because the content of the Clipboard doesn't change when the user moves from one application to another, or when the user opens a desk accessory, the Clipboard is used for transferring data among compatible applications and desk accessories.  
If the Clipboard file is moved from one disk to another, the contents move with it, replacing any existing Clipboard file on the target disk.  
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
#### Cut  
The user chooses Cut either to delete the current selection or to move it. A move is eventually completed by choosing Paste.  
When the user chooses Cut, the application removes the current selection from the document and puts it in the Clipboard, replacing the Clipboard's previous contents. The place where the selection used to be becomes the new selection; the visual implications of this vary among applications. For example, in text, the new selection is an insertion point; in an array, it's an empty but highlighted cell. If the user chooses Paste immediately after choosing Cut, the document is just as it was before the cut.  
The Apple-X key combination is reserved as a keyboard substitute for the Cut operation in the Edit menu and should be used for no other purpose.  
#### Copy  
Before the user can copy something, she must first select it. Copy puts a duplicate of the selection in the Clipboard, but the selection also remains in the document. The user can then choose Paste to insert the Clipboard's contents somewhere else.  
The Apple-C key combination is reserved as a keyboard substitute for Copy in the Edit menu and should be used for no other purpose.  
#### Paste  
Paste is the last stage of a move or copy operation. It inserts the contents of the Clipboard into the document, replacing the current selection. If there is no current selection, it's  
inserted at the insertion point (or at the application's equivalent of an insertion point). The user can choose Paste several times in a row to paste multiple copies. After a paste, the new selection is the object that was pasted, except in text, where it's an insertion point immediately after the pasted text. The Clipboard remains unchanged.  
The Apple-V key combination is reserved as a keyboard substitute for Paste in the Edit menu and should be used for no other purpose.  
#### Clear  
When the user makes a selection and then either chooses Clear from the Edit menu or presses the Backspace key or Clear key, the application deletes the highlighted selection. Unlike Cut and Copy, the Clear operation does not put the selection in the Clipboard. The Clipboard is unchanged and the new selection is the same as it would be after a Cut.  
#### Select All  
Select All selects every object in the document. In a word processing application, Select All selects every character.  
#### Show Clipboard  
Show Clipboard is a toggled item. When the Clipboard isn't displayed, it is *Show Clipboard*. If the user chooses *Show Clipboard*, the Clipboard window is displayed and the wording in the menu changes to *Hide Clipboard*.  
#### Font-Related Menus  
Three standard menus affect the appearance of text. The Font menu lets the user determine the font of a text selection or of the characters she's about to type. The FontSize menu lets the user determine the size, in points, of the characters. The Style menu lets the user determine such aspects of the text's appearance as boldface, italic, and so on.  
A font (also often called a typeface) is a set of typographical characters created with a consistent design. All the characters in a font share such features as the thickness of vertical and horizontal lines, the degree and position of curves, and the use of serifs. Serifs are fine lines added to the main strokes of a letter. The text of this book is set in various sizes and styles of a serif font. This sentence, on the other hand, is set in a sans serif font, which has no serifs.) The characters in a font can appear in many different point sizes, but all have the same general appearance, regardless of size. Because fonts can be either fixed-width or proportional, an application can't make assumptions about exactly how many characters will fit in a given area.  
#### Font Menu  
The Font menu lists only those fonts that are currently available. A check mark indicates which font is currently in effect.  
![](images/_page_73_Picture_1.jpeg)  
Figure 33. A Font Menu with Some Common Fonts  
#### *FontSize Menu*  
Font sizes are measured in points. A point is a typographical unit of measure equivalent to In2 inch. The FontSize menu lists the nine standard sizes. The font size currently in effect is indicated with a check mark. (See Figure 34.) Not every font is available in all sizes; the sizes that are available for the selected font are shown outlined in the FontSize menu. A font can be scaled to the other sizes, but scaled fonts usually suffer in appearance on the screen and when printed by some kinds of printers.  
This sentence is in lO-point type. This sentence is in 12-point type. This sentence is in 14 point type.  
![](images/_page_73_Picture_6.jpeg)  
Figure 34. FontSize Menu with Standard Font Sizes  
If there's insufficient room in the menu bar for the word FontSize, it can be abbreviated to Size. If there's insufficient room for both a Font menu and a Size menu, the sizes can be put at the end of the Style menu.  
#### Style Menu  
Text-oriented application programs, such as word processors, have a Style menu that is almost a standard menu. See Figure 35.  
The operations in the standard Style menu are Plain Text, Bold, Italic, Underline, Outline, and Shadow. All except Plain Text are accumulating attributes. This means that the user can choose all of them, none of them, or any combination of them. It is important that each attribute can be individually toggled on and off. If a user has accumulated several attributes (bold, italic, and underline for example), and wants to eliminate bold and italic (keeping underline), he doesn't want to have to choose Plain (which turns off all three attributes) then start over by choosing underline.  
A attribute that's in effect for the current selection is preceded, in the Style menu, by a check mark. The absence of the check mark indicates that the attribute is not in effect for the current selection. Choosing Plain Text cancels all the other choices.  
| Style            |    |
|------------------|----|
| √Plain Text      | ₩P |
| Bold             | ₩B |
| Italic           | ЖI |
| <u>Underline</u> | ₩U |
| Outline          |    |
| Spagom           |    |  
Figure 35. Standard Style Menu  
Other menus use plain 12-point Chicago for their text, but the Style menu can be self-documenting by using, for example, shadowed 12-point Chicago to list the shadowed attribute. Apple key combinations can be used as keyboard shortcuts to the Style menu.