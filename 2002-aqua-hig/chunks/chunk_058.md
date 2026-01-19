<!-- Chunk 58 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 485 -->
<span id="page-51-3"></span>The **menu bar** extends across the top of the main screen and contains pull-down menus. The menu bar  
- is always visible and available, except in circumstances such as a slide show (see discussion below)
- always has the Apple menu (provided by the operating system), the application menu containing items that apply to the active application as a whole, and a Window menu
- <span id="page-51-1"></span>■ can also contain File, Edit, and Help menus, as well as application-specific menus  
**Figure 4-5** The menu bar displayed when the Finder is active  
![](images/_page_51_Picture_8.jpeg)  
If there is insufficient room to display all of an application's menus, the menu bar status items are omitted. If there is still insufficient room to display all menus, the application's menus may be omitted, starting with the rightmost menu.  
If your application can display full-screen images (such as slide shows), you may allow users to hide the menu bar. If you implement this feature, provide a clearly visible way, such as a button, for the user to make the menu bar reappear. If there is no button visible, pressing the Escape key or moving the mouse to the top of the screen should display the menu bar.  
<span id="page-51-4"></span><span id="page-51-2"></span>If *all* of a menu's commands are unavailable (dimmed) at the same time, dim the menu title. (The Menu Manager in Carbon does this automatically if you set the kMenuAttrAutoDisable attribute.) Users should still be able to open a dimmed menu to see its contents.  
For information about keyboard equivalents for pull-down menu commands, see ["Reserved and Recommended Keyboard Equivalents" \(page 176\).](#page-175-0)  
The order in which menus and their contents appear is under developer control; your application should reflect the guidelines discussed in the following sections, which describe the standard pull-down menus in the menu bar.