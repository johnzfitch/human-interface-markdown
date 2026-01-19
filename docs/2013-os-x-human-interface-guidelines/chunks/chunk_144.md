<!-- Chunk 144 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 334 -->
The **stepper control** (also known as little arrows) allows users to increment or decrement values, usually in conjunction with a text field that indicates the current value.  
![](images/_page_273_Picture_3.jpeg)  
The text field may or may not be editable.  
<span id="page-273-1"></span>The stepper control is available in Interface Builder. To create one using AppKit programming interfaces, use the NSStepper class.  
#### Placard  
A **placard** displays information at the bottom edge of a window.  
![](images/_page_273_Picture_8.jpeg)  
**Note:** Placards are not recommended for use in apps that run in OS X v10.7 and later.  
Placards are not available in Interface Builder. To create one using AppKit programming interfaces, subclass NSScrollView.  
Typically, placards are used in document windows as a way to enable quick modifications to the view of the contents—for example, to change the current page or the magnification. The most familiar use of the placard is as a pop-up menu placed at the bottom of a window, to the left of the horizontal scroll bar.  
![](images/_page_273_Picture_12.jpeg)  
**Don't add to the placard menu commands that affect the contents of the window in other ways.** Instead, you should use an Action menu (for more information on Action menus, see ["Action](#page-260-0) Menu" (page 261)).