<!-- Chunk 105 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 1071 -->
A user makes an overview picker appear by tapping the appropriate label. The picker stays open until the user taps its Close box. The user does not have to press and hold the pen on the button or label to keep the picker open. An overview picker stays open even if a user taps, writes, or draws outside the picker.  
#### Picking Items 4  
A user selects items listed in an overview picker by tapping them. A selected item has a check mark in its checkbox. Tapping a selected item deselects it. For selecting or deselecting, tapping an item's name has the same effect as tapping its checkbox.  
The picker reports the number of selected items at its bottom right corner, and the user can preview the set of selected items by tapping the Selected Only checkbox at the bottom left of the picker. An application can suppress the count of selected items, the Selected Only checkbox, or both in any of its overview pickers.  
If a value in the right column of an overview picker begins with a black diamond, tapping it pops up a list picker that contains alternate values from the stored data plus a command for entering a new value. [Figure 4-16](#page-147-0) shows how this works in an overview picker that lists names and phone numbers.  
If a user selects an item for which there is no value displayed in the right column of an overview picker, a slip appears in which the user can enter the needed information.  
An overview picker can be set up to only allow selecting one item. In this case selecting an item automatically deselects the previously selected item. Setting up an overview picker for only one selection does not change the way the picker looks (the checkbox next to each item does not change to a radio button).  
Overview Pickers **4-21**  
<span id="page-147-0"></span>**Figure 4-16** Entering a new value in an overview picker  
![](images/_page_147_Figure_3.jpeg)  
1. A user taps in the second column where a diamond indicates a list picker will pop up  
![](images/_page_147_Figure_5.jpeg)  
2. The user picks the New command  
![](images/_page_147_Figure_7.jpeg)  
3. The user enters a new value in a slip and then taps the slip's Close box  
![](images/_page_147_Figure_9.jpeg)  
4. The new value appears in the overview picker and the item is selected  
When a user closes an overview picker, the selected item or items are customarily displayed next to the picker label. The label and the value are customarily aligned at their baselines. The value should be displayed in the casual font, not in the system font like the picker label and picker items.  
#### Scrolling Items 4  
Most overview pickers list more items than can be displayed at once. Users can see more items by using the scroll arrows in the picker (unless the application has suppressed them). The color of the scroll arrow indicates whether tapping it will bring more items into view. An arrow is black if tapping it will bring more items into view. An arrow is white if tapping it will not bring more items into view.  
<span id="page-148-0"></span>Users can also scroll overview pickers with the universal scroll arrows. In addition, users can scroll overview pickers by dragging from the middle of the picker past the top or bottom of the picker.  
#### Creating New Items 4  
When the item a user wants is not included in an overview picker, the user doesn't have to close the picker and go to another application to create the item. Users can create entirely new items without leaving an overview picker that has a New button. (If you don't want users to be able to create new items from within an overview picker, you can suppress the picker's New button.)  
To create a new item, a user taps the New button at the bottom of the overview picker. A slip appears in which the user enters just the information needed for the picker. The new item is added to the picker and to the other information in Newton storage. For example, tapping the New button in an overview picker that lists names and fax numbers would bring up a slip in which the user enters a first name, last name, and fax number. The name and fax number would be added to the overview picker and to the Names File data. Later the user could use the Names File application to fill in additional information for the new person.