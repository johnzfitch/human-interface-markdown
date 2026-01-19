<!-- Chunk 16 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 5225 -->
<span id="page-20-5"></span>There are four kinds of keys: character keys, modifier keys, arrow keys, and function keys. A **character key** sends a character to the computer. When the user holds down a **modifier key,** it alters the meaning of the character key being pressed or the meaning of a mouse action.  
**Note:** Not all the keys described here exist on all keyboards. Don't depend on a key as the only way for users to accomplish a task. You cannot assume anything about which keyboard (if any) is connected to a computer.  
#### <span id="page-20-4"></span><span id="page-20-2"></span>Character Keys  
<span id="page-20-6"></span>Character keys include letters, numbers, punctuation, the Space bar, and nonprinting characters—Tab, Enter, Return, Delete (or Backspace), Clear, and Esc (Escape). It is essential that your application use these keys consistently.  
#### **Space Bar**  
In text, pressing the Space bar enters a space between characters.  
<span id="page-20-7"></span>When full keyboard access is turned on, pressing the Space bar selects the item that currently has the keyboard navigation focus (the equivalent of clicking the mouse button).  
#### **Tab**  
In text-oriented applications, the Tab key moves the insertion point to the next tab stop. In other contexts, Tab is a signal to proceed; it means "move to the next item in a sequence." The next item can be a table cell or a dialog text field. Shift-Tab navigates in the reverse direction. Pressing Tab can cause data to be entered before focus moves to the next item. For more details about navigating with the Tab key, see ["Keyboard Focus and Navigation"](#page-30-0) (page 31).  
The Keyboard **21**  
#### **Enter**  
<span id="page-21-2"></span>Most applications add information to a document as soon as the user enters it. In some cases, however, the application may need to wait until a whole collection of information is available before processing it. The Enter key tells the application that the user has finished entering information in a particular area of the document, such as a text field. While the user is entering text into a *text* document, pressing Enter has no effect.  
If a dialog has a default button, pressing Enter (or Return) is the same as clicking it.  
#### <span id="page-21-5"></span>**Return**  
In text, the Return key inserts a carriage return (a line break) and moves the insertion point to the beginning of the next line. In arrays, the Return key signals movement to the leftmost field one step lower (like a carriage return on a typewriter). As with Tab, pressing Return can cause data to be entered before focus moves to the next item.  
If a dialog has a default button, pressing Return (or Enter) is the same as clicking it.  
#### <span id="page-21-1"></span>**Delete (or Backspace)**  
<span id="page-21-4"></span>Generally, if an item is selected, pressing Delete (or Backspace) removes the selection without putting it on the Clipboard. If nothing is selected, pressing Delete removes the character preceding the insertion point without putting it on the Clipboard. The Delete key has the same effect as the Delete command in the Edit menu.  
**Note:** The Delete key is different from the Forward Delete (Fwd Del) key (labeled *Del*), which removes characters following the insertion point. See ["Forward Delete \(Fwd Del\)"](#page-26-0) (page 27).  
The Option key can be used to extend a deletion to the next semantic unit (such as a word). The Command key can extend a deletion to the next semantic unit beyond that supported by Option. Recommended key combinations for text applications are Command-Delete to delete the previous word and Command–Fwd Del to delete the next word. Option-Delete could delete either the word containing the insertion point or the part of the word to the left of the insertion point, depending on what makes the most sense in your application; Option–Fwd Del could delete the part of the word to the right of the insertion point.  
#### <span id="page-21-0"></span>**Clear**  
<span id="page-21-3"></span>The Clear key has the same effect as the Delete command in the Edit menu: It removes the selection without putting it on the Clipboard. Not all keyboards have a Clear key, so don't require its use in your application.  
#### **Esc (Escape)**  
The Esc (Escape) key basically means "let me out of here." It has specific meanings in certain contexts. The user can press Esc in the following situations:  
- In a dialog, instead of clicking Cancel
- To stop an operation in progress (such as printing), instead of pressing Command-period
- To cancel renaming a file or an item in a list  
#### ■ To cancel a drag in progress  
<span id="page-22-3"></span>Pressing Esc should never cause the user to back out of an operation that would require extensive time or work to reenter. When the user presses Esc during a lengthy operation, display a confirmation dialog to be sure that the key wasn't pressed accidentally.  
#### <span id="page-22-5"></span><span id="page-22-4"></span>Modifier Keys  
Modifier keys alter the way other keystrokes or mouse clicks are interpreted. You should use these keys—Shift, Caps Lock, Option, Command, and Control—consistently as described here.  
#### <span id="page-22-7"></span>**Shift**  
When pressed at the same time as a character key, the Shift key produces the uppercase alphabetic letter or the upper symbol on the key.  
The Shift key is also used with the mouse for extending a selection or for constraining movements in graphics applications. For example, in some applications pressing Shift while using a rectangle tool draws squares.  
#### <span id="page-22-0"></span>**Caps Lock**  
When activated, the Caps Lock key has the same effect on alphabetic keys as the Shift key, but it has no effect on nonalphabetic keys. When the Caps Lock key is down, the user must press Shift to type the upper character on a nonalphabetic key.  
#### <span id="page-22-6"></span>**Option**  
When used with other keys, the Option key produces special symbols. The Key Caps application shows which keys generate each symbol.  
<span id="page-22-1"></span>The Option key can also be used with the mouse to modify the effect of a click or drag. For example, in some applications pressing Option while dragging an object makes a copy of the object.  
#### **Command**  
<span id="page-22-2"></span>On most keyboards, the Command key is labeled with a cloverleaf symbol ( ) and an Apple logo ( ). Pressing the Command key at the same time as a character key tells the application to interpret the key as a command rather than a character. It can also be used with the mouse to modify the effect of a click or drag. Key combinations that use the Command key are described in ["Keyboard Shortcuts"](#page-27-0) (page 28).  
#### **Control**  
The Control key is used to modify the functions of other keys. Combined with a mouse click, it displays contextual menus (see ["Contextual Menus"](#page-97-0) (page 98)).  
Control-F7 temporarily overrides a user's preference for default navigation or full keyboard navigation in windows and dialogs. For more information, see ["Keyboard Focus and](#page-30-0) [Navigation"](#page-30-0) (page 31).  
**Cocoa:** In Cocoa applications, the Control key has additional defined behaviors, as described in "Text System Defaults and Key Bindings" in *Basic Event Handling* in Cocoa Events & Other Input Documentation.  
#### <span id="page-23-4"></span><span id="page-23-1"></span>Arrow Keys  
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
<span id="page-24-12"></span><span id="page-24-11"></span><span id="page-24-10"></span><span id="page-24-9"></span><span id="page-24-8"></span><span id="page-24-0"></span>  
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
| Command–Down Arrow  | Downward in the next semantic unit, typically the end<br>of the document                                                                      |  |  
<span id="page-24-7"></span><span id="page-24-6"></span><span id="page-24-5"></span><span id="page-24-4"></span><span id="page-24-3"></span><span id="page-24-1"></span>**Note:** For non-Roman script systems, Command–Left Arrow and Command–Right Arrow are reserved for changing the direction of keyboard input.  
#### **Extending Text Selection With the Shift and Arrow Keys**  
Table 2-2 describes how to extend text selection by pressing the Shift key with the arrow keys.  
<span id="page-25-1"></span>**Table 2-2** Extending text selection with the Shift and arrow keys  
<span id="page-25-6"></span><span id="page-25-0"></span>  
| Keys                      | Extends selection                                                                                                                                                  |  |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Shift–Right Arrow         | One character to the right                                                                                                                                         |  |
| Shift–Left Arrow          | One character to the left                                                                                                                                          |  |
| Shift–Up Arrow            | To the line above, to the nearest character<br>boundary at the same horizontal location                                                                            |  |
| Shift–Down Arrow          | To the line below, to the nearest character<br>boundary at the same horizontal location                                                                            |  |
| Shift–Option–Right Arrow  | To the end of the current word, then to the end<br>of the next word                                                                                                |  |
| Shift–Option–Left Arrow   | To the beginning of the current word, then to<br>the beginning of the previous word                                                                                |  |
| Shift–Option–Up Arrow     | To the beginning of the current paragraph, then<br>to the beginning of the next paragraph                                                                          |  |
| Shift–Option–Down Arrow   | To the end of the current paragraph, then to the<br>end of the next paragraph (include the blank line<br>between paragraphs in cut, copy, and paste<br>operations) |  |
| Command–Shift–Right Arrow | To the next semantic unit, typically the end of<br>the current line                                                                                                |  |
| Command–Shift–Left Arrow  | To the previous semantic unit, typically the<br>beginning of the current line                                                                                      |  |
| Command–Shift–Up Arrow    | Upward in the next semantic unit, typically the<br>beginning of the document                                                                                       |  |
| Command–Shift–Down Arrow  | Downward in the next semantic unit, typically<br>the end of the document                                                                                           |  |  
<span id="page-25-5"></span><span id="page-25-4"></span><span id="page-25-3"></span><span id="page-25-2"></span>If no text is selected, the extension begins at the insertion point. If text is selected by dragging, then the extension begins at the selection boundary. For example, in the phrase *stop time,* if the user places the insertion point between the "s" and "t" and then presses Shift–Option–Right Arrow, *top* is selected. However, if the user double-clicks so the whole word is selected, and then extends the selection left or up, it's as if the insertion point were before the "s." If the user extends the selection right or down, it's as if the insertion point were between the "p" and the space after the word.  
Reversing the direction of the selection deselects the appropriate unit. In the previous example, if the word *stop* is selected and the user presses Shift–Option–Right Arrow, so *stop time* is selected, and then presses Shift–Option–Left Arrow, *time* is deselected and *stop* remains selected.  
#### **Moving the Insertion Point in "Empty" Documents**  
<span id="page-26-5"></span>Various text-editing programs treat empty documents in different ways. Some assume that an empty document contains no characters, in which case clicking at the bottom of a blank window causes the insertion point to appear at the top. In this situation, Down Arrow cannot move the insertion point into the blank space because there are no characters there.  
<span id="page-26-6"></span>Other applications treat an empty document as a page of space characters, in which case clicking at the bottom of a blank window puts the insertion point where the user has clicked and lets the user type characters there, overwriting the spaces. Whichever of these methods you choose for your application, it's essential that you be consistent throughout.  
#### <span id="page-26-7"></span><span id="page-26-3"></span>Function Keys  
There are 15 nondedicated function keys on desktop Macintosh keyboards (F1 through F15). Default function key combinations are listed in *Making Carbon Applications Accessible to Users With Disabilities*. Desktop Macintosh keyboards provide the following six dedicated function keys with standard behaviors. Because not all Macintosh computers have all function keys, don't rely on these keys for critical keyboard shortcuts. For example, portable computers usually have 12 function keys (F1 through F12), not 15.  
#### <span id="page-26-4"></span>**Help**  
<span id="page-26-2"></span><span id="page-26-0"></span>Pressing the Help key (or Command-? or Command-/) invokes the application's help in Help Viewer.  
#### **Forward Delete (Fwd Del)**  
Pressing the Forward Delete (labeled Del) key deletes the character *after* the insertion point, shifting everything following the removed character one position back. The effect is that the insertion point remains stationary while it "vacuums" the character or selection ahead of it.  
If something is selected when Fwd Del is pressed, it has the same effect as pressing Delete (Backspace) or choosing Delete from the Edit menu.  
<span id="page-26-1"></span>You can support Option–Fwd Del to delete the next larger semantic unit, as described in ["Moving](#page-23-0) [the Insertion Point"](#page-23-0) (page 24), but deleting more than one word at a time is inadvisable. Users prefer to select large amounts of text with the mouse so they have more control over what they're deleting.  
#### **Home, End**  
Pressing the Home key is equivalent to moving the scrollers all the way to the top and to the left. In a text document, for example, pressing Home scrolls to the beginning of the document; in a spreadsheet, it may scroll to the beginning of the spreadsheet or to the beginning of a row. These keys should also work in scrolling lists to display the top or bottom of the list.  
End is the opposite of Home: It scrolls to the end of a document.  
If the beginning or end of the document is already reached, pressing Home or End produces a system alert sound. Pressing the Home or End key has no effect on the location of the insertion point or selected data.  
#### <span id="page-27-5"></span>**Page Up, Page Down**  
Pressing Page Up or Page Down scrolls the document up or down one page. If an entire page can't be displayed in the window, these keys first scroll incrementally up or down, until the top or bottom of the page is visible, before scrolling to the next page. These keys should also work in scrolling lists.  
<span id="page-27-4"></span>If the beginning or end of the document is reached, pressing Page Up or Page Down produces a system alert sound. Pressing the Page Up or Page Down key has no effect on the location of the insertion point or selected data.