<!-- Chunk 27 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 2597 -->
Apple keyboards have four arrow keys: Up Arrow, Down Arrow, Left Arrow, and Right Arrow. They can be used alone or in combination with other keys. Keyboard combinations using the arrow keys should be used only for shortcuts for mouse actions. It is *never* appropriate to implement only a keyboard combination and not provide a mouse-based way to perform the same action.  
#### <span id="page-23-2"></span>**Appropriate Uses for the Arrow Keys**  
You can use arrow keys in these ways:  
- In text, the arrow keys move the insertion point. When used with the Shift key, they extend or shrink the selection. If the user makes a selection and then presses the Right Arrow or Left Arrow key, the selection shrinks to zero length and the insertion point moves to the right or left edge of the selection.
- In lists, the arrow keys change the selection.
- In a graphics application, the arrow keys can be used to move a selected object the smallest possible increment (one pixel or one grid unit).
- In full keyboard access mode, the arrow keys move between values within a control. This behavior is described in *Making Carbon Applications Accessible to Users With Disabilities*.  
Don't use the arrow keys to:  
- <span id="page-23-0"></span>■ Move the mouse pointer onscreen
- <span id="page-23-3"></span>■ Duplicate the function of the scroll bars  
#### **Moving the Insertion Point**  
When the insertion point moves vertically in a text document, its horizontal position is maintained in terms of screen pixels, not characters (in other words, the insertion point could move from the twenty-fifth character in a line down to the fiftieth character, depending on the font and size). As the insertion point moves from line to line, keep it as close as possible to its original horizontal position, moving it slightly left or right to the nearest character boundary.  
The Option and Command keys are used as semantic modifiers with the arrow keys. As a general rule, the Option key increases the size of the semantic unit by 1 compared to the arrow keys alone, and the Command key enlarges the semantic unit again. The application determines what the semantic units are. In a word processor, typically the units are characters, words, lines, paragraphs, and documents. In a spreadsheet, a basic semantic unit could be a cell.  
Table 2-1 describes the appropriate behavior of the arrow keys in text documents and fields. In some cases, the behavior describes what happens when the indicated keys are pressed more than once in succession.  
<span id="page-24-2"></span>**Table 2-1** Moving the insertion point with the arrow keys  
<span id="page-24-11"></span><span id="page-24-10"></span><span id="page-24-9"></span><span id="page-24-8"></span><span id="page-24-7"></span><span id="page-24-0"></span>  
| Key                 | Moves insertion point                                                                                                                         |  |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|--|
| Right Arrow         | One character to the right                                                                                                                    |  |
| Left Arrow          | One character to the left                                                                                                                     |  |
| Up Arrow            | To the line above, to the nearest character boundary<br>at the same horizontal location                                                       |  |
| Down Arrow          | To the line below, to the nearest character boundary<br>at the same horizontal location                                                       |  |
| Option–Right Arrow  | To the end of current word, then to the end of the next<br>word                                                                               |  |
| Option–Left Arrow   | To the beginning of the current word, then to the<br>beginning of the previous word                                                           |  |
| Option–Up Arrow     | To the beginning of the current paragraph, then to the<br>beginning of the previous paragraph                                                 |  |
| Option–Down Arrow   | To the end of the current paragraph, then to the end<br>of the next paragraph (not to the blank line after the<br>paragraph, if there is one) |  |
| Command–Right Arrow | To the next semantic unit, typically the end of the<br>current line, then the end of the next line                                            |  |
| Command–Left Arrow  | To the previous semantic unit, typically the beginning<br>of the current line, then the previous unit                                         |  |
| Command–Up Arrow    | Upward in the next semantic unit, typically the<br>beginning of the document                                                                  |  |
| Command–Down Arrow  | Downward in the next semantic unit, typically the<br>end of the document                                                                      |  |  
<span id="page-24-6"></span><span id="page-24-5"></span><span id="page-24-4"></span><span id="page-24-3"></span><span id="page-24-1"></span>**Note:** For non-Roman script systems, Command–Left Arrow and Command–Right Arrow are reserved for changing the direction of keyboard input.  
#### **Extending Text Selection With the Shift and Arrow Keys**  
Table 2-2 describes how to extend text selection by pressing the Shift key with the arrow keys.  
<span id="page-25-1"></span>**Table 2-2** Extending text selection with the Shift and arrow keys  
<span id="page-25-6"></span><span id="page-25-0"></span>  
| Keys                      | Extends selection                                                                                                                                                  |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Shift–Right Arrow         | One character to the right                                                                                                                                         |
| Shift–Left Arrow          | One character to the left                                                                                                                                          |
| Shift–Up Arrow            | To the line above, to the nearest character<br>boundary at the same horizontal location                                                                            |
| Shift–Down Arrow          | To the line below, to the nearest character<br>boundary at the same horizontal location                                                                            |
| Shift–Option–Right Arrow  | To the end of the current word, then to the end<br>of the next word                                                                                                |
| Shift–Option–Left Arrow   | To the beginning of the current word, then to<br>the beginning of the previous word                                                                                |
| Shift–Option–Up Arrow     | To the beginning of the current paragraph, then<br>to the beginning of the next paragraph                                                                          |
| Shift–Option–Down Arrow   | To the end of the current paragraph, then to the<br>end of the next paragraph (include the blank<br>line between paragraphs in cut, copy, and paste<br>operations) |
| Command–Shift–Right Arrow | To the next semantic unit, typically the end of<br>the current line                                                                                                |
| Command–Shift–Left Arrow  | To the previous semantic unit, typically the<br>beginning of the current line                                                                                      |
| Command–Shift–Up Arrow    | Upward in the next semantic unit, typically the<br>beginning of the document                                                                                       |
| Command–Shift–Down Arrow  | Downward in the next semantic unit, typically<br>the end of the document                                                                                           |  
<span id="page-25-5"></span><span id="page-25-4"></span><span id="page-25-3"></span><span id="page-25-2"></span>If no text is selected, the extension begins at the insertion point. If text is selected by dragging, then the extension begins at the selection boundary. For example, in the phrase *stop time,* if the user places the insertion point between the "s" and "t" and then presses Shift–Option–Right Arrow, *top* is selected. However, if the user double-clicks so the whole word is selected, and then extends the selection left or up, it's as if the insertion point were before the "s." If the user extends the selection right or down, it's as if the insertion point were between the "p" and the space after the word.  
Reversing the direction of the selection deselects the appropriate unit. In the previous example, if the word *stop* is selected and the user presses Shift–Option–Right Arrow, so *stop time* is selected, and then presses Shift–Option–Left Arrow, *time* is deselected and *stop* remains selected.  
#### **Moving the Insertion Point in "Empty" Documents**  
<span id="page-26-5"></span>Various text-editing programs treat empty documents in different ways. Some assume that an empty document contains no characters, in which case clicking at the bottom of a blank window causes the insertion point to appear at the top. In this situation, Down Arrow cannot move the insertion point into the blank space because there are no characters there.  
<span id="page-26-6"></span>Other applications treat an empty document as a page of space characters, in which case clicking at the bottom of a blank window puts the insertion point where the user has clicked and lets the user type characters there, overwriting the spaces. Whichever of these methods you choose for your application, it's essential that you be consistent throughout.