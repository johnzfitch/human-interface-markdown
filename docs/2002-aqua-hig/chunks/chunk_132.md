<!-- Chunk 132 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 202 -->
A **combination box** (or combo box) is a text entry field combined with a drop-down scrolling list. Combo boxes are useful for displaying a list of likely choices while still allowing the user to type in an item not in the list.  
<span id="page-127-1"></span>**Figure 7-11** Combo box with scrolling list open  
![](images/_page_127_Picture_7.jpeg)  
The default state of the combo box is closed, with the text field empty or displaying a default selection. The default selection (not necessarily the first item in the list) should provide a meaningful clue to the hidden choices. The combo box should also have a useful label.  
To create a combo box, Carbon developers can use the HIComboBoxCreate function and DrawThemeButton with the appropriate constant. Cocoa developers can use the NSComboBox class.