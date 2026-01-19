<!-- Chunk 267 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 1151 -->
<span id="page-297-1"></span>A **combination box** (or combo box) is a text entryfield combinedwith a drop-down list. Combo boxes can display a list of likely choices while still allowing the user to type in an item not in the list. For example, Safari allows users to set a preference for the minimum font size to display. In its Advanced preferences pane (shown in Figure 15-35), Safari lists several font sizes in a combo box, and users can supply a custom font size if none of the listed choices is suitable.  
**Figure 15-35** A combo box allows users to select from a list or supply their own item  
![](images/_page_297_Picture_12.jpeg)  
Users can type any appropriate characters into the text field. If a user types in an item already in the list, or types in a few characters that match the first characters of an item in the list, the item is highlighted when the user opens the list. A user-typed item is *not* added to the permanent list.  
Users open the list by pressing or clicking the arrow to the right of the text field. The list descends from the text field; it is the same width as the text field plus the arrow box, and it has a drop shadow.  
When the user selects an item in the list, the item replaces whatever is in the text entry field and the list closes. If the list was opened by pressing the arrow, the user selects an item in the list by dragging to it. If the list was opened by clicking the arrow, the user selects an item by clicking it or by pressing the Up Arrow or Down Arrow key. The user can accept an item by pressing the Space bar, Enter, or Return.  
<span id="page-298-0"></span>If the list is open and the user clicks outside it, including within the text entry field, the list closes.  
**Figure 15-36** A combo box with the list open  
![](images/_page_298_Picture_7.jpeg)  
#### Combo Box Usage  
Use a combo boxwhen youwant togive users the convenience of selectingan item from a list combined with the freedom of specifyingtheir own custom item. A combo box does not allow multiple selections, so be sure to offer users a list of items from which they can choose only one at a time.  
#### Combo Box Contents and Labeling  
The default state of the combo box is closed,with the text field emptyor displayinga default selection. Recall that user-supplied items are not added to the control's permanent list.  
The default selection (which may not be the first item in the list) should provide a meaningful clue to the hidden choices, but it's agood idea to introduce a combo boxwith a label that helps usersknow what types of items to expect.  
Don't extend the right edge of the list beyond the right edge of the arrow box; if an item is too long, it is truncated.  
#### Combo Box Specifications  
**Control sizes**: The height of a combo box is fixed for each size, but its width should be wide enough to accommodate the longest list item.  
**Label spacing and fonts**: The text of the list items in a combo box should be in a font that is proportional to the size of the control. The text of the introductory label should be an emphasized version of the same font. Use the following metrics and specifications for a combo box:  
#### ■ Regular size:  
- ❏ List-item text: System font. This font is automatically supplied by Interface Builder.
- ❏ Introductorylabel: Emphasized system font. Leave 8 pixels between the end of the text (colon) and the left edge of the control.  
#### ■ Small:  
- ❏ List-item text: Small system font. This font is automatically supplied by Interface Builder.
- ❏ Introductory label: Emphasized small system font. Leave 6 pixels between the end of the text (colon) and the left edge of the control.  
#### ■ Mini:  
- ❏ List-item text: Mini system font. This font is automatically supplied by Interface Builder.
- <span id="page-299-2"></span>❏ Introductory label: Emphasized mini system font. Leave 5 pixels between the end of the text (colon) and the left edge of menu.  
<span id="page-299-1"></span>Figure 15-37 shows how the combo box introductory label and list-item text are positioned.  
**Figure 15-37** A combo box with an introductory label and list-item text  
![](images/_page_299_Picture_14.jpeg)  
**Control spacing**: When combo boxes are stacked vertically, leave the following amounts of space between them:  
- Regular size: At least 12 pixels.
- Small: At least 10 pixels.
- Mini: At least 8 pixels.  
#### <span id="page-299-0"></span>Combo Box Implementation  
Combo boxes are available in Interface Builder. To create one using the Application Kit programming interfaces, use the NSComboBox class.