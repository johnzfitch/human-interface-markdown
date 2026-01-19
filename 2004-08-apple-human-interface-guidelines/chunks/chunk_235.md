<!-- Chunk 235 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 326 -->
**List views** display ordered records in a table in which users can resize, rearrange, and sometimes add and subtract, columns representing attributes of the data.  
Sort the rows in the table by the selected column heading. You can implement sorting on secondary attributes behind the scenes, but the user should see only one column selected at a time. If a user clicks an already selected column heading, change the direction of the sort.  
List views may contain disclosure triangles to reveal a list hierarchy, but only in one column. (See Figure 10-47.)  
<span id="page-193-3"></span><span id="page-193-2"></span>Items may be editable depending on the purpose of your application. In the Finder, for example, items in the Name column are editable when in list view, but nothing else is.  
**Figure 10-47** List view with disclosure triangles  
![](images/_page_193_Picture_12.jpeg)  
**Carbon:** List views are available in the Browsers & Tab palette of Interface Builder. To create one programmatically, use the list version of the data browser control.  
<span id="page-194-5"></span>**Cocoa:** List views are available in the Data palette of Interface Builder. To create a simple list view programmatically, use the NSTableView class. NSOutlineView in column format gives you disclosure triangles.