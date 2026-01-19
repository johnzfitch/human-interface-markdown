<!-- Chunk 200 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 463 -->
**Group boxes**, like separators, are used to break a window into distinct logical areas. A group box provides a more pronounced separation than a separator. Use a group box when you want a set of controls to be perceived as a single element. Avoid putting too many controls in group boxes so they don't look cluttered.  
Group boxes can be untitled or titled. If titled, they may have text-only titles, checkbox titles, or pop-up menu titles. If the group box uses a checkbox title, the items in the group box should be active only when the checkbox is checked. Pop-up menu titles should either be centered or be 14 pixels from the left side of the group box.  
Grouping Controls **199**  
<span id="page-199-0"></span>**Figure 10-55** Types of group boxes  
![](images/_page_199_Picture_3.jpeg)  
**Carbon:** Group boxes are available in Interface Builder. To create one programmatically, use the function CreateGroupBoxControl, CreateCheckGroupBoxControl, or CreatePopupGroupBoxControl.  
**Cocoa:** Group boxes are available in Interface Builder. To create one programmatically, use the NSBox class. See *Boxes* in Cocoa User Experience documentation.  
#### <span id="page-199-1"></span>Group Box Specifications  
**Figure 10-56** A group box with a text-only title  
![](images/_page_199_Picture_8.jpeg)  
<span id="page-200-0"></span>**Figure 10-57** A group box with a checkbox title  
![](images/_page_200_Picture_3.jpeg)  
**Figure 10-58** Group boxes with pop-up menu titles  
<span id="page-200-1"></span>![](images/_page_200_Picture_5.jpeg)  
![](images/_page_200_Picture_6.jpeg)  
#### ■ **Label text size:**  
❏ Full size: System font  
<span id="page-200-2"></span>❏ Small: Small system font  
❏ Mini: Mini system font  
#### ■ **Spacing:**  
❏ Leave at least 20 pixels from the edge of the group box to the edge of the window.  
Controls