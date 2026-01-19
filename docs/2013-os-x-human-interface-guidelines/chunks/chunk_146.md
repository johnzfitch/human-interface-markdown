<!-- Chunk 146 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 2801 -->
Text controls either display text or accept text as input. The combination box, which combines a text input field with a menu, is not covered in this section; instead, see ["Combination](#page-264-0) Box" (page 265).  
<span id="page-280-1"></span>**Important:** The controls described in thissection are suitable for use in the window body only; they should not be used in the window-frame areas. The single exception is the search field, which can also be used in a toolbar. To learn about the controls that are specifically designed for use in a toolbar (or bottom bar), see ["Window-Frame](#page-237-0) Controls" (page 238).  
#### Static Text Field  
A **static text field** displays text that can't be modified by the user.  
Static text fields are available in Interface Builder (where they're called labels). To create a static text field using AppKit programming interfaces, use the NSTextField class.  
Static text fields have two states: active and dimmed.  
**Make static text selectable when it provides an obvious user benefit.** For example, a user should be able to copy an error message, a serial number, or an IP address to paste elsewhere.  
#### <span id="page-281-0"></span>Text Input Field  
A **text input field** accepts user-entered text.  
![](images/_page_281_Picture_5.jpeg)  
Text input fields are available in Interface Builder. To create one using AppKit programming interfaces, use the NSTextField class.  
#### Appearance and Behavior  
A text input field (also called an editable text field) is a rectangular area in which the user enterstext or modifies existing text. A text input field displays user-supplied text in a system font that is appropriate for the size of the control. In addition, a text input field can contain a token field control, which displays the user input in the form of a draggable token (for more information on tokens, see ["Token](#page-282-0) Field" (page 283)).  
By default, a text input field supports keyboard focus and password entry.  
Text input fields are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light [Content](#page-240-0) [Controls"](#page-240-0) (page 241).  
#### Guidelines  
Use a text input field to get information from the user.  
**Be sure to perform appropriate edit checks when you receive user input.** For example, if the only legitimate value for a field is a string of digits, an app should issue an alert if the user types characters other than digits. In most cases, the appropriate time to check the data in the field is when the user clicks outside the field or presses the Return, Enter, or Tab key.  
**Be sure to use a combo box if you want to combine a menu or list of choices with a text input field.** Don't try to create one by putting a text input field and a menu together. For more information about combo boxes, see ["Combination](#page-264-0) Box" (page 265).  
**In general, display an introductory label with a text input field.** A label helps users understand what type of information they should enter. Generally, these labels should have title-style capitalization (for more information on this style, see ["Capitalizing](#page-303-0) Labels and Text" (page 304)).  
**In general, ensure that the length of a text input field comfortably accommodates the length of the expected input.** The length of a text input field helps users gauge whether they're inputting the appropriate information.  
**Space multiple text input fields evenly.** If you want to use more than one text input field in a window, you need to leave enough space between them so users can easily see which input field belongs with each introductory label. If you need to position more than one text input field at the same height (that is, in a horizontal line), be sure to leave plenty of space between the end of one text field and the introductory label of the next. Typically, however, multiple text input fields are stacked vertically, as in a form users fill out. In addition, if you display multiple text input fields in a window, be sure they all have the same length.  
#### <span id="page-282-0"></span>Token Field  
A **token field** creates a movable token out of text.  
Token field controls are available in Interface Builder. To create one using AppKit programming interfaces, use the NSTokenField class.  
#### Guidelines  
**In general, use a token field control in a text input field.** As the user types in the text input field, the token field control invokes text completion after a delay that you specify. When the user types the comma character or presses Return, the preceding text input is transformed into a token. (For more information about text input fields, see "Text Input [Field"](#page-281-0) (page 282)).  
**If appropriate, add a contextual menu to a token.**(Note that you have to add code to support the addition of a contextual menu.) In a token field's menu, you might offer more information about the token and ways to manipulate it. In Mail, for example, the token menu displays information about the token (the email address associated with the name) and items that allow the user to edit the token or add its associated information to Contacts.  
![](images/_page_283_Picture_2.jpeg)  
#### <span id="page-283-0"></span>Search Field  
A **search field** accepts text from users, which can be used as input for a search (shown here in a toolbar).  
![](images/_page_283_Picture_5.jpeg)  
**Important:** A search field can be used in the window-frame area or in the window body. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-237-0) [Controls"](#page-237-0) (page 238).  
Search field controls are available in Interface Builder. To create one using AppKit programming interfaces, use the NSSearchField class.  
#### Appearance and Behavior  
A search field looks like a text field with rounded ends. Users enter text (or modify existing text) that specifies itemsthey want to search for. A search field can be configured to begin searching while the user isstill entering text, or to wait until the user is finished.  
By default, a search field displays the magnifying icon in its left end. A search field can also contain an icon the user clicks to cancel the search or clear the field.  
Search fields are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light [Content](#page-240-0) [Controls"](#page-240-0) (page 241).  
#### Guidelines  
Use a search field to enable search functionality within your app.  
**Decide when to start the search.** You can begin searching as soon as the user starts typing, or wait until the user presses Return or Enter. If searching occurs while the user is still typing, the behavior is more like a find in which results are filtered as the entered text becomes more specific. This behavior is especially useful when the search field is in a scope bar that focuses on a window's contents. If search should occur after the user finishes typing, you might want to enable a search term completion menu so that users can choose from commonly searched terms.  
**In general, avoid using a menu to display search history.** For privacy reasons, users might not appreciate having their search history displayed. You might instead use the menu to allow users to choose different types of searches or define the context or scope of a search. Note that a scope bar is well-suited to enabling this type of searching (for more information, see "Using a Scope Bar to Enable [Searching](#page-184-0) and Filtering" (page 185)).  
**Avoid supplying an introductory label.** Users are familiar with the distinctive appearance of a search field, so there is no need to label it. The exception to this is when you place a search field in a toolbar; in this case, you need to supply the label "Search" to be displayed when users customize the toolbar to show icons and text or text only.  
**Display placeholder text, if it helps users understand how search works in your app.** A search field can display light gray placeholder text in its left end. For example, the search field in the Safari toolbar can display one of three common search engines (users can choose the search engine they want to use in the search field menu).  
#### <span id="page-285-0"></span>Scrolling List  
A **scrolling list** is a list that uses scroll bars to reveal its contents.  
![](images/_page_285_Figure_3.jpeg)  
Scrolling lists are available in Interface Builder. Start with a table view object and ensure that it is sized so that only the verticalscroller can be visible. Then, in the Attributes pane of the inspector,set the number of columns to 1 and deselect the Headers checkbox. To create a scrolling list using AppKit programming interfaces, use the NSTableView class.  
#### Appearance and Behavior  
A scrolling list is a single-column rectangular view of any height. The background of a scrolling list can be white or white striped with light blue.  
**Note:** Scrolling lists, like other scrolling areas, are governed by the user's scroll direction setting in System Preferences.  
Users can scroll through a scrolling list without selecting anything, or they can click an item to select it, use Shift-click to select more than one contiguous item, or use Command-click for a discontinuous selection. Users can press the arrow keys to navigate through the list and can quickly select an item by typing the first few characters.  
#### Guidelines  
Use a scrolling list to display an arbitrarily large number of items from which users can choose. Although scrolling lists aren't directly editable, you can provide editing functionality that allows usersto provide additional list items.  
**In general, don't use a scrolling list to provide choices in a limited range.** A scrolling list might not display all items at once, which can make it difficult for users to grasp the scope of their choices. If you need to display a limited range of choices, a pop-up menu (described in ["Pop-Up](#page-258-0) Menu" (page 259)) might be a better choice.  
**Insert an ellipsis in the middle of an item that is too long to fit in the list.** Inserting the ellipsis in the middle allows you to preserve the beginning and end of the item name, so that users can more easily recognize it. For example, users sometimes add the most specific information (such as a date) to the end of a document name, so it's helpful when both the beginning and the end of the name are visible.  
**Use a striped background when it helps users distinguish list items.** For example, users can lose their place in a very long list in which most of the items look similar. In this case, it can be easier for users to scan the list and find specific items when the background is striped.  
<span id="page-286-0"></span>**In general, provide an introductory label for a scrolling list.** A label helps users understand the types of items that are available to them.