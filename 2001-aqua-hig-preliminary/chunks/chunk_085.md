<!-- Chunk 85 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 605 -->
A combination (or "combo") box is a text entry field combined with a pop-up menu or a drop-down scrolling list. Combo boxes are useful for displaying a list of likely choices while still allowing the user to type in an item not in the list.  
<span id="page-95-1"></span>**Figure 7-9** Combo box with pop-up menu and scrolling list  
![](images/_page_95_Picture_5.jpeg)  
The default state of the combo box is closed, with the text field empty or displaying a default selection. The default selection (not necessarily the first item in the list) should provide a meaningful clue to the hidden choices. The combo box should also have a useful label.  
Combo boxes are available for Cocoa applications. Carbon developers should use the Appearance Manager to simulate these controls.  
<span id="page-95-2"></span>**Figure 7-10** Combo box specifications  
![](images/_page_95_Picture_9.jpeg)  
#### <span id="page-96-0"></span>The Text Entry Field  
The user can type any appropriate characters into the text field. If the user types in an item already in the menu or list, or types in a few characters that match the first characters of an item in the menu or list, the item is highlighted when the user displays the menu or list. A user-typed item does *not* get added to the permanent menu or list.  
If the user presses Tab to select the field, the keyboard focus ring is inside the text entry field.  
#### <span id="page-96-1"></span>The Pop-Up Menu or Scrolling List  
Use a pop-up menu to display up to 12 choices. If you want to offer more than 12 items, use a scrolling list.  
The user displays the menu or list by pressing the arrows to the right of the text field. The menu or list is a window that descends from the text field; the window is the same width as the text field and has a drop shadow. Don't extend the right edge of the menu or list beyond the right edge of the arrow box; if an item is too long, it gets truncated.  
When the user selects an item in the menu or list, the item replaces whatever is in the text entry field and the menu or list closes. If the user presses the Up Arrow or Down Arrow key to move through the items, the selected item is highlighted and appears in the text entry field. The user can accept an item by pressing the Space bar, Enter, or Return.  
If the menu or list is open and the user clicks outside it, including within the text entry field, the menu or list closes.