<!-- Chunk 123 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 2566 -->
<span id="page-98-1"></span>Apple keyboards have four arrow keys: Up Arrow, Down Arrow, Left Arrow, and Right Arrow. They can be used alone or in combination with other keys. Keyboard combinations using the arrow keys should be used only for shortcuts for mouse actions. It is *never* appropriate to implement only a keyboard combination and not provide a mouse-based way to perform the same action.  
#### **Appropriate Uses for the Arrow Keys**  
You can use arrow keys in these ways:  
- In text, the arrow keys move the insertion point. When used with the Shift key, they extend or shrink the selection. If the user makes a selection and then presses the Right Arrow or Left Arrow key, the selection shrinks to zero length and the insertion point moves to the right or left edge of the selection.
- In lists, the arrow keys change the selection.
- In a graphics application, the arrow keys can be used to move a selected object the smallest possible increment (one pixel or one grid unit).
- In full keyboard access mode, the arrow keys move between values within a control.  
Don't use the arrow keys to:  
- Move the mouse pointer onscreen
- <span id="page-99-1"></span>■ Duplicate the function of the scroll bars  
#### <span id="page-99-3"></span>**Moving the Insertion Point**  
When the insertion point moves vertically in a text document, its horizontal position is maintained in terms ofscreen pixels, not characters(in other words, the insertion point could move from the twenty-fifth character in a line down to the fiftieth character, depending on the font and size). As the insertion point moves from line to line, keep it as close as possible to its original horizontal position, moving it slightly left or right to the nearest character boundary.  
The Option and Command keys are used as semantic modifiers with the arrow keys. As a general rule, the Option key increases the size of the semantic unit by 1 compared to the arrow keys alone, and the Command key enlarges the semantic unit again. The application determines what the semantic units are. In a word processor, typically the units are characters, words, lines, paragraphs, and documents. In a spreadsheet, a basic semantic unit could be a cell.  
<span id="page-99-2"></span><span id="page-99-0"></span>Table 8-1 describes the appropriate behavior of the arrow keys in text documents and fields. In some cases, the behavior describes what happens when the indicated keys are pressed more than once in succession.  
<span id="page-99-7"></span>**Table 8-1** Moving the insertion point with the arrow keys  
<span id="page-99-8"></span><span id="page-99-6"></span><span id="page-99-5"></span><span id="page-99-4"></span>  
| Key                | Moves insertion point                                                                         |
|--------------------|-----------------------------------------------------------------------------------------------|
| Right Arrow        | One character to the right                                                                    |
| Left Arrow         | One character to the left                                                                     |
| Up Arrow           | To the line above, to the nearest character boundary at the same horizontal<br>location       |
| Down Arrow         | To the line below, to the nearest character boundary at the same horizontal<br>location       |
| Option–Right Arrow | To the end of current word, then to the end of the next word                                  |
| Option–Left Arrow  | To the beginning of the current word, then to the beginning of the previous<br>word           |
| Option–Up Arrow    | To the beginning of the current paragraph, then to the beginning of the previous<br>paragraph |  
<span id="page-100-6"></span><span id="page-100-5"></span>  
| Key                 | Moves insertion point                                                                                                                      |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Option–Down Arrow   | To the end of the current paragraph, then to the end of the next paragraph (not<br>to the blank line after the paragraph, if there is one) |
| Command–Right Arrow | To the next semantic unit, typically the end of the current line, then the end of<br>the next line                                         |
| Command–Left Arrow  | To the previous semantic unit, typically the beginning of the current line, then<br>the previous unit                                      |
| Command–Up Arrow    | Upward in the next semantic unit, typically the beginning of the document                                                                  |
| Command–Down Arrow  | Downward in the next semantic unit, typically the end of the document                                                                      |  
<span id="page-100-12"></span><span id="page-100-10"></span><span id="page-100-4"></span><span id="page-100-1"></span>**Note:** For non-Roman script systems, Command–Left Arrow and Command–Right Arrow are reserved for changing the direction of keyboard input.  
#### <span id="page-100-3"></span><span id="page-100-2"></span><span id="page-100-0"></span>**Extending Text Selection With the Shift and Arrow Keys**  
Table 8-2 describes how to extend text selection by pressing the Shift key with the arrow keys.  
**Table 8-2** Extending text selection with the Shift and arrow keys  
<span id="page-100-11"></span><span id="page-100-9"></span><span id="page-100-8"></span><span id="page-100-7"></span>  
| Keys                      | Extends selection                                                                                                                                               |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Shift–Right Arrow         | One character to the right                                                                                                                                      |
| Shift–Left Arrow          | One character to the left                                                                                                                                       |
| Shift–Up Arrow            | To the line above, to the nearest character boundary at the same horizontal<br>location                                                                         |
| Shift–Down Arrow          | To the line below, to the nearest character boundary at the same horizontal<br>location                                                                         |
| Shift–Option–Right Arrow  | To the end of the current word, then to the end of the next word                                                                                                |
| Shift–Option–Left Arrow   | To the beginning of the current word, then to the beginning of the previous<br>word                                                                             |
| Shift–Option–Up Arrow     | To the beginning of the current paragraph, then to the beginning of the<br>next paragraph                                                                       |
| Shift–Option–Down Arrow   | To the end of the current paragraph, then to the end of the next paragraph<br>(include the blank line between paragraphs in cut, copy, and paste<br>operations) |
| Command–Shift–Right Arrow | To the next semantic unit, typically the end of the current line                                                                                                |
| Command–Shift–Left Arrow  | To the previous semantic unit, typically the beginning of the current line                                                                                      |
| Command–Shift–Up Arrow    | Upward in the nextsemantic unit, typically the beginning of the document                                                                                        |  
<span id="page-101-1"></span>  
| Keys                     | Extends selection                                                     |
|--------------------------|-----------------------------------------------------------------------|
| Command–Shift–Down Arrow | Downward in the next semantic unit, typically the end of the document |  
If no text is selected, the extension begins at the insertion point. If text is selected by dragging, then the extension begins at the selection boundary. For example, in the phrase *stop time,* if the user places the insertion point between the "s" and "t" and then presses Shift–Option–Right Arrow, *top* is selected. However, if the user double-clicks so the whole word is selected, and then extends the selection left or up, it's as if the insertion point were before the "s." If the user extendsthe selection right or down, it's asif the insertion point were between the "p" and the space after the word.  
Reversing the direction of the selection deselects the appropriate unit. In the previous example, if the word *stop* is selected and the user presses Shift–Option–Right Arrow, so *stop time* is selected, and then presses Shift–Option–Left Arrow, *time* is deselected and *stop* remains selected.  
#### <span id="page-101-5"></span>**Moving the Insertion Point in "Empty" Documents**  
Varioustext-editing programstreat empty documentsin different ways. Some assume that an empty document contains no characters, in which case clicking at the bottom of a blank window causes the insertion point to appear at the top. In thissituation, Down Arrow cannot move the insertion point into the blank space because there are no characters there.  
<span id="page-101-6"></span>Other applications treat an empty document as a page of space characters, in which case clicking at the bottom of a blank window putsthe insertion point where the user has clicked and letsthe user type characters there, overwriting the spaces. Whichever of these methods you choose for your application, it's essential that you be consistent throughout.