<!-- Chunk 121 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 1095 -->
Character keys include letters, numbers, punctuation, the Space bar, and nonprinting characters—Tab, Enter, Return, Delete (or Backspace), Clear, and Esc (Escape). It is essential that your application use these keys consistently.  
#### <span id="page-96-5"></span>**Space Bar**  
In text, pressing the Space bar enters a space between characters.  
<span id="page-96-6"></span>When full keyboard accessisturned on, pressing the Space barselectsthe item that currently hasthe keyboard navigation focus (the equivalent of clicking the mouse button).  
#### **Tab**  
In text-oriented applications, the Tab key moves the insertion point to the next tab stop. In other contexts, Tab is a signal to proceed; it means "move to the next item in a sequence." The next item can be a table cell or a dialog text field. Shift-Tab navigates in the reverse direction. Pressing Tab can cause data to be entered before focus moves to the next item. For more details about navigating with the Tab key, see ["Keyboard](#page-106-0) Focus and [Navigation"](#page-106-0) (page 107)  
#### <span id="page-96-2"></span>**Enter**  
Most applications add information to a document as soon as the user enters it. In some cases, however, the application may need to wait until a whole collection of information is available before processing it. The Enter key tells the application that the user has finished entering information in a particular area of the document, such as a text field. While the user is entering text into a *text* document, pressing Enter has no effect.  
If a dialog has a default button, pressing Enter (or Return) is the same as clicking it.  
#### **Return**  
<span id="page-97-6"></span>In text, the Return key inserts a carriage return (a line break) and moves the insertion point to the beginning of the next line. In arrays, the Return key signals movement to the leftmost field one step lower (like a carriage return on a typewriter). As with Tab, pressing Return can cause data to be entered before focus moves to the next item.  
If a dialog has a default button, pressing Return (or Enter) is the same as clicking it.  
#### **Delete (or Backspace)**  
<span id="page-97-1"></span>Generally, if an item is selected, pressing Delete (or Backspace) removes the selection without putting it on the Clipboard. If nothing is selected, pressing Delete removes the character preceding the insertion point without putting it on the Clipboard. The Delete key has the same effect as the Delete command in the Edit menu.  
**Note:** The Delete key is different from the Forward Delete (Fwd Del) key (labeled *Del*), which removes characters following the insertion point. See ["Forward](#page-101-0) Delete (Fwd Del)" (page 102)  
The Option key can be used to extend a deletion to the next semantic unit (such as a word). The Command key can extend a deletion to the next semantic unit beyond that supported by Option. Recommended key combinations for text applications are Command-Delete to delete the previous word and Command–Fwd Del to delete the next word. Option-Delete could delete either the word containing the insertion point or the part of the word to the left of the insertion point, depending on what makes the most sense in your application; Option–Fwd Del could delete the part of the word to the right of the insertion point.  
#### <span id="page-97-0"></span>**Clear**  
<span id="page-97-2"></span>The Clear key has the same effect as the Delete command in the Edit menu: It removes the selection without putting it on the Clipboard. Not all keyboards have a Clear key, so don't require its use in your application.  
#### **Esc (Escape)**  
The Esc (Escape) key basically means "let me out of here." It has specific meanings in certain contexts. The user can press Esc in the following situations:  
- In a dialog, instead of clicking Cancel
- To stop an operation in progress (such as printing), instead of pressing Command-period
- <span id="page-97-3"></span>■ To cancel renaming a file or an item in a list
- To cancel a drag in progress  
<span id="page-97-5"></span><span id="page-97-4"></span>Pressing Esc should never cause the user to back out of an operation that would require extensive time or work to reenter. When the user presses Esc during a lengthy operation, display a confirmation dialog to be sure that the key wasn't pressed accidentally.