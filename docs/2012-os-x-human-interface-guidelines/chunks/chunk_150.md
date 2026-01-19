<!-- Chunk 150 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 2201 -->
A **column view** displays a hierarchy of data, in which each level of the hierarchy is displayed in one column.  
![](images/_page_293_Picture_3.jpeg)  
Column views are available in Interface Builder. To create one using AppKit programming interfaces, use the NSBrowser class or an NSOutlineView object in column format.  
#### Appearance and Behavior  
Column views do not display disclosure triangles. The triangle displayed to the right of an item is an indicator that means the item contains other objects (to reveal those objects, users click anywhere on the item's row).  
Users scroll vertically within columns and horizontally between columns. When users click an object in one column, its contents (its descendants in the hierarchy) are revealed in a column to the right. Each column displays only those objectsthat are descendants of the item selected in the previous column. If the item selected in the previous column has no descendants, the column to the right might display details about the item.  
Columnsin column views do not have headings, because a column view does not behave like a table. A column in a column view contains the objects that exist at a particular node in the hierarchy; it does not contain an attribute of every object in the hierarchy.  
**Note:** Column views, like other scrolling areas in OS X, are governed by the user's scroll direction setting in System Preferences.  
#### Guidelines  
Use a column view when there is only one way the data can be sorted or when you want to present only one way of sorting the data. A column view is also useful for displaying a deep hierarchy of data in which users frequently move back and forth among levels.  
#### **Display the first or root level of the hierarchy in the leftmost column (in systems that use left-right script).**  
As users select items, the focus moves to the right, displaying either the child objects at that node or, if there are no more children, the terminal object (a leaf node in the hierarchy). When the userselects a terminal object, you can display additional information about it in the rightmost column.  
**In general, allows users to resize columns.** This is especially helpful when the names of some items might be too long to display in the default width of a column.  
#### <span id="page-294-0"></span>Split View  
A **split view** groups together two or more other views, such as column or list views, and allows the user to adjust the relative width or height of those views (shown here with a "move" pointer resting on it).  
![](images/_page_294_Picture_6.jpeg)  
Split views are available in Interface Builder (you can specify the splitter width in the Style pop-up menu in the Attributes pane of the inspector). To create one using AppKit programming interfaces, use the NSSplitView class (note that the splitter bars are horizontal by default).  
#### Appearance and Behavior  
A split view includes a **splitter bar**, or **splitter**, between each of its subviews; for example, a split view with five subviews would have four splitters. Each subview is generally known as a **pane**. A split view can arrange views horizontally or vertically, but not both.  
**Note:** The standard splitter is known as a "zero-width" splitter, although it is actually 1 point wide. There is also a wider splitter available, which measures 9 points in width, but it is not frequently used.  
The entire splitter bar is a hot zone. In other words, when the pointer passes over any part of the splitter, the pointer changes to one of the move or resize pointers. (To learn more about the different pointers that are available, see "Use the Right [Pointer](#page-55-0) for the Job" (page 56).) For zero-width splitters, the hot zone includes two points on both sides of the splitter.  
#### Guidelines  
Use a split view to display two or more resizable content views.  
**In general, use the zero-width splitter.** Users are accustomed to the appearance of the zero-width splitter. You might want to use a wide splitter bar if you need to indicate a stronger visual distinction between panes, but this is unusual.  
**Don't let users lose the splitter.** A zero-width splitter can disappear when the user drags it far enough to hide the subview. To avoid this, you can define minimum and maximum sizes for the subviews so that the splitter remains visible. Alternatively, if you want to allow usersto completely hide a subview by dragging a zero-width splitter, you should provide a button that re-opens the subview.  
#### <span id="page-296-0"></span>Tab View  
A **tab view** presents information in a multipane format.  
![](images/_page_296_Picture_3.jpeg)  
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
**Provide a label for each tab that describes the contents of the pane.** It's best when users can accurately predict the contents of a pane before they click the tab. Nouns or very short noun phrases work well for tab labels, although a verb (or short verb phrase) might make sense in some contexts. Tab labels should have title-style capitalization (for more information on this style, see ["Capitalizing](#page-305-0) Labels and Text" (page 306)).  
<span id="page-297-0"></span>**Avoid using a pop-up menu as a tab-switcher.** This arrangement is not encouraged in modern Mac apps. If you have too many tabsto fit into a single tab view, you should investigate other waysto factor your information hierarchy.  
#### Group Box  
A **group box** provides a visual way to break a window into distinct logical areas.  
![](images/_page_297_Picture_8.jpeg)  
Group boxes are available in Interface Builder. To create one using AppKit programming interfaces, use the NSBox class.  
#### Appearance and Behavior  
The outline of a group box is similar in appearance to the outline of a tab view, except that a group box does not include a tab view control (for more information about tab views, see "Tab [View"](#page-296-0) (page 297)). Users do not interact with a group box (for example, they can't directly resize it), but they can interact with the controls inside it.  
Group boxes tend to be untitled, but they can include a text title that appears above the outline of the box.  
#### Guidelines  
Group boxes are seldom used in modern Mac apps. You might want to use a group box when you want users to understand logical groupings of controls in a window.  
**Avoid nesting group boxes.** Nested group boxes take up a lot of space, and it can be difficult for users to perceive individual boundaries when group boxes are nested too deeply. Instead, consider using white space to group content within a group box.  
**Use sentence-style capitalization in the title of a group box.** For more information on this style, see ["Capitalizing](#page-305-0) Labels and Text" (page 306).