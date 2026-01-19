<!-- Chunk 287 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 666 -->
Use a search field to allow users to search for terms within your application. A search field supports keyboard focus, so if searching is important in your application, provide the keyboard shortcut Command-Option-F, which allows users to navigate to a search field without using the mouse.  
Depending on how you implement searching functionality in your application, you can specify a search field that begins searching as soon as the user starts typing, or that begins the search when the user presses Return or Enter.  
#### Search Field Contents and Labeling  
By default, a search field displays the magnifying icon at its left edge. A search field can also contain an icon the user clicks to stop the search or clear the field. It's appropriate to use this icon if the user has to click a button or press a key to initiate the search, especially if the search might take more than a second or two. If you use this icon, consider displaying a progress indicator for lengthy searches. The magnifying glass and stop-search icons are supplied automatically.  
A search field can include a menu that allows users to view a history of recent searches. However, if you provide this functionality you should consider not providing it by default; you should also allow users to turn it off for privacy reasons. If you need to allow users to choose different types of searches or define the context or scope of a search, consider providinga scope bar in yourwindow(see ["Scope](#page-206-0) [Bars"](#page-206-0) (page 207) for more information).  
Text Controls **331 2008-01-15 | © 1992, 2001-2003, 2008 Apple Inc. All Rights Reserved.**  
A search field does not need an introductory label because users recognize this control (and the magnifying glass icon) from elsewhere in Mac OS X. If you place a search field in a toolbar, however, you should supplythe label "Search" to be displayedwhen users customize the toolbar to showicons and text or text only.  
#### Search Field Specifications  
**Control sizes**: Search fields are available in regular and small sizes. The height of a search field is fixed for its size, but you decide how long the control should be. The heights for each size of search field are listed below (Figure 15-75 shows a regular-size search field):  
■ Regular size: 22 pixels high.  
<span id="page-331-1"></span>■ Small: 19 pixels high.  
**Figure 15-75** A regular-size search field  
![](images/_page_331_Picture_8.jpeg)  
#### Search Field Implementation  
<span id="page-331-0"></span>Search field controls are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSSearchField class.