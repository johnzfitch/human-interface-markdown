<!-- Chunk 161 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 1188 -->
If an action might take a while, then the user should be able to cancel it by holding the Command key while pressing the period (.) key (as described in Chapter 3, "User Actions: The Keyboard and Mouse"). In addition, sometimes it's convenient for buttons that perform a time-consuming action to have a stop state, to make it more obvious to users that they can interrupt the action.  
If you implement a button with a stop state, the button's appearance should change as shown below.  
![](images/_page_154_Picture_8.jpeg)  
before clicking  
![](images/_page_154_Picture_10.jpeg)  
during first click  
![](images/_page_154_Picture_12.jpeg)  
after first click  
![](images/_page_154_Picture_14.jpeg)  
during second click (if any)  
![](images/_page_154_Picture_16.jpeg)  
after action is finished or canceled  
The button's action should be started when the user completes the first click (by releasing the mouse button). Similarly, the button's action should be stopped when the user finishes clicking the stop button.  
#### **Text Fields**  
![](images/_page_155_Picture_1.jpeg)  
A text field is a slot where the user can type in a single line of data—such as a file name, a part number, or an address. The text is editable and selectable. The data is entered only when the user types Return or clicks a button that's associated with the field. If the user enters more text than will fit in the field, the entry automatically scrolls so that the insertion point stays visible.  
A text field should have a white background and be surrounded by a bezeled border that makes it appear inset from the surface of the screen. When the text field is temporarily disabled, the text becomes gray (just like the label of a button), but the background color doesn't change.  
If a text field is not usually edited or selected but can be—as is, for example, the name associated with a file icon in the Workspace Manager File Viewer—the text should have a gray background with no bezeled border. When the user selects the text, the text field's background should turn white, and the selected text's background should be light gray.  
Text fields can be titled and arranged in groups to produce an on-screen form, such as the one illustrated below.  
| Name:     |          |
|-----------|----------|
| Street:   | 200000   |
| City:     |          |
| State:    |          |
| Zip Code: | 2000 WES |  
When there's more than one text field in a window, the Tab key can move the selection—the point where typing will appear—from one field to another:  
Tab Moves from one text field to the next one in the series. For example, in the form illustrated above, Tab would cause the current selection to jump from the Name field to the Street field to the City field, and so on.  
Shift-Tab Moves from one text field to the previous one in the series.  
When the user presses the Return key after typing in a text field, the field usually makes something happen. Data might be entered and processed, a search might begin for text that matches the string in the field, or a document might be saved to a file name the user typed. Exactly what happens is up to the application.  
To let users know what to expect, it's recommended that you include a button in the display to act as the equivalent of Return. The button's label is an explicit reminder of what Return will do. From the user's point of view, Return is simply a shortcut for the action of the button.  
The Print panel below has an example of using a button for the Return key's action. The user can start printing the document either by pressing the Print button or by pressing Return while editing any of the three text fields. If the user presses Return, the Print button pushes in and highlights as if it were pressed.  
![](images/_page_156_Figure_2.jpeg)  
For the user's convenience, if the action associated with Return is repeatable, Return may select all the text in the same field so the user can easily replace it.  
When a text field is part of a form, Return might not perform any particular action of its own. Instead, it will do just what Tab does-move the selection to the next field. Action on a button or other control is required to enter data typed into the form.  
Generally, text fields accept unrestricted data, but sometimes an entry won't be acceptable if it's the wrong data type-if, for example, the user types in a floating-point number when an integer is called for. Typical examples of restricted data include the following:  
- Unsigned or signed integers
- Unsigned or signed floating-point numbers
- Dates  
If the user's entry isn't acceptable, all of the text in the field should be selected and highlighted. The user can make any necessary corrections and try again.