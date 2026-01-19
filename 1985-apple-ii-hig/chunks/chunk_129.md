<!-- Chunk 129 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 372 -->
Commands in menus normally act on only one object. If a command needs more information before it can be performed, it presents a dialog box to gather the additional information from the user. The user can tell which commands bring up dialog boxes because they're followed by an ellipsis (...) in the menu.  
A dialog box is a rectangle that may contain text, controls, and icons. There should be some text in the box that indicates which command brought up the dialog box.  
Other than explanatory text, the contents of a dialog box are all objects that the user sets to provide the needed information. These objects include controls and text fields. When the application puts up the dialog box, it should set the controls to some default setting and fill in the text fields with default values, if possible. One of the text fields (the "first" field) should be highlighted, so that the user can change its value just by typing in the new value. If all the text fields are blank, there should be an insertion point in the first field.  
Editing text fields in a dialog box should conform to the guidelines detailed above, under "Text Editing".  
When the user is through editing an item:  
- Pressing Tab accepts the changes made to the item, and selects the next item in sequence.  
1/15/85 Tognazzini  
DIALOGS 109  
Clicking in another item accepts the changes made to the previous item and selects the newly clicked item.  
Dialog boxes are either modal or modeless, as described below.