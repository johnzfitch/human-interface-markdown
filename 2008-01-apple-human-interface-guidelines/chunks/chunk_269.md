<!-- Chunk 269 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 403 -->
Use a path control when you want to display the file-system location of the currently selected item in a way that is not overly technical. You can also use a path control to allow users to retrace their steps along a path and open folders they visited earlier.  
#### Path Control Contents and Labeling  
All three path-control styles display text in addition to icons for applications, folders, and document types. When users clickthe pop-up style path control, a pop-up menu appears,which lists all locations in the path and a Choose menu item. Users can use the Open dialog opened by the Choose item to view the contents of the selected folder. (See "The Open [Dialog"](#page-247-0) (page 248) for more information on the Open dialog.)  
#### Path Control Specifications  
The standard-style path control is available in regular size only. The navigation bar and pop-up styles are each available in regular, small, and mini sizes.  
You specify the horizontal length of the standard and navigation bar styles; if the displayed path is too long to fit in the control, the folder names between the first location and the last are hidden, as shown in Figure 15-39.  
<span id="page-301-1"></span>**Figure 15-39** A path control can accommodate a large number of locations  
![](images/_page_301_Picture_4.jpeg)  
#### Path Control Implementation  
<span id="page-301-0"></span>The path control is available in Interface Builder. You can change the style of the control in the Attributes pane of the inspector panel. To create this control using Application Kit programming interfaces, use the NSPathControl class.