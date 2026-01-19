<!-- Chunk 121 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 488 -->
A **combination box** (or combo box) provides a list of choices and allows users to specify custom choices.  
![](images/_page_196_Figure_6.jpeg)  
**API Note:** To define a combo box in your code, use the NSComboBox class.  
A combo box is a text entry field combined with a drop-down list. The default state of the combo box is closed, with the text field empty or displaying a default selection.  
Users can type any appropriate characters into the text field. If a user types in an item already in the list, or types in a few characters that match the first characters of an item in the list, that item is highlighted when the user opens the list. A user-typed item is *not* added to the permanent list.  
Use a combo box to give users the convenience of selecting an item from a list combined with the freedom of specifying their own custom item.  
**List only items that users can choose singly.** A combo box does not allow multiple selections, so be sure to offer users a list of items from which they can choose only one at a time.  
**Display a meaningful default selection.** It's best when the default selection (which may not be the first item in the list) provides a clue to the hidden choices. It's also a good idea to introduce a combo box with a label that helps users know what types of items to expect.  
**Don't extend the right edge of the list beyond the right edge of the arrow box.** If an item is too long, it's truncated.  
**Display the most likely choices, even though users can enter their own.** Users appreciate being able to specify custom choices, but they also appreciate the convenience of choosing from a list. For example, Safari allows users to set a preference for the minimum font size to display. In its Advanced preferences pane (shown here), Safari lists several font sizes in a combo box, and users can supply a custom font size if none of the listed choices is suitable.  
![](images/_page_197_Picture_2.jpeg)