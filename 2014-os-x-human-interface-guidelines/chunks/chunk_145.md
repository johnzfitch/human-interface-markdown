<!-- Chunk 145 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 200 -->
A **placard** displays information at the bottom edge of a window.  
![](images/_page_232_Picture_6.jpeg)  
Placards are not available in Interface Builder. To create one using AppKit programming interfaces, subclass NSScrollView.  
Typically, placards are used in document windows as a way to enable quick modifications to the view of the contents—for example, to change the current page or the magnification. The most familiar use of the placard is as a pop-up menu placed at the bottom of a window, to the left of the horizontal scroll bar.  
![](images/_page_232_Picture_9.jpeg)  
**Don't add to the placard menu commands that affect the contents of the window in other ways.** Instead, you should use an Action menu (for more information on Action menus, see [Action](#page-191-0) Menu (page 192)).