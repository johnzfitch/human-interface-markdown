<!-- Chunk 114 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 443 -->
A **scope button** specifies the scope of an operation, such as a search, or defines a set of scoping criteria.  
![](images/_page_186_Picture_5.jpeg)  
**Important:** Scope buttons are designed to be used in scope bars and related filter rows only. They are not intended to be used in window-frame areas or outside of a scope bar in the window body.  
To learn more about scope bars, see [Searching](#page-130-0) In a Window (page 131).  
**API Note:** To define a recessed scope button in your code, use the setBezelStyle: method of NSButtonCell with NSRecessedBezelStyle asthe argument. To create a round rectangle scope button, pass NSRoundRectBezelStyle as the argument to the setBezelStyle: method.  
Scope buttons are available in two different styles:  
The **recessed scope button**:  
The **round rectangle scope button**:  
Typically, round rectangle and recessed scope buttons contain text, but they can instead contain images.  
Use a recessed scope button to display types or groups of objects or locations that users select to narrow the focus of a search or other operation.  
Use a round rectangle scope button to allow users to save a set of search criteria and to change or set scoping criteria.  
For example, the Finder uses round rectangle scope buttons to display search criteria, such as creation and last opened dates, and to provide a save search button. The Finder location buttons, such as This Mac and Shared, are recessed scope buttons.  
![](images/_page_187_Picture_2.jpeg)  
If you want to display an image in a scope button, be sure to consider the system-provided images before you spend time designing your own. If you decide to design a custom icon for use in a scope button, see [Toolbar](#page-323-0) [Items](#page-323-0) (page 324).