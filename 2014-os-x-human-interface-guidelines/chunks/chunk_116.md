<!-- Chunk 116 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 937 -->
A **pop-up menu** presents a list of mutually exclusive choices in a dialog or window.  
![](images/_page_189_Picture_3.jpeg)  
**Important:** The pop-up menu described here is suitable for use in the window-body only. If you need to provide pop-up menu functionality in a window-frame area,see Some [Controls](#page-176-1) Can Be Used on the Window [Frame](#page-176-1) (page 177).  
**API Note:** To define a pop-up menu in your code, use the NSPopUpButton class.  
#### A pop-up menu:  
- Has a double-arrow indicator
- Contains nouns (things) or adjectives (states or attributes), but not verbs (commands)
- Displays a checkmark to the left of the currently selected value when open  
You can see most of these components in the Highlight color pop-up menu in General preferences (the double-arrow indicator isn't completely visible because the menu is open).  
![](images/_page_189_Picture_11.jpeg)  
A pop-up menu behaves like other menus: Users press to open the menu and then drag to choose an item. The chosen item flashes briefly and is displayed in the closed pop-up menu. If users move the pointer outside the open menu without releasing the mouse button, the current value remains active. An exploratory press in the menu to see what's available doesn't select a new value.  
Use a pop-up menu to present up to 12 mutually exclusive choices that users don't need to see all the time.  
**Consider using a pop-up menu as an alternative to other types of selection controls.** For example, if you have a dialog that contains a set ofsix or more radio buttons, you might consider replacing them with a pop-up menu to save space.  
**Use a pop-up menu to provide a menu of things or states.** If you need to provide a menu of commands (that is, verbs), use a pull-down menu instead. Use title-style capitalization for the label of each item in a pop-up menu. To learn more about menus, see About [Menus](#page-70-0) (page 71).  
**In general, provide an introductory label to the left of the pop-up menu (in left-to-right scripts).** The label should have sentence-style capitalization For more information on this capitalization style, see Use the [Right](#page-46-0) [Capitalization](#page-46-0) Style in Labels and Text (page 47).  
**Avoid adding a submenu to an item in a pop-up menu.** A submenu tends to hide choices too deeply and can be physically difficult for users to use.  
**Avoid using a pop-up menu to display a variable number of items.** Because users must open a pop-up menu to see its contents, they should be able to rely on the contents remaining the same.  
**Consider using a scrolling list, instead of a pop-up menu, for a large number of items.** If space is not restricted, use a scrolling list to display more than 12 items.  
**Don't use a pop-up menu when more than one simultaneous selection is appropriate.** For example, a list of text styles, from which users might choose both bold and italic, should not be displayed in a pop-up menu. In this situation, you should instead use checkboxes or a pull-down menu in which checkmarks appear.  
**In rare cases, include a command that affects the contents of the pop-up menu itself.** For example, in the Print dialog, the Printer pop-up menu contains the Add Printer item, which allows users to add a printer to the menu. If users add a new printer, it becomes the menu's default selection. If you need to add such commands to a pop-up menu, put them at the bottom of the menu, below a separator. (A separator—called a Separator Menu Item in Interface Builder—is a horizontal line.)  
**Ensure that all pop-up menus in a stack have the same width.** Even if the visible contents of each pop-up menu varies, the width of the controls themselves should be equal.