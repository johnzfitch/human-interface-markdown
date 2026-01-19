<!-- Chunk 75 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 2136 -->
The Clipboard holds whatever is cut or copied from a document. Its contents stay intact when the user changes documents, opens a desk accessory, or leaves the application. An application can show the contents of the Clipboard in a window and can choose whether to have the Clipboard window open or closed when the application starts up.  
The Clipboard window looks like a document window. The user can see its contents but cannot edit them. In other respects, the Clipboard window behaves like any other window.  
Every time the user performs a Copy on the current selection, a copy of the selection replaces the previous contents of the Clipboard. The previous contents of the Clipboard remain available in case the user chooses Undo.  
The Clipboard is available to all applications that support Cut, Copy, and Paste. The user can see the Clipboard window by choosing Show Clipboard from the Edit menu. If the Clipboard window is already showing, the user can hide it by clicking the close box or choosing Hide Clipboard in the Edit menu. (Show Clipboard and Hide Clipboard are a single toggled item.)  
Because the content of the Clipboard doesn't change when the user moves from one application to another, or when the user opens a desk accessory, the Clipboard is used for transferring data among compatible applications and desk accessories.  
If the Clipboard file is moved from one disk to another, the contents move with it, replacing any existing Clipboard file on the target disk.  
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
#### Cut  
The user chooses Cut either to delete the current selection or to move it. A move is eventually completed by choosing Paste.  
When the user chooses Cut, the application removes the current selection from the document and puts it in the Clipboard, replacing the Clipboard's previous contents. The place where the selection used to be becomes the new selection; the visual implications of this vary among applications. For example, in text, the new selection is an insertion point; in an array, it's an empty but highlighted cell. If the user chooses Paste immediately after choosing Cut, the document is just as it was before the Cut.  
The Apple-X key combination is reserved as a keyboard substitute for the Cut operation in the Edit menu and should be used for no other purpose.  
#### Copy  
Before copying something, the user must first select it. Copy puts a duplicate of the selection in the Clipboard, but the selection also remains in the document. The user can then move the insertion point and choose Paste to insert the Clipboard's contents somewhere else.  
The Apple-C key combination is reserved as a keyboard substitute for Copy in the Edit menu and should be used for no other purpose.  
#### Paste  
Paste is the last stage of a move or copy operation. It inserts the contents of the Clipboard into the document, replacing the current selection. If there is no current selection, it's inserted at the insertion point. The user can choose Paste several times in a row to paste multiple copies. After a paste, the new selection is the object that was pasted, except in text, where it's an insertion point immediately after the pasted text. The Clipboard remains unchanged.  
The Apple-V key combination is reserved as a keyboard substitute for Paste in the Edit menu and should be used for no other purpose.  
#### Clear  
When the user makes a selection and then either chooses Clear from the Edit menu or presses the Backspace key (Delete key on some keyboards) or the Clear key, the application deletes the highlighted selection. Unlike Cut and Copy, the Clear operation does not put the selection in the Clipboard. The Clipboard is unchanged and the new selection is the same as it would be after a cut.  
#### Select all  
Select All selects every object in the document. In a word processing application, Select All selects every character as well as all graphics in the document (making it very easy to reformat or copy an entire document).  
#### **Show Clipboard**  
Show Clipboard is a toggled item. When the Clipboard isn't displayed, it is *Show Clipboard*. If the user chooses *Show Clipboard*, the Clipboard window is displayed and the wording in the menu changes to *Hide Clipboard*.  
#### Font-related menus  
Three standard menus affect the appearance of text. The Font menu lets the user determine the font of a text selection or of the characters about to be typed. The FontSize menu lets the user determine the size, in points, of the characters. The Style menu lets the user determine such aspects of the text's appearance as boldface, italic, and so on.  
A font (also often called a typeface) is a set of typographical characters created with a consistent design. All the characters in a font share such features as the thickness of vertical and horizontal lines, the degree and position of curves, and the use of serifs. Serifs are fine lines added to the main strokes of a letter. The text of this book is set in various sizes and styles of a serif font. The section headings in this book, on the other hand, are set in a sans serif font, which has no serifs. The characters in a font can appear in many different point sizes, but all have the same general appearance, regardless of size. Because fonts can be either fixed-width or proportional, an application can't make assumptions about exactly how many characters will fit in a given area.  
#### Font menu  
The Font menu lists the fonts that are currently available. A check mark indicates which font is currently in effect. Figure 41 illustrates a font menu with some common Macintosh fonts  
Font
Athens
Chicago
Geneva
London
Monaco
New York
Venice  
**Figure 41**A Font menu with some common Macintosh fonts  
#### FontSize menu  
Font sizes are measured in **points**. A point is a typographical unit of measure equivalent to 1/72 inch. The FontSize menu lists the nine standard available sizes. The font size currently in effect is indicated with a check mark. (See Figure 42.) Not every font is available in all sizes; the sizes that are available for the selected font are shown outlined in the FontSize menu. A font can be **scaled** to the other sizes, but scaled fonts usually suffer in appearance on the screen and when printed by some kinds of printers.  
This sentence is in 10-point type. The chapter title on the first page of this chapter is in 18-point type.  
| FontSize    |  |
|-------------|--|
| 9 point     |  |
| 10          |  |
| <b>√</b> 12 |  |
| 14          |  |
| 18          |  |
| 24          |  |
| 36          |  |
| 48          |  |
| 72          |  |  
Figure 42
FontSize menu with standard font sizes  
If there's insufficient room in the menu bar for the word FontSize, it can be abbreviated to Size. If there's insufficient room for both a Font menu and a Size menu, the sizes can be put at the end of the Style menu.