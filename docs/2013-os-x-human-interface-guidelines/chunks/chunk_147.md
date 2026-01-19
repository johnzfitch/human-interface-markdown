<!-- Chunk 147 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 3941 -->
View controls allow users to modify how information is presented to them in a window. Some view controls allow you to provide additional information or functionality that remains hidden until users choose to see it, and others give you a frame for organizing and displaying data, such as a table.  
**Important:** The controls described in thissection are suitable for use in the window body only; they should not be used in the window-frame areas. For more information about controls that are designed specifically for the toolbar (and bottom bar), see ["Window-Frame](#page-237-0) Controls" (page 238).  
#### <span id="page-287-0"></span>Disclosure Triangle  
A **disclosure triangle** displays(or discloses) information or functionality associated with the primary information in a window.  
![](images/_page_287_Picture_4.jpeg)  
Disclosure triangles are available in Interface Builder. To create one using AppKit programming interfaces, use NSButton and set the bezel style to NSDisclosureBezelStyle and the button type to NSPushOnPushOffButton.  
#### Appearance and Behavior  
A disclosure triangle is in the closed position (that is, pointing to the right) by default. When the user clicks a disclosure triangle, it points down and the additional information is displayed.  
#### Guidelines  
Use a disclosure triangle when you want to provide a simple default view ofsomething but need to allow users to view more details or perform additional actions at specific times.  
In general, you can use a disclosure triangle in the following two ways:  
● To reveal more information in dialogs that have a minimal state and an expanded state. For example, you might want to use a disclosure triangle to hide explanatory information about a choice that most users aren't interested in seeing.  
● To revealsubordinate itemsin a hierarchical list. For example, the Mail Photo Browser panel uses a disclosure triangle to reveal specific iPhoto categories.  
![](images/_page_288_Picture_2.jpeg)  
**Supply a label for a disclosure triangle in a dialog.** The label should indicate what is disclosed or hidden and it should change, depending on the position of the disclosure triangle. For example, when the disclosure triangle is closed the label might be "Show advanced settings;" when the disclosure triangle is open the label can change to "Hide advanced settings."  
<span id="page-288-0"></span>**Don't use a disclosure triangle to display additional choices associated with a specific control.** If you need to do this, use a disclosure button instead (for more information about this control,see ["Disclosure](#page-288-0) Button" (page 289)).  
#### Disclosure Button  
A **disclosure button** expands a dialog or panel to display a wider range of choicesrelated to a specific selection control.  
![](images/_page_288_Picture_7.jpeg)  
Disclosure buttons are available in Interface Builder. To create one using AppKit programming interfaces, use NSButton and set the bezel style to NSRoundedDisclosureBezelStyle and the button type to NSPushOnPushOffButton.  
#### Appearance and Behavior  
A disclosure button is button that contains a small triangular icon. By default, a disclosure button is in the closed position (that is, pointing down). When the user clicks a disclosure button, the window expands to reveal the additional choices and the disclosure button changes to point up.  
#### Guidelines  
Use a disclosure button when you need to provide additional options that are closely related to a specific list of choices.  
**Don't use a disclosure button to display additional information or functionality or subordinate items in a list.** If you need to display additional information or functionality related to the contents of a window or a section of a window, or if you need a way to reveal subordinate items in a hierarchical list, use a disclosure triangle instead. For more information on this control, see ["Disclosure](#page-287-0) Triangle" (page 288).  
**Place a disclosure button close to the control to which it's related.** Users need to understand how the expanded choices are related to their current task. For example, the Preview Export As dialog puts a disclosure button close to the Export Astext field,so that users understand that the expanded view will help them choose a location for their document.  
![](images/_page_289_Picture_7.jpeg)  
#### <span id="page-289-0"></span>Table View  
A **table view** displays data in a one-column list, with optional additional columns that display attributes associated with the data.  
Table views are available in Interface Builder. To create a simple table view using AppKit programming interfaces, use the NSTableView class. To get disclosure triangles in a list, use an NSOutlineView object in column format.  
#### Appearance and Behavior  
A table view displays the entire set of data in the leftmost column (in systems that use left-to-right script). When the data is hierarchical, the child objects are revealed within the primary column, not in other columns (table views use disclosure triangles to indicate objects that contain other objects).  
Additional columns in a table view display attributes that apply to the data in the primary column; they don't contain data that isspecific to a different level of hierarchy. In general, users can resize, rearrange, and sometimes add and subtract the columns that represent attributes of the table data.  
When users click a disclosure triangle to reveal the child items contained within another item, the table lengthens and the leftmost column can widen. If the primary column widens, other columns might shift to the right, but they don't change their headings or order.  
In an editable table view, users begin editing by clicking once on a selected table row. This behavior allows the table view to respond differently to a double click. In the Finder, for example, users can double-click a file to open it or single-click a selected file to edit its name.  
**Note:** Table views, like other scrolling areas, are governed by the user's scroll direction setting in System Preferences.  
#### Guidelines  
Use a table view to display a list of items along with various attributes of each item. If you need to display a simple list of items, and you don't need to display associated attributes, you might want to use a scrolling list instead (for more information about scrolling lists, see ["Scrolling](#page-285-0) List" (page 286)). Using a table view, you can create a column for each attribute that is associated with the items you display.  
**Sort the rows in a table view by the selected column heading.** You can implement sorting on secondary attributes behind the scenes, but the user should see only one column selected at a time. If the user clicks an already selected column heading, change the direction of the sort.  
<span id="page-290-0"></span>**Create column headers that are nouns or short noun phrases that describe an attribute of the data.** When you use clear,succinct attribute names, users quickly understand what information is available in each column.  
#### Column View  
A **column view** displays a hierarchy of data, in which each level of the hierarchy is displayed in one column.  
![](images/_page_290_Picture_11.jpeg)  
Column views are available in Interface Builder. To create one using AppKit programming interfaces, use the NSBrowser class or an NSOutlineView object in column format.  
#### Appearance and Behavior  
Column views don't display disclosure triangles. The triangle displayed to the right of an item shows that the item contains other objects (to reveal those objects, users click anywhere on the item's row).  
Users scroll vertically within columns and horizontally between columns. When users click an object in one column, its contents(that is, its descendantsin the hierarchy) are revealed in a column to the right. Each column displays only those objectsthat are descendants of the item selected in the previous column. If the item selected in the previous column has no descendants, the column to the right might display details about the item.  
Columns in column views don't have headings, because a column view doesn't behave like a table. A column in a column view contains the objects that exist at a particular node in the hierarchy; it doesn't contain an attribute of every object in the hierarchy.  
**Note:** Column views, like other scrolling areas in OS X, are governed by the user's scroll direction setting in System Preferences.  
#### Guidelines  
Use a column view when there is only one way the data can be sorted or when you want to present only one way of sorting the data. A column view is also useful for displaying a deep hierarchy of data in which users frequently move back and forth among levels.  
**Display the first or root level of the hierarchy in the leftmost column (in systems that use left-right script).** As users select items, the focus moves to the right, displaying either the child objects at that node or, if there are no more children, the terminal object (a leaf node in the hierarchy). When the userselects a terminal object, you can display additional information about it in the rightmost column.  
**In general, allows users to resize columns.** This is especially helpful when the names of some items might be too long to display in the default width of a column.  
#### <span id="page-292-0"></span>Split View  
A **split view** groups together two or more other views, such as column or table views, and allows the user to adjust the relative width or height of those views (shown here with a "move" pointer resting on it).  
![](images/_page_292_Picture_3.jpeg)  
Split views are available in Interface Builder (you can specify the splitter width in the Style pop-up menu in the Attributes pane of the inspector). To create one using AppKit programming interfaces, use the NSSplitView class (note that the splitter bars are horizontal by default).  
#### Appearance and Behavior  
A split view includes a **splitter bar**, or **splitter**, between each of its subviews; for example, a split view with five subviews would have four splitters. Each subview is generally known as a **pane**. A split view can arrange views horizontally or vertically, but not both.  
**Note:** The standard splitter is known as a "zero-width" splitter, although it is actually 1 point wide. There is also a wider splitter available, which measures 9 points in width, but it is not frequently used.  
The entire splitter bar is a hot zone. In other words, when the pointer passes over any part of the splitter, the pointer changes to one of the move or resize pointers. (To learn more about the different pointers that are available, see "Use the Right [Pointer](#page-55-0) for the Job" (page 56).) For zero-width splitters, the hot zone includes two points on both sides of the splitter.  
#### Guidelines  
Use a split view to display two or more resizable content views.  
**In general, use the zero-width splitter.** Users are accustomed to the appearance of the zero-width splitter. You might want to use a wide splitter bar if you need to indicate a stronger visual distinction between panes, but this is unusual.  
**Don't let users lose the splitter.** A zero-width splitter can disappear when the user drags it far enough to hide the subview. To avoid this, you can define minimum and maximum sizes for the subviews so that the splitter remains visible. Alternatively, if you want to allow usersto completely hide a subview by dragging a zero-width splitter, you should provide a button that re-opens the subview.  
#### <span id="page-293-0"></span>Tab View  
A **tab view** presents information in a multipane format.  
![](images/_page_293_Picture_4.jpeg)  
Tab views are available in Interface Builder. To create one using AppKit programming interfaces, use the NSTabView class.  
#### Appearance and Behavior  
A tab view consists of a tab view control (which looks similar to a segmented control) combined with a set of views. Each segment in the tab view control is called a **tab**. The content area below a tab is called a **pane**, and each tab is attached to a specific pane. The tab view control is horizontally centered at the top edge of the view.  
Users click a tab to view the pane associated with that tab. Although different panes can contains different amounts of content, switching tabs does not change the overall size of the tab view or the window.  
#### Guidelines  
Use a tab view to present a small number of different content views in one place within a window. Depending on the size of the window, you can create a tab view that contains between two and about six tabs.  
**Use a tab view to present a few peer areas of content that are closely related.** The outline of a tab view provides a strong visual indication of enclosure. Users expect each tab to display content that is in some way similar or related to the content in the other tabs.  
**Ensure that each pane contains controls that affect only the contents ofthat pane.** Controls and information in one pane should not affect objects in the rest of the window or in other panes.  
**In general, inset the tab view so that a margin of window-body area is visible on all sides of the tab view.** The inset layout looks good and it allows you to provide additional controls that can affect the window itself (or other tabs). For example, the "Enable access for assistive devices" and "Show Universal Access status in the menu bar" checkboxesin Universal Access preferences are outside of the inset tab view, because they represent settings that affect accessibility generally.  
It's also possible to extend the side and bottom edges of a tab view so that they meet the window edges, although this is unusual.  
**Provide a label for each tab that describes the contents of the pane.** It's best when users can accurately predict the contents of a pane before they click the tab. Nouns or very short noun phrases work well for tab labels, although a verb (or short verb phrase) might make sense in some contexts. Tab labels should have title-style capitalization (for more information on this style, see ["Capitalizing](#page-303-0) Labels and Text" (page 304)).  
**Avoid using a pop-up menu as a tab-switcher.** This arrangement is not encouraged in modern Mac apps. If you have too many tabsto fit into a single tab view, you should investigate other waysto factor your information hierarchy.  
#### <span id="page-295-0"></span>Group Box  
A **group box** provides a visual way to break a window into distinct logical areas.  
![](images/_page_295_Picture_3.jpeg)  
Group boxes are available in Interface Builder. To create one using AppKit programming interfaces, use the NSBox class.  
#### Appearance and Behavior  
The outline of a group box is similar in appearance to the outline of a tab view, except that a group box does not include a tab view control (for more information about tab views, see "Tab [View"](#page-293-0) (page 294)). Users don't interact with a group box (for example, they can't directly resize it), but they can interact with the controls inside it.  
Group boxes tend to be untitled, but they can include a text title that appears above the outline of the box.  
#### Guidelines  
Group boxes are seldom used in modern Mac apps. You might want to use a group box when you want users to understand logical groupings of controls in a window.  
**Avoid nesting group boxes.** Nested group boxes take up a lot of space, and it can be difficult for users to perceive individual boundaries when group boxes are nested too deeply. Instead, consider using white space to group content within a group box.