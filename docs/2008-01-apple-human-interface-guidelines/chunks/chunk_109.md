<!-- Chunk 109 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 553 -->
The user can select a range of text by dragging. A range can consist of characters, words, lines, or paragraphs, as defined by the application.  
In text fields, clicking should perform the following actions:  
- <span id="page-114-1"></span>■ Single-clicking places the insertion point at the pointer's location in the text.
- Double-clicking within a word selects the word. The selection should provide "smart" behavior; if the user deletes the selectedword, for example, the space after theword should also be deleted.
- Double-clicking in a space selects the space.
- <span id="page-114-0"></span>■ Triple-clicking selects the next logical unit, as defined by the application. In a word-processing document, triple-clicking in a word selects the paragraph containing the word.  
#### <span id="page-114-2"></span>What Constitutes a Word  
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
In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parentheses (or braces or brackets) in a pair, aswell as all the characters between them, by double-clicking either one of them. That would mean that a user could select the entire expression  
[*x*+*y*–(4\*3)^(*n*–1)]  
by double-clicking [ or ].