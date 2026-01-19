<!-- Chunk 128 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 634 -->
The easiest way to attach a submenu is simply to click its controlling command, but the user can also drag to the controlling command and release the mouse button while the cursor is still above it. The controlling command for an attached submenu stays highlighted to indicate that the submenu is attached.  
A supermenu and its attached submenu act like a single window. User actions that move or close the supermenu also move and close the submenu; an attached submenu has no close button of its own. A submenu attached to the main menu is assigned to the same window tier as the main menu.  
An attached submenu can also have its own attached submenu. This is illustrated below. The Librarian menu is attached to Services, and Services is attached to the main menu. Moving the main menu serves to move all three.  
![](images/_page_115_Picture_4.jpeg)  
#### **Tearing Off an Attached Submenu**  
The user can *tear off* an attached submenu by dragging it away from its supermenu. Moving it free of its supermenu gives it an independent life on-screen. As a sign of its independence, it gets, for the first time, its own close button. The close button identifies the menu as a tom-off submenu. (Any submenus that were attached to the tom-off submenu move with it and remain attached.)  
#### main menu  
![](images/_page_115_Picture_8.jpeg)  
![](images/_page_115_Picture_9.jpeg)  
The idea is for users to bring up a submenu, then tear it off and move it to a desired location if they want it to stay on-screen. Once a submenu has been tom away from its supermenu, it stays where the user puts it. To reattach the submenu, the user must close it and then choose its controlling command.  
If the user presses the mouse button while the cursor is over the command that controls the tom-off submenu, a copy of the submenu temporarily appears next to its supermenu.  
![](images/_page_116_Picture_2.jpeg)  
![](images/_page_116_Picture_3.jpeg)  
#### **Removing a Submenu from the Screen**  
Assuming its application is active, an attached submenu can be removed from the screen in three ways:  
- By again choosing its controlling command. Choosing the Librarian command in the detached Services menu in the previous figure causes the Librarian submenu to disappear.
- By choosing any other command in the supermenu.
- By removing its supermenu from the screen. For example, when a tom-off supermenu is closed, its attached submenu disappears from the screen.  
A tom-off submenu is removed from the screen by clicking its close button.