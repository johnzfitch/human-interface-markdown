<!-- Chunk 149 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 1791 -->
View controls allow users to modify how information is presented to them in a window. Some view controls allow you to provide additional information or functionality that remains hidden until users choose to see it, and others give you a frame for organizing and displaying data, such as a list.  
**Important:** The controls described in thissection are suitable for use in the window body only; they should not be used in the window-frame areas. For more information about controls that are designed specifically for the toolbar (and bottom bar), see ["Window-Frame](#page-240-0) Controls" (page 241).  
#### <span id="page-289-0"></span>Disclosure Triangle  
A **disclosure triangle** displays(or discloses) information or functionality associated with the primary information in a window.  
![](images/_page_289_Picture_4.jpeg)  
Disclosure triangles are available in Interface Builder. To create one using AppKit programming interfaces, use NSButton and set the bezel style to NSDisclosureBezelStyle and the button type to NSPushOnPushOffButton.  
#### Appearance and Behavior  
A disclosure triangle is in the closed position (that is, pointing to the right) by default. When the user clicks a disclosure triangle, it points down and the additional information is displayed.  
#### Guidelines  
Use a disclosure triangle when you want to provide a simple default view ofsomething but need to allow users to view more details or perform additional actions at specific times.  
In general, you can use a disclosure triangle in the following two ways:  
● To reveal more information in dialogs that have a minimal state and an expanded state. For example, you might want to use a disclosure triangle to hide explanatory information about a choice that most users aren't interested in seeing.  
● To revealsubordinate itemsin a hierarchical list. For example, the Mail Photo Browser panel uses a disclosure triangle to reveal specific iPhoto categories.  
![](images/_page_290_Picture_2.jpeg)  
**Supply a label for a disclosure triangle in a dialog.** The label should indicate what is disclosed or hidden and it should change, depending on the position of the disclosure triangle. For example, when the disclosure triangle is closed the label might be "Show advanced settings;" when the disclosure triangle is open the label can change to "Hide advanced settings."  
<span id="page-290-0"></span>**Don't use a disclosure triangle to display additional choices associated with a specific control.** If you need to do this, use a disclosure button instead (for more information about this control,see ["Disclosure](#page-290-0) Button" (page 291)).  
#### Disclosure Button  
A **disclosure button** expands a dialog or panel to display a wider range of choicesrelated to a specific selection control.  
![](images/_page_290_Picture_7.jpeg)  
Disclosure buttons are available in Interface Builder. To create one using AppKit programming interfaces, use NSButton and set the bezel style to NSRoundedDisclosureBezelStyle and the button type to NSPushOnPushOffButton.  
#### Appearance and Behavior  
A disclosure button is button that contains a small triangular icon. By default, a disclosure button is in the closed position (that is, pointing down). When the user clicks a disclosure button, the window expands to reveal the additional choices and the disclosure button changes to point up.  
#### Guidelines  
Use a disclosure button when you need to provide additional options that are closely related to a specific list of choices.  
**Don't use a disclosure button to display additional information or functionality or subordinate items in a list.** If you need to display additional information or functionality related to the contents of a window or a section of a window, or if you need a way to reveal subordinate items in a hierarchical list, use a disclosure triangle instead. For more information on this control, see ["Disclosure](#page-289-0) Triangle" (page 290).  
**Place a disclosure button close to the control to which it's related.** Users need to understand how the expanded choices are related to their current task. For example, the Preview Export As dialog puts a disclosure button close to the Export Astext field,so that users understand that the expanded view will help them choose a location for their document.  
![](images/_page_291_Picture_7.jpeg)  
#### <span id="page-291-0"></span>List View  
A **list view** displays data in a one-column list, with optional additional columnsthat display attributes associated with the data.  
List views are available in Interface Builder. To create a simple list view using AppKit programming interfaces, use the NSTableView class. To get disclosure triangles in a list, use an NSOutlineView object in column format.  
#### Appearance and Behavior  
A list view displays the entire set of data in the leftmost column (in systems that use left-to-right script). When the data is hierarchical, the child objects are revealed within the primary column, not in other columns (list views use disclosure triangles to indicate objects that contain other objects).  
Additional columns in a list view display attributes that apply to the data in the primary column; they do not contain data that isspecific to a different level of hierarchy. In general, users can resize, rearrange, and sometimes add and subtract the columns that represent attributes of the list data.  
When users click a disclosure triangle to reveal the child items contained within another item, the list lengthens and the leftmost column can widen. If the primary column widens, other columns might shift to the right, but they do not change their headings or order.  
**Note:** List views, like other scrolling areas, are governed by the user's scroll direction setting in System Preferences.  
#### Guidelines  
Use a list view to display a list items along with various attributes of each item. If you need to display a simple list of items, and you don't need to display associated attributes, you might want to use a scrolling list instead (for more information about scrolling lists, see ["Scrolling](#page-287-0) List" (page 288)). Using a list view, you can create a column for each attribute that is associated with the items you display.  
**Sort the rows in the list view by the selected column heading.** You can implement sorting on secondary attributes behind the scenes, but the user should see only one column selected at a time. If the user clicks an already selected column heading, change the direction of the sort.  
**Determine whether list items should be editable.** In the Finder, for example, items in the Name column (the leftmost column) are editable when in list view, but nothing else is. This makes sense because it allows users to select and edit a file or folder name in the same way that they do in all the other Finder view modes (that is, icon, column, and Cover Flow).  
**Create column headers that are nouns or short noun phrases that describe an attribute of the data.** When you use clear,succinct attribute names, users quickly understand what information is available in each column.