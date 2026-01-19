<!-- Chunk 110 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 2453 -->
Apple keyboards have four arrow keys: Up Arrow, Down Arrow, Left Arrow, and Right Arrow. They can be used alone or in combination with other keys. Keyboard combinations using the arrow keys should be used only for shortcuts for mouse actions. It is *never* appropriate to implement only a keyboard combination and not provide a mouse-based way to perform the same action.  
#### <span id="page-130-5"></span><span id="page-130-3"></span>Appropriate Uses for the Arrow Keys  
You can use arrow keys in these ways:  
■ In text, the arrow keys move the insertion point. When used with the Shift key, they extend or shrink the selection. If the user makes a selection and then presses the Right Arrow or Left Arrow, shrink the selection to zero length and place the insertion point at the right or left edge of the selection.  
The Keyboard **131**  
#### User Input  
- In lists, the arrow keys change the selection.
- In a graphics application, the arrow keys can be used to move a selected object the smallest possible increment (one pixel or one grid unit).  
Don't use the arrow keys to  
- move the mouse pointer onscreen
- duplicate the function of the scroll bars  
If it's important for your application to make use of the numeric keypad, don't use the Shift–arrow key combinations to extend text selections; the keypad's codes for the four Shift–arrow key combinations are the same as those for the keypad's +, \*, /, and = keys.  
#### <span id="page-131-1"></span><span id="page-131-0"></span>Moving the Insertion Point  
<span id="page-131-2"></span>When the insertion point moves vertically in a text document, its horizontal position is maintained in terms of screen pixels, not characters (in other words, the insertion point could move from the twenty-fifth character in a line down to the fiftieth character, depending on the font and size). As the insertion point moves from line to line, keep it as close as possible to its original horizontal position, moving it slightly left or right to the nearest new character boundary.  
The Option and Command keys are used as semantic modifiers with the arrow keys. As a general rule, the Option key increases the size of the semantic unit by one compared to the arrow keys alone, and Command key enlarges the semantic unit again. (The application determines what the semantic units are. In a word processor, typically the units are characters, words, lines, paragraphs, and documents. In a spreadsheet, a basic semantic unit could be a cell.)  
#### User Input  
[Table 8-1](#page-132-1) describes the appropriate behavior of the arrow keys in text documents and fields. In some cases, the behavior describes what happens when the indicated keys are pressed more than once in succession.  
<span id="page-132-2"></span><span id="page-132-1"></span><span id="page-132-0"></span>**Table 8-1** Arrow key behaviors  
| Key                 | Moves insertion point                                                                                                                         |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| Right Arrow         | One character to the right                                                                                                                    |
| Left Arrow          | One character to the left                                                                                                                     |
| Up Arrow            | To the line above, to the nearest character boundary<br>at the same horizontal location                                                       |
| Down Arrow          | To the line below, to the nearest character boundary<br>at the same horizontal location                                                       |
| Option–Right Arrow  | To end of current word, then to the end of the next<br>word                                                                                   |
| Option–Left Arrow   | To the beginning of the current word, then to the<br>beginning of the previous word                                                           |
| Option–Up Arrow     | To the beginning of the current paragraph, then to the<br>beginning of the previous paragraph                                                 |
| Option–Down Arrow   | To the end of the current paragraph, then to the end<br>of the next paragraph (not to the blank line after the<br>paragraph, if there is one) |
| Command–Right Arrow | To the next semantic unit, typically the end of the<br>current line, then the end of the next line                                            |
| Command–Left Arrow  | To the previous semantic unit, typically the beginning<br>of the current line                                                                 |
| Command–Up Arrow    | Upward in the next semantic unit, typically the<br>beginning of the document                                                                  |
| Command–Down Arrow  | Downward in the next semantic unit, typically the<br>end of the document                                                                      |  
The Keyboard **133**  
#### <span id="page-133-4"></span><span id="page-133-3"></span><span id="page-133-0"></span>Extending Text Selection With the Shift and Arrow Keys  
[Table 8-2](#page-133-2) describes how to extend text selection by pressing the Shift key with the arrow keys.  
If no text is selected, the extension begins at the insertion point. If text is selected by dragging, then the extension begins at the selection boundary. For example, in the phrase *stop time,* if the user places the insertion point between the "s" and "t" and then presses Shift–Option–Right Arrow, *top* is selected. However, if the user double-clicks so that the whole word is selected, and then extends the selection left or up, it's as if the insertion point were before the "s." If the user extends the selection right or down, it's as if the insertion point were between the "p" and the space after the word.  
Reversing the direction of the selection deselects the appropriate unit. In the previous example, if the word *stop* is selected and the user presses Shift–Option–Right Arrow, so that *stop time* is selected, and then presses Shift–Option–Left Arrow, *time* is deselected and *stop* remains selected.  
<span id="page-133-2"></span><span id="page-133-1"></span>**Table 8-2** Extending text selection with the Shift and arrow keys  
| Keys                     | Extends selection                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------|
| Shift–Right Arrow        | One character to the right                                                                |
| Shift–Left Arrow         | One character to the left                                                                 |
| Shift–Up Arrow           | To the line above, to the nearest character<br>boundary at the same horizontal location   |
| Shift–Down Arrow         | To the line below, to the nearest character<br>boundary at the same horizontal location   |
| Shift–Option–Right Arrow | To the end of the current word, then to the end<br>of the next word                       |
| Shift–Option–Left Arrow  | To the beginning of the current word, then to<br>the beginning of the previous word       |
| Shift–Option–Up Arrow    | To the beginning of the current paragraph, then<br>to the beginning of the next paragraph |  
**Table 8-2** Extending text selection with the Shift and arrow keys (continued)  
| Keys                      | Extends selection                                                                                                                                                  |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Shift–Option–Down Arrow   | To the end of the current paragraph, then to the<br>end of the next paragraph (include the blank<br>line between paragraphs in cut, copy, and paste<br>operations) |
| Shift–Command–Right Arrow | To the next semantic unit, typically the end of<br>the current line                                                                                                |
| Shift–Command–Left Arrow  | To the previous semantic unit, typically the<br>beginning of the current line                                                                                      |
| Shift–Command–Up Arrow    | Upward in the next semantic unit, typically the<br>beginning of the document                                                                                       |
| Shift–Command–Down Arrow  | Downward in the next semantic unit, typically<br>the end of the document                                                                                           |  
<span id="page-134-5"></span><span id="page-134-3"></span>**Note:** For non-Roman script systems, Command–Left Arrow and Command–Right Arrow are reserved for changing the direction of keyboard input.  
#### <span id="page-134-0"></span>Moving the Insertion Point in "Empty" Documents  
When a boundary is reached where there are no more characters in a document, the effect of the arrow keys depends on how the application defines blank space. If it defines it as a page of space characters, then pressing an arrow key moves the insertion point one character in the appropriate direction, until it reaches the beginning or end of the document. In truly empty space, nothing happens when an arrow key is pressed.