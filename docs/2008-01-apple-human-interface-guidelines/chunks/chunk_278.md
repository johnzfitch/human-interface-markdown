<!-- Chunk 278 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 323 -->
A **placard** is a small control at the bottom of awindowused to displayinformation, such as the current page number or the current magnification level.  
<span id="page-312-2"></span>Typically, placards are used in document windows as a way to quickly modify the view of the contents—for example, to change the current page or the magnification. The most familiar use of the placard is as a pop-up menu placed at the bottom of a window, to the left of the horizontal scroll bar, as shown in Figure 15-54.  
**Figure 15-54** A placard  
![](images/_page_312_Picture_14.jpeg)  
If you need to offer a menu of commands that affect the contents of the window in ways other than magnification or number of pages per view, don't add the commands to the placard's menu. Instead, you should use an Action menu (see "Action [Menus"](#page-295-0) (page 296) for more information on Action menus).  
Placards are not available in Interface Builder. To create one using Application Kit programming interfaces, subclass NSScrollView (for an example of how to do this, see the Sketch sample code located in /Developer/Examples/AppKit when the Developer package is installed). A placard is 15 pixels high and text on it should be in either the small system font or the label font.  
Selection Controls **313**