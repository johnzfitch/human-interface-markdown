<!-- Chunk 99 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 1761 -->
A user makes a list picker pop up by tapping the button or label that controls it. While the picker is open, the application highlights the picker's controlling button or label. Nothing else happens until the user touches the screen again. The user does not have to press and hold the pen on the button or label to keep the picker open; the picker stays open until the user touches the screen again. If the user touches the screen outside the list, the picker goes away.  
#### Picking an Item 4  
A user picks an item listed in a list picker by tapping the item. The picked item blinks briefly, the picker disappears, and the action or effect associated with the picked item happens. [Figure 4-7](#page-135-0) shows the sequence of events for the Set button in the built-in Clock application.  
List Pickers **4-9**  
<span id="page-135-0"></span>**Figure 4-7** Using a list picker from a button  
![](images/_page_135_Picture_3.jpeg)  
![](images/_page_135_Picture_4.jpeg)  
![](images/_page_135_Picture_5.jpeg)  
2. User taps a listed item to pick it  
![](images/_page_135_Picture_7.jpeg)  
3. Picker disappears 4. Picked item takes effect but button stays highlighted until…  
![](images/_page_135_Picture_9.jpeg)  
In the case of a list picker that pops up next to a text label, the current value of the picker (the most recently picked item) is usually displayed next to the picker label. The label and the value are customarily aligned at their baselines. The value should be displayed in the casual font, not in the system font like the picker label and picker items. Figure 4-8 shows the sequence of events with the label picker in the Sleep preferences slip.  
**Figure 4-8** Using a list picker from a label  
![](images/_page_135_Picture_13.jpeg)  
![](images/_page_135_Picture_15.jpeg)  
1. User taps a label to pop up its picker 2. User taps a listed item to pick it  
![](images/_page_135_Picture_17.jpeg)  
3. Picker disappears and picked item appears next to picker label  
<span id="page-136-0"></span>If a user touches a picker list and slides the pen instead of lifting it, the picker tracks the pen movement. As the pen appears over an item in the list, the item is highlighted. When the user lifts the pen within the list, the currently highlighted item blinks briefly, the picker disappears, and the effect associated with the picked item happens. If the user slides the pen outside the list, so that no item is highlighted, and then lifts the pen, the picker simply goes away. The display of electronic ink is turned off while the pen is tracked.  
An item that can't be selected, such as a separator line, is not highlighted when a user taps it or slides the pen over it. Tapping an unselectable item or lifting the pen while it is over an unselectable item makes the picker go away.  
After the user picks an item and the picker disappears, your application must continue to highlight the label or button that controls the picker until the action or effect associated with the picked item is complete. In the case of a picker item that displays an ordinary slip (not a status slip), the picker's controlling label or button stays highlighted only until the slip appears. Keeping the label or button highlighted provides the minimal feedback to the user that the application is still working. When a process begun by a picker item takes more than a few seconds, your application should provide more feedback by displaying a status slip that names the process underway (as described in ["Status Slips" on](#page-63-0)  [page 2-20](#page-63-0)).  
#### User Editing of Pickers 4  
If you want to allow users to be able to add, remove, and change items in a list picker, include an item "Edit" or "Edit Picker" at the bottom of the picker, with a separator line above it. Choosing this item should bring up a slip in which users can edit the picker. The slip should clearly indicate how many items the picker can contain. Title the slip to make its purpose clear, for example "Edit Category List."  
Instead of allowing users to edit picker items, an application could automatically include recent inputs for an input field in that field's picker. For information on input fields, see [Chapter 6, "Data Input."](#page-168-0)  
List Pickers **4-11**  
#### <span id="page-137-0"></span>Scrolling 4  
A list picker may contain too many items to display at once on some Newton devices. This can happen when a user rotates the display (by tapping the Rotate button in the Extras Drawer). It can also happen if a user adds many items to a customizable picker, such as a folder picker.  
When a list picker becomes too long to fit on the screen, the Newton operating system automatically reduces the picker's length and adds ordinary local scroll arrows to the picker. A user can tap the scroll arrows to bring more picker items into view. Figure 4-9 shows a scrolling folder picker.  
**Figure 4-9** List pickers that are too long to display all at once have scroll arrows  
![](images/_page_137_Figure_6.jpeg)  
As usual, the color of the scroll arrow indicates whether tapping it will bring more items into view. An arrow is black if tapping it will bring more items into view. An arrow is white if tapping it will not bring more items into view.  
Users can also scroll list pickers by dragging from the middle of the picker past the top or bottom of the picker. Users cannot scroll a list picker with the universal scroll arrows. Tapping a universal scroll arrow or anywhere else outside a list picker makes the picker go away.  
<span id="page-138-0"></span>Scrolling pickers are harder to use than pickers that don't scroll, because users have to remember the picker items that aren't currently visible. You should keep your pickers short and avoid scrolling pickers in your applications.  
#### Index Tabs 4  
If the list of picker items is very long, scrolling from one end to the other can be tedious. To give users a quicker method of traveling through a long list of picker items, you can augment scroll arrows with a series of small labeled index tabs displayed along the right edge of the picker. The tabs essentially divide the picker items into sections alphabetically, and a user taps a tab to see the section it identifies. Figure 4-10 illustrates picker scroll arrows and index tabs.  
**Figure 4-10** A lengthy picker can include scroll arrows and index tabs  
![](images/_page_138_Figure_6.jpeg)  
Tapping an index tab scrolls to the picker items that begin with the first letter of the tapped tab. Double-tapping an index tab scrolls to the picker items that begin with the second letter of the tapped tab. Triple-tapping an index tab scrolls to the picker items that begin with the third letter of the tapped tab.  
In a list picker with an index tab, tapping a listed item selects the item but doesn't close the picker. To close the picker and confirm the selection, a user taps the picker's Close box. To cancel the selection and close the picker, a user taps outside the picker.  
List Pickers **4-13**