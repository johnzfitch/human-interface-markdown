<!-- Chunk 123 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 200 -->
When the user presses the Delete (or Backspace) key, one of two things happens:  
- If text is selected, the entire selection is deleted.
- If there is no current selection, the character preceding the insertion point is deleted.  
In either case, the insertion point replaces the deleted character or characters in the document. The deleted characters don't go into the Clipboard, but the user can undo the deletion by immediately choosing Undo from the Edit menu.  
You can also implement the keyboard combination Option-Delete (or Backspace) to delete the word that currently contains the insertion point. Be sure to document this behavior if you implement it.  
If a keyboard has a Forward Delete (Del) key, the character following the insertion point is deleted each time the user presses the key.