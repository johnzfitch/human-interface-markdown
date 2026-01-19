<!-- Chunk 337 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 317 -->
The **column view** control provides a way for users to display and select items from an organized hierarchy of data.  
- A column view is useful when there is only one way the data can be sorted or when you want to present onlyonewayof sortingthe data. It is also useful for deep hierarchies, such as a file system, where users move back and forth among multiple levels frequently.
- <span id="page-265-2"></span>■ If the column view represents a tree of information, the root is on the left side. As users select items, the focus moves to the right, displaying either the possible choices at that branch or, if there are no more choices, the terminal object. When the user selects a terminal object, you may display additional information about it in the rightmost column.  
**Figure 14-56** Column view display of files  
![](images/_page_265_Picture_8.jpeg)  
<span id="page-265-4"></span><span id="page-265-1"></span>**Carbon:** Column views are available in the Browsers & Tab palette of Interface Builder. To create one programmatically, use the column version of the data browser control.  
**Cocoa:** Column views are available in the Data palette of Interface Builder. To create one programmatically, use the NSBrowser class or NSOutlineView in column format.