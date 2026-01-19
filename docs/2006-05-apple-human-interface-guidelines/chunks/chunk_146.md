<!-- Chunk 146 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 235 -->
When the user presses the Delete (or Backspace) key, one of two things happens:  
- If text is selected, the entire selection is deleted.
- If there is no current selection, the character preceding the insertion point is deleted.  
In either case, the insertion point replaces the deleted character or characters in the document. The deleted characters don't go on to the Clipboard, but the user can undo the deletion by immediately choosing Undo from the Edit menu.  
You can also implement the keyboard combination Option-Delete (or Option-Backspace) to delete the word that currently contains the insertion point or to delete the part of the word to the left of the insertion point. Be sure to document this behavior if you implement it.  
<span id="page-108-9"></span><span id="page-108-3"></span>If a keyboard has a Forward Delete (Fwd Del) key, the character following the insertion point is deleted each time the user presses the key.