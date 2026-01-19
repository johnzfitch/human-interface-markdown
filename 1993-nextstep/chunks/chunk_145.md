<!-- Chunk 145 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 1048 -->
| Edit               |
|--------------------|
|                    |
|                    |
|                    |
|                    |
|                    |
|                    |
|                    |
|                    |
|                    |
|                    |
| 1 Check Spelling   |
| [seled A Ii<br>. a |  
The Edit menu contains commands that alter the selection in the current key window (or in the main window if the key window doesn't respond to the command). Each command should be dimmed when it can't operate on the current selection.  
| Command | Action                                                              |
|---------|---------------------------------------------------------------------|
| Cut     | Deletes the current selection and copies it to the pasteboard.      |
| Copy    | Copies the current selection to the pasteboard without deleting it. |
| Paste   | Replaces the current selection with the contents of the pasteboard. |
|         | ( continued)                                                        |  
| Command        | Action                                                                                                                                                                                                                                               |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Paste As       | Attaches a submenu that permits the user to paste the current<br>contents of the pasteboard into the document in a specified data type.<br>The submenu lists the possible data types, as discussed in "The Paste<br>As Menu," later in this chapter. |
| Link           | Attaches the Link menu, which contains commands for<br>manipulating linked information. See "The Link Menu," later in<br>this chapter.                                                                                                               |
| Delete         | Deletes the current selection without copying it to the pasteboard<br>(thus leaving the contents of the pasteboard intact). The Delete key<br>has the same effect.                                                                                   |
| Undo           | Undoes the last editing change. This usually means all changes<br>since the user last made a selection, including the selection of an<br>insertion point.                                                                                            |
| Find           | Attaches the Find menu, which contains commands related to the<br>Find panel. See "The Find Menu," later in this chapter.                                                                                                                            |
| Spelling       | Brings up the Spelling panel.                                                                                                                                                                                                                        |
| Check Spelling | Finds the next misspelled word without bringing up the Spelling<br>panel.                                                                                                                                                                            |
| Select All     | Makes the entire contents of the file the current selection.                                                                                                                                                                                         |  
Applications that permit the user to edit text or graphics should support at least the Cut, Copy, Paste, and Select All commands. It's strongly recommended that you also implement the Undo command.  
#### **Programming Note: The Edit Menu**  
To get this menu, you can just drag it in from the Palettes window of Interface Builder. It's already hooked up to the Text object, which automatically provides all the menu's functionality except for Find, Paste As, Link, and Undo.