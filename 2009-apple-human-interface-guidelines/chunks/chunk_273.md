<!-- Chunk 273 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 825 -->
A **search field** is a text field with rounded ends in which the user enters new text or modifies existing text that identifies items to search for. For example, the Finder provides a search field in its toolbar, as shown in Figure 15-74. For information on waysto provide search functionality in your application,see ["Spotlight"](#page-77-1) (page 78) and ["Scope](#page-204-0) Bars" (page 205).  
<span id="page-326-0"></span>**Figure 15-74** A search field in a toolbar  
![](images/_page_326_Picture_3.jpeg)  
**Important:** A search field is one of the three window-body controlsthat can also be used in a window-frame area. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-254-1) Controls" (page 255).  
#### Search Field Usage  
Use a search field to allow users to search for terms within your application. A search field supports keyboard focus, so if searching is important in your application, provide the keyboard shortcut Command-Option-F, which allows users to navigate to a search field without using the mouse.  
<span id="page-326-1"></span>Depending on how you implement searching functionality in your application, you can specify a search field that begins searching as soon as the user starts typing, or that begins the search when the user presses Return or Enter.  
#### Search Field Contents and Labeling  
By default, a search field displays the magnifying icon at its left edge. A search field can also contain an icon the user clicks to stop the search or clear the field. It's appropriate to use this icon if the user has to click a button or press a key to initiate the search, especially if the search might take more than a second or two. If you use this icon, consider displaying a progress indicator for lengthy searches. The magnifying glass and stop-search icons are supplied automatically.  
A search field can include a menu, but you should not use it to display search history (recent searches) for privacy reasons. Although you can use the menu to allow usersto choose different types ofsearches or define the context orscope of a search, consider providing a scope bar in your window instead (see ["Scope](#page-204-0) Bars" (page 205) for more information).  
A search field does not need an introductory label because users recognize this control (and the magnifying glass icon) from elsewhere in Mac OS X. If you place a search field in a toolbar, however, you should supply the label "Search" to be displayed when users customize the toolbar to show icons and text or text only.  
#### Search Field Specifications  
**Control sizes**: Search fields are available in regular and small sizes. The height of a search field is fixed for its size, but you decide how long the control should be. The heights for each size of search field are listed below (Figure 15-75 shows a regular-size search field):  
- Regular size: 22 pixels high.
- <span id="page-327-1"></span>● Small: 19 pixels high.  
**Figure 15-75** A regular-size search field  
![](images/_page_327_Picture_7.jpeg)  
#### Search Field Implementation  
<span id="page-327-0"></span>Search field controls are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSSearchField class.