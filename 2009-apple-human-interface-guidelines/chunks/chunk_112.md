<!-- Chunk 112 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1019 -->
<span id="page-114-3"></span>A block of text is a string of characters. A text selection is a substring of this string, which has any length from zero characters to the whole block.  
The **insertion point** (a zero-length text selection) shows where text will be inserted when the user starts typing, or where the contents of the Clipboard will be pasted. The user establishesthe location of the insertion point by clicking somewhere in the text; the insertion point appears at the nearest character boundary. If the user clicks anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character.  
Selected text in a window is highlighted with the color chosen by the user in Appearance preferences. When the window becomes inactive, the text should remain highlighted, but in the secondary color, which is a percentage of the original highlight color. Both Carbon and Cocoa provide a way to return the current highlight color, as well as other important colors in the user interface. Your application should use these defined colors in any custom controls you create, rather than hard-coding specific color values.  
#### Selecting With the Mouse  
The user can select a range of text by dragging. A range can consist of characters, words, lines, or paragraphs, as defined by the application.  
In text fields, clicking should perform the following actions:  
- <span id="page-114-2"></span>● Single-clicking places the insertion point at the pointer's location in the text.
- Double-clicking within a word selects the word. The selection should provide "smart" behavior; if the user deletes the selected word, for example, the space after the word should also be deleted.
- Double-clicking in a space selects the space.
- Triple-clicking selectsthe next logical unit, as defined by the application. In a word-processing document, triple-clicking in a word selects the paragraph containing the word.  
<span id="page-114-1"></span>Note that a paragraph usually includes a trailing terminator, such as a Return. Triple-clicking a word in a paragraph highlights the entire paragraph, including all space on the last line that appears between the trailing terminator and the edge of the field or window. This gives the user a visual reminder that the selected text includes a trailing terminator.  
#### <span id="page-114-4"></span>What Constitutes a Word  
The following definition of a word applies in the United States, Canada, and some other countries. In many countries, the definition differs to reflect local formats for numbers, dates, and currency. Double-clicking a character *not* in the list below results in the selection of only that character.  
A word is defined as any continuous string that contains any of the following characters:  
- A letter
- A digit  
- A nonbreaking space (Option–Space bar or Command–Space bar)
- A currency symbol (\$, ¢, £, ¥)
- A percent sign
- A comma between digits
- A period before a digit
- An apostrophe between letters or digits
- A hyphen, but not an en dash (Option–hyphen) or em dash (Shift–Option–hyphen)  
These are examples of words:  
- \$123,456.78
- shouldn't
- 3 1/2 (with a nonbreaking space)
- 0.5%  
These are examples of strings treated as more than one word:  
- 7/10/6
- Blue cheese (with a regular space)
- "Wow!" (The quotation marks and exclamation point are not part of the word.)  
In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parentheses (or braces or brackets) in a pair, as well as all the characters between them, by double-clicking either one of them. That would mean that a user could select the entire expression  
```
[x+y–(4*3)^(n–1)]
```  
by double-clicking [ or ].  
#### <span id="page-115-0"></span>Selecting Text With the Arrow Keys  
See ["Extending](#page-103-1) Text Selection With the Shift and Arrow Keys" (page 104)