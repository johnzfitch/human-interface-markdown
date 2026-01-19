<!-- Chunk 118 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 802 -->
A block of text is a string of characters. A text selection is a substring of this string, which has any length from zero characters to the whole block.  
The **insertion point** (a zero-length text selection) shows where text will be inserted when the user starts typing, or where the contents of the Clipboard will be pasted. The user establishes the location of the insertion point by clicking somewhere in the text; the insertion point appears at the nearest character boundary. If the user clicks  
anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character.  
#### <span id="page-146-0"></span>Selecting With the Mouse  
The user can select a range of text by dragging. A range can consist of characters, words, lines, or paragraphs, as defined by the application.  
In text fields, clicking should perform the following actions:  
- Single-clicking places the insertion point at the pointer's location in the text.
- Double-clicking within a word selects the word. The selection should provide "smart" behavior; if the user deletes the selected word, for example, the space after the word should also be deleted.
- Double-clicking in a space selects the space.
- Triple-clicking selects the next logical unit, as defined by the application. In a word-processing document, triple-clicking in a word selects the paragraph containing the word. In a table, triple-clicking selects the cell.  
#### <span id="page-146-2"></span><span id="page-146-1"></span>What Constitutes a Word  
The following definition of a word applies in the United States, Canada, and some other countries. In many countries, the definition differs to reflect local formats for numbers, dates, and currency. Double-clicking a character *not* in the list below results in the selection of only that character.  
A word is defined as any continuous string that contains any of the following characters:  
- a letter
- a digit
- a nonbreaking space (Option-space or Command-space)
- a currency symbol (\$, ¢, £, ¥)
- a percent sign
- a comma between digits
- a period before a digit  
Selecting **147**  
- an apostrophe between letters or digits
- a hyphen, but not Option-hyphen (–) or Option-Shift-hyphen (—)  
These are examples of words:  
- \$123,456.78
- shouldn't
- 3 1/2 (with a nonbreaking space)
- .5%  
These are examples of strings treated as more than one word:  
- 7/10/6
- blue cheese (with a regular space)
- "Wow!" (The quotation marks and exclamation point are not part of the word.)  
In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parentheses (or braces or brackets) in a pair, as well as all the characters between them, by double-clicking either one of them. That would mean that a user could select the entire expression  
$$[x+y-(4*3)^{n-1}]$$  
by double-clicking [ or ].  
#### <span id="page-147-0"></span>Selecting Text With the Arrow Keys  
See ["Extending Text Selection With the Shift and Arrow Keys" \(page 134\)](#page-133-3).