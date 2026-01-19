<!-- Chunk 108 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 925 -->
Character keys include letters, numbers, punctuation, the Space bar, and nonprinting characters—Enter, Tab, Return, Delete (or Backspace), Clear, Escape (Esc). It is essential that your application use these keys consistently.  
#### <span id="page-127-4"></span><span id="page-127-2"></span>Enter  
Most applications add information to a document as soon as the user enters it. In some cases, however, the application may need to wait until a whole collection of information is available before processing it. The Enter key tells the application that the user is through entering information in a particular area of the document, such as a text field. While the user is entering text into a *text* document, pressing Enter has no effect.  
If a dialog has a default button, pressing Enter (or Return) is the same as clicking it.  
#### <span id="page-128-8"></span><span id="page-128-0"></span>Tab  
In text-oriented applications, the Tab key moves the insertion point to the next tab stop. In other contexts, Tab is a signal to proceed; it means "move to the next item in a sequence." The next item can be a table cell or a dialog text field. Pressing Tab can cause data to be entered before focus moves to the next item.  
#### <span id="page-128-7"></span><span id="page-128-1"></span>Return  
In text, the Return key inserts a carriage return (a line break) and moves the insertion point to the beginning of the next line. In arrays, the Return key signals movement to the leftmost field one step lower (like a carriage return on a typewriter). Like Tab, pressing Return can cause data to be entered before focus moves to the next item.  
If a dialog has a default button, pressing Return (or Enter) is the same as clicking it.  
#### <span id="page-128-4"></span><span id="page-128-2"></span>Delete (or Backspace)  
Generally, if an item is selected, pressing Delete (or Backspace) removes the selection without putting it in the Clipboard. If nothing is selected, pressing Delete removes the character preceding the insertion point, without putting it in the Clipboard. The Delete key has the same effect as the Clear command in the Edit menu.  
<span id="page-128-6"></span>**Note:** The Delete key is different from the Forward Delete key (labeled *Del*), which removes characters following the insertion point. See ["Forward Delete](#page-135-4)  [\(Del\)" \(page 136\)](#page-135-4).  
A recommended shortcut for text applications is Command-Delete to delete the previous word, and Command–Forward Delete, to delete the next word. You can support Option-Delete to delete the part of the word to the left of the insertion point, and Option–Forward Delete to delete the part of the word right of the insertion point.  
#### <span id="page-128-5"></span><span id="page-128-3"></span>Clear  
The Clear key has the same effect as the Clear command in the Edit menu: it removes the selection without putting it in the Clipboard. Not all keyboards have a Clear key, so don't require its use in your application.  
The Keyboard **129**  
#### <span id="page-129-7"></span><span id="page-129-0"></span>Escape  
The Escape (Esc) key basically means "let me out of here." It has specific meanings in certain contexts:  
- The user can press Escape instead of clicking Cancel in a dialog.
- The user can press Escape to stop an operation in progress (such as printing), instead of pressing Command-period.  
<span id="page-129-6"></span>Pressing Escape should never cause the user to back out of an operation that would require extensive time or work to reenter. When the user presses Escape during a lengthy operation, display a confirmation dialog to be sure that the key wasn't pressed accidentally.