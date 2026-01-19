<!-- Chunk 100 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 1896 -->
This section covers the topic of selection according to the *kind* of data involved: text, graphics, and arrays.  
#### Selections in text  
In most applications, the user is required at some point to edit text. The principle of consistency (both within and among applications) requires that text be selected and edited in a consistent way, regardless of where it appears.  
A block of text is a string of characters. A text selection is a substring of this string, which can have any length from zero characters to the whole block. Each of the text selection methods selects a different kind of substring. Figure 56 shows different kinds of text selections.  
| Insertion point            | Life is just a bowl of Apples! |
|----------------------------|--------------------------------|
| Range of characters        | Life is just a bowl of Apples! |
| Word                       | Life is just a bowl of Apples! |
| Range of words             | Life is just a bowl of Apples! |
| Discontinuous<br>selection | Life is ust a bowl of Apples   |  
Figure 56 Text selections  
The **insertion point** is a zero-length text selection. The user establishes the location of the insertion point by clicking somewhere in the text. The insertion point then appears at the nearest character boundary. If the user clicks anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character (unless the document is filled with space characters).  
The insertion point shows where text will be inserted when the user begins typing, or where cut or copied data (the contents of the Clipboard) will be pasted. As each character is typed, it is inserted to the left of the insertion point.  
If, between mouse-down (the moment the mouse button is pressed) and mouse-up (the moment the button is released), the user drags (moves the pointer more than about half the width of a character), the characters that were dragged across become selected (the selection is a *range selection* rather than an insertion point).  
The user selects a whole *word* by double-clicking somewhere within that word. If the user begins a double-click sequence, but then drags the mouse between the mouse-down and the mouse-up of the second click, the selection becomes a range of words rather than a single word. As the pointer moves, the application highlights or unhighlights a whole word at a time.  
A word, or range of words can also be selected in the same way as any other range; whether this type of selection is treated as a range of characters or as a range of words depends on the operation. For example, in MacWrite, a range of individual characters that happens to coincide with a range of words is treated like characters for purposes of extending a selection, but is treated like words for purposes of "intelligent cut and paste" (described later in this chapter under "Editing text").  
The following definition of a *word* applies to the United States and Canada. In other countries, the definition differs to reflect local formats for numbers, dates, and currency. A word is defined as any continuous string that contains only the following characters:  
- a letter
- a digit
- a nonbreaking space (Option-space or Apple-space)
- a currency symbol (\$, ¢, £, or ¥)
- a percent sign
- a comma between digits
- a period before a digit
- an apostrophe between letters or digits
- a hyphen, but not a minus sign (Option-hyphen) or a dash (Option-Shift-hyphen)  
If the user double-clicks over any character *not* on the list above, only that character is selected.  
These are examples of words:  
\$123,456.78  
shouldn't  
3 1/2 (with a nonbreaking space)  
5%  
These are examples of strings treated as more than one word:  
7/10/6  
blue cheese (with a breaking space)  
"Wow!" (The quotation marks and exclamation point aren't part of the word.)  
In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parenthesis in a pair, as well as all the characters between them, by double-clicking on either one of them. The same feature could be implemented for both square and curly brackets. This would mean that the user could select the entire expression  
$[x+y-(4*3)\land (n-1)]$  
simply by double clicking on [ or ].  
The user selects a range of text by dragging through the range. A range can be a range of characters, words, lines, or paragraphs, as defined by the application.  
If the user extends the range, the way the range is extended depends on what kind of range it is. If it's a range of individual characters, it can be extended one character at a time. If it's a range of words (including a single word), it's extended only by whole words.  
#### Making a selection with arrow keys  
To use arrow keys to make a text selection, the user holds down Shift while pressing an arrow key. If it's important that your Macintosh application makes use of the numeric keypad, you shouldn't use these Shift-arrow key combinations. This is because the key codes for the four Shift-arrow key combinations are the same as those for the keypad's +, \*, /, and = keys. If the use of a Shift-arrow key combination for making selections is more important to your application than is the numeric keypad, the following paragraphs tell how it should work.  
After a Shift-arrow key combination has been pressed, the insertion point moves and the range over which it moves becomes selected. If both the Shift key and another modifier key are held down, the insertion point moves as defined for the particular modifier key, and the range over which the insertion point moves becomes selected. For example, Option-Shift-Left Arrow selects the whole word that contains the character to the left of the insertion point (just like double clicking on a word).  
A selection made by using the mouse is no different from one made by using arrow keys. A selection started with the mouse can be extended by using Shift and Left or Right Arrow.  
In a text application, pressing Shift and either Left Arrow or Right Arrow selects a single character. Assuming that the Left Arrow key was used, the anchor point of the selection is on the right side of the selection, the active end on the left. Each subsequent Shift–Left Arrow adds another character to the left side of the selection. A Shift–Right Arrow at this point shrinks the selection. Figure 57 summarizes these actions.  
| 1. | Insertion point is within a word: | word          |
|----|-----------------------------------|---------------|
| 2. | Shift- is pressed:                | w <b>g</b> rd |
| 3. | Another Shift- :                  | <b>w</b> rd   |
| 4. | Shift-                            | ward          |
| 5. | Three more times Shift-           | wo            |  
Figure 57
Selecting with Shift-arrow keys  
Pressing Option–Shift and either Left Arrow or Right Arrow (in a text application) selects the entire word containing the character to the left of the insertion point. Assuming Left Arrow were pressed, the anchor point is at the right end of the word, the active end at the left. Each subsequent Option–Shift–Left Arrow adds another word to the left end of the selection, as shown in Figure 58.  
1. Insertion point is within a word:  
another word  
2. Option-Shift- is pressed:  
another word  
3. Another Option-Shift-  
another word  
Figure 58
Selecting with Option-Shift-arrow keys