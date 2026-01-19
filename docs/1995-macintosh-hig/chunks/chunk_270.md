<!-- Chunk 270 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 226 -->
When the user presses the Delete (or Backspace) key, one of two things happens:  
- If the current selection has one or more characters, it's deleted. This behavior is equivalent to choosing Clear from the Edit menu.
- If there is no current selection, but only an insertion point, the character preceding the insertion point is deleted.  
In either case, the insertion point replaces the deleted character or characters in the document. The deleted characters don't go into the Clipboard, but the user can undo the deletion by immediately choosing Undo from the Edit menu.  
You can also implement the keyboard combination Option-Delete (Backspace) to delete the word that currently contains the insertion point. Be sure to document this behavior if you implement it.  
If a keyboard has a Forward Delete (Del) key, the character following the insertion point is deleted each time the user presses the key.