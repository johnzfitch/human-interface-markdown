<!-- Chunk 140 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 314 -->
A **group box** provides a visual way to break a window into distinct logical areas.  
![](images/_page_228_Figure_3.jpeg)  
**API Note:** To define a group box in your code, use the NSBox class.  
The outline of a group box is similar in appearance to the outline of a tab view, except that a group box does not include a tab view control (for more information about tab views, see Tab [View](#page-226-0) (page 227)). Users don't interact with a group box (for example, they can't directly resize it), but they can interact with the controls inside it.  
Group boxes tend to be untitled, but they can include a text title that appears above the outline of the box.  
Group boxes are seldom used in modern Mac apps. You might want to use a group box when you want users to understand logical groupings of controls in a window.  
**Avoid nesting group boxes.** Nested group boxes take up a lot of space, and it can be difficult for users to perceive individual boundaries when group boxes are nested too deeply. Instead, consider using white space to group content within a group box.  
**Use sentence-style capitalization in the title of a group box.** For more information on thisstyle,see [Capitalizing](#page-46-0) [Labels](#page-46-0) and Text (page 47).