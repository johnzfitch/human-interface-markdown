<!-- Chunk 375 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 321 -->
**List views** display ordered records in a table in which users can resize, rearrange, and sometimes add and subtract, columns representing attributes of the data.  
Sort the rows in the table by the selected column heading. You can implement sorting on secondary attributes behind the scenes, but the user should see only one column selected at a time. If a user clicks an already selected column heading, change the direction of the sort.  
List views may contain disclosure triangles to reveal a list hierarchy, but only in one column. (See Figure 14-55.)  
<span id="page-268-1"></span>Items may be editable depending on the purpose of your application. In the Finder, for example, items in the Name column are editable when in list view, but nothing else is.  
![](images/_page_268_Picture_11.jpeg)  
**Figure 14-55** List view with disclosure triangles  
**Carbon:** List views are available in the Browsers & Tab palette of Interface Builder. To create one programmatically, use the list version of the data browser control.  
View Controls **269**  
Controls  
**Cocoa:** List views are available in the Data palette of Interface Builder. To create a simple list view programmatically, use the NSTableView class. NSOutlineView in column format gives you disclosure triangles.