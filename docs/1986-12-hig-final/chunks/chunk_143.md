<!-- Chunk 143 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 689 -->
By: Katie Withey Date: 31 March 87  
This information will be in the final versions of Inside Macintosh, vol. V and Human Interface Guidelines: the Apple Desktop Interface (to be published by Addison Wesley)  
Hierarchical menus are a logical extension of the current menu metaphor: another dimension is added to a menu, so that a menu item can be the title of a submenu. When the user drags the pointer through a hierarchical menu item, a submenu appears after a brief delay.  
Hierarchical menu items have an indicator (a small black triangle pointing to the right, to indicate "more") at the edge of the menu, as illustrated in Figure 1.  
![](images/_page_162_Figure_7.jpeg)  
Figure 1. Main menu before and after submenu appears  
One main menu can contain both standard menu items and submenus; both levels can have Command-key equivalents. (The submenu title can't have a Command-key equivalent, of course, because it's not a command. Key combinations aren't used to pull down menus.)  
Two delay values enable submenus to function smoothly, without jarring distractions to the user: The submenu delay is the length of time before a submenu appears as the user drags the pointer through a hierarchical menu item. It prevents flashing from rapid appearance-disappearance of submenus. The drag delay allows the user to drag diagonally from the submenu title into the submenu, briefly crossing part of the main menu, without the submenu disappearing (which would ordinarily happen when the pointer was dragged into another main menu item). See Figure 2.  
![](images/_page_163_Figure_2.jpeg)  
Figure 2. Dragging diagonally to a submenu item  
Other aspects of submenus—menu blink, etc.—behave exactly the same way as in standard menus.  
The original Macintosh menus were designed so that the user could drag the mouse across the menu bar and immediately see all of the choices currently available. Although developers have found they need more menu space, and hierarchical menus were designed to meet that need, it's important that this original capability be maintained as much as possible. To keep this essential simplicity and clarity, follow these guidelines:  
- Hierarchical menus should be used only for lists of related items, such as fonts or font sizes (in this case, the title of the submenu clearly tells what the submenu contains).
- Only one level of hierarchical menu should be used, although the capability for more is provided. This one extra layer of menus potentially  
increases by an order of magnitude the number of menu items that can be used; if you need more layers than that, your application is probably more complex than most users can understand, and you should rethink your design.  
![](images/_page_165_Picture_0.jpeg)