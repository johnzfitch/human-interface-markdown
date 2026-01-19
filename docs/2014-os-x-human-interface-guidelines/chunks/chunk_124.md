<!-- Chunk 124 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 397 -->
A **path control** displays the file-system path of the currently selected item. For example, when you choose Show Path Bar, Finder uses one style of path control to display the path of the currently selected item at the bottom of the window.  
![](images/_page_201_Figure_4.jpeg)  
**API Note:** To define a path control in your code, use the NSPathControl class.  
There are three styles of path control, all of which are suitable for use in the window body:  
- Standard
- Navigation bar
- Pop up  
All three path-controlstyles display text in addition to iconsfor apps, folders, and document types. When users click the pop-up style path control, a pop-up menu appears, which lists all locations in the path and a Choose menu item. Users can use the Open dialog opened by the Choose item to view the contents of the selected folder. For more information on the Open dialog, see The Open [Dialog](#page-159-0) (page 160).  
If the displayed path is too long to fit in the control, the folder names between the first location and the last are hidden, as shown here in the path control in a Finder window.  
![](images/_page_201_Picture_12.jpeg)  
Use a path control to display the file-system location of the currently selected item in a way that is not overly technical. You can also use a path control to allow users to retrace their steps along a path and open folders they visited earlier.  
**Use a path control only when necessary.** For most apps, a path control is unlikely to be useful, because few apps need to provide a file-system browsing experience the way the Finder does.