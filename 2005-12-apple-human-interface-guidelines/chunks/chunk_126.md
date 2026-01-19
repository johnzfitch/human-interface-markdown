<!-- Chunk 126 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 1339 -->
Apple keyboards have four arrow keys: Up Arrow, Down Arrow, Left Arrow, and Right Arrow. They can be used alone or in combination with other keys. Keyboard combinations using the arrow keys should be used only for shortcuts for mouse actions. It is *never* appropriate to implement only a keyboard combination and not provide a mouse-based way to perform the same action.  
#### <span id="page-91-2"></span>**Appropriate Uses for the Arrow Keys**  
You can use arrow keys in these ways:  
- In text, the arrow keys move the insertion point. When used with the Shift key, they extend or shrink the selection. If the user makes a selection and then presses the Right Arrow or Left Arrow key, the selection shrinks to zero length and the insertion point moves to the right or left edge of the selection.
- In lists, the arrow keys change the selection.
- In a graphics application, the arrow keys can be used to move a selected object the smallest possible increment (one pixel or one grid unit).
- In full keyboard access mode, the arrow keys move between values within a control.  
Don't use the arrow keys to:  
- <span id="page-91-0"></span>■ Move the mouse pointer onscreen
- <span id="page-91-4"></span>■ Duplicate the function of the scroll bars  
#### **Moving the Insertion Point**  
When the insertion point moves vertically in a text document, its horizontal position is maintained in terms of screen pixels, not characters (in other words, the insertion point could move from the twenty-fifth character in a line down to the fiftieth character, depending on the font and size). As the insertion point moves from line to line, keep it as close as possible to its original horizontal position, moving it slightly left or right to the nearest character boundary.  
The Option and Command keys are used as semantic modifiers with the arrow keys. As a general rule, the Option key increases the size of the semantic unit by 1 compared to the arrow keys alone, and the Command key enlarges the semantic unit again. The application determines what the semantic units are. In a word processor, typically the units are characters, words, lines, paragraphs, and documents. In a spreadsheet, a basic semantic unit could be a cell.  
<span id="page-91-3"></span>Table 7-1 describes the appropriate behavior of the arrow keys in text documents and fields. In some cases, the behavior describes what happens when the indicated keys are pressed more than once in succession.  
<span id="page-92-0"></span>**Table 7-1** Moving the insertion point with the arrow keys  
<span id="page-92-13"></span><span id="page-92-12"></span><span id="page-92-11"></span><span id="page-92-10"></span><span id="page-92-9"></span>  
| Key                 | Moves insertion point                                                                                                                      |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Right Arrow         | One character to the right                                                                                                                 |
| Left Arrow          | One character to the left                                                                                                                  |
| Up Arrow            | To the line above, to the nearest character boundary at the same<br>horizontal location                                                    |
| Down Arrow          | To the line below, to the nearest character boundary at the same<br>horizontal location                                                    |
| Option–Right Arrow  | To the end of current word, then to the end of the next word                                                                               |
| Option–Left Arrow   | To the beginning of the current word, then to the beginning of the<br>previous word                                                        |
| Option–Up Arrow     | To the beginning of the current paragraph, then to the beginning of the<br>previous paragraph                                              |
| Option–Down Arrow   | To the end of the current paragraph, then to the end of the next<br>paragraph (not to the blank line after the paragraph, if there is one) |
| Command–Right Arrow | To the next semantic unit, typically the end of the current line, then the<br>end of the next line                                         |
| Command–Left Arrow  | To the previous semantic unit, typically the beginning of the current<br>line, then the previous unit                                      |
| Command–Up Arrow    | Upward in the next semantic unit, typically the beginning of the<br>document                                                               |
| Command–Down Arrow  | Downward in the next semantic unit, typically the end of the document                                                                      |  
<span id="page-92-14"></span><span id="page-92-8"></span><span id="page-92-7"></span><span id="page-92-6"></span><span id="page-92-5"></span><span id="page-92-3"></span><span id="page-92-2"></span>**Note:** For non-Roman script systems, Command–Left Arrow and Command–Right Arrow are reserved for changing the direction of keyboard input.