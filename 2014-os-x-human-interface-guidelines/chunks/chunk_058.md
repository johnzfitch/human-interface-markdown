<!-- Chunk 58 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 444 -->
A **dynamic menu item** is a command that changes when the user presses a modifier key. For example, when the user opens the Window menu in the Finder and then presses the Option key, the Minimize and Zoom menu items change.  
![](images/_page_78_Figure_4.jpeg)  
![](images/_page_78_Picture_5.jpeg)  
![](images/_page_78_Picture_7.jpeg)  
**API Note:** To define dynamic menu items in code, you can use the setAlternate: method of NSMenuItem to designate one menu item as the alternate of another.  
Follow these guidelines if you decide to use dynamic menu items in your app.  
**Avoid making a dynamic menu item the only way to accomplish a task.** Dynamic menu items are hidden by default, so they're an appropriate way to offer a shortcut to sophisticated users. In all cases, don't make users discover a dynamic menu item before they can use your app effectively. For example, a user who hasn't discovered the Minimize All dynamic menu item in the Finder Window menu (shown above) can still minimize all open Finder windows by minimizing each one individually.  
Although you can enable dynamic menu items in a contextual or Dock menu, these items can be doubly hard for users to discover. As with app menus, make sure that the functionality of the contextual or Dock menu does not depend on the discovery of dynamic menu items.  
**Require only a single modifier key to reveal the dynamic menu items in a menu.** Users are apt to find it physically awkward to press more than one key while simultaneously opening and choosing a menu item. Also, requiring more than one additional key press greatly decreases the user's chances of discovering the dynamic menu items.  
**Note:** OS X automatically sizes the menu to hold the widest item, including Option-enabled commands.