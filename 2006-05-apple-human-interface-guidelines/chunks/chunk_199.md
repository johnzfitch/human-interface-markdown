<!-- Chunk 199 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 806 -->
When people use menus, they usually make a selection within their data and then choose a menu item. This behavior follows the see-and-point paradigm of identifying what needs to be acted on and then specifying the action by choosing a menu item. To choose an item in a menu, the user positions the pointer on the menu title and drags to the desired item. Each item is highlighted as it is selected.  
Menu Behavior **149**  
No action happens until the user releases the mouse button with the cursor over a menu item. (See "The Mouse and Other Pointing [Devices"](#page-88-1) (page 89).) People can move the pointer off a menu before releasing the mouse button without initiating any action. They can open and scan menus to find out what features are availablewithout havingto actually perform an action. When a menu item has been activated, it blinks briefly.  
A user can also open a menu with a click. The menu stays open without the user having to continue holding down the mouse button. The user can then move the pointer to an item to select it or can move the pointer anywhere on the screen without losing sight of the menu. Once a menu is opened, it remains open until another action forces it to close. Such actions include:  
- Choosing a command from the menu
- Moving the pointer to another menu title
- A click outside the menu
- A system-initiated alert
- <span id="page-149-1"></span>■ A system-initiated application switch or quit  
Even if all of the items in a menu or submenu are unavailable, the menu or submenu title is not dimmed. The user can still open the menu, but all of its items are dimmed to indicate that these items are not available in the present context. [Figure](#page-160-1) 12-13 (page 161) shows a menu with unavailable menu items in the open and closed state.  
As a general rule, avoid creating long menus. Long menus are difficult for the user to scan and can be overwhelming. If you find that there are too many items in a single menu, try regrouping them; you may find that some of the items fit more naturally in other menus.  
<span id="page-149-0"></span>If a menu contains more items than are visible onscreen, the menu can scroll to allow the user access to all of the menu items. A **scrolling menu** is shown in Figure 12-2.  
**Figure 12-2** Scrolling menu  
![](images/_page_149_Picture_13.jpeg)  
A downward-pointing indicator at the bottom of the scrolling menu indicates that there are more items. When the user starts to scroll down, an upward-pointing indicator appears at the top of the menu to show that some items are no longer visible in that direction. When the user drags past the last visible item, the menu scrolls to show the additional items. When the last item is shown, the downward-pointing indicator disappears.  
If the user drags back up to the top, the menu scrolls back down in the same manner. The next time the menu is opened, it appears in its original state (with the indicator at the bottom).  
Do not design your application to intentionally include scrolling menus; they should exist only when a user adds many items to a customizable menu or when the menu's function causes it to have items added to it (for example, the Finder's Window menu).