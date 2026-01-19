<!-- Chunk 79 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 734 -->
When people use menus, they usually make a selection within their data and then choose a menu item. This behavior follows the see-and-point paradigm of identifying what needs to be acted on and then specifying the action by choosing a menu item. To choose an item in a menu, the  
Menu Behavior **75**  
user positions the pointer on the menu title and drags to the desired item. Each item is highlighted as it is selected. No action happens until the user releases the mouse button with the cursor over a menu item. (See ["The Mouse and Other Pointing Devices"](#page-18-1) (page 19).) People can move the pointer off a menu before releasing the mouse button without initiating any action. They can open and scan menus to find out what features are available without having to actually perform an action. When a menu item has been activated, it blinks briefly.  
A user can also open a menu with a click. The menu stays open without the user having to continue holding down the mouse button. The user can then move the pointer to an item to select it or can move the pointer anywhere on the screen without losing sight of the menu. Once a menu is opened, it remains open until another action forces it to close. Such actions include:  
- Choosing a command from the menu
- Moving the pointer to another menu title
- A click outside the menu
- <span id="page-75-1"></span>■ A system-initiated alert
- A system-initiated application switch or quit  
<span id="page-75-2"></span>If all of the items in a menu or submenu are unavailable, the menu title is dimmed. The user can still open the menu, but all of its items are dimmed to indicate that these items are not available in the present context. [Figure 7-13](#page-85-2) (page 86) shows a dimmed menu in the open and closed state.  
<span id="page-75-0"></span>If a menu contains more items than are visible onscreen, the menu can scroll to allow the user access to all of the menu items. A **scrolling menu** is shown in Figure 7-2.  
**Figure 7-2** Scrolling menu  
![](images/_page_75_Picture_12.jpeg)  
A downward-pointing indicator at the bottom of the scrolling menu indicates that there are more items. When the user starts to scroll down, an upward-pointing indicator appears at the top of the menu to show that some items are no longer visible in that direction. When the user drags past the last visible item, the menu scrolls to show the additional items. When the last item is shown, the downward-pointing indicator disappears.  
If the user drags back up to the top, the menu scrolls back down in the same manner. The next time the menu is opened, it appears in its original state (with the indicator at the bottom).  
Do not design your application to intentionally include scrolling menus; they should exist only when a user adds many items to a customizable menu or when the menu's function causes it to have items added to it (for example, the Finder's Window menu).