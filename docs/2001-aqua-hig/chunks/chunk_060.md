<!-- Chunk 60 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 416 -->
The **menu bar** extends across the top of the main screen and contains pull-down menus. The menu bar  
- is always visible and available, except in circumstances such as a slide show (see discussion below)
- always has the Apple menu (provided by the operating system), the application menu containing items that apply to the active application as a whole, a File menu, and a Window menu
- can also contain Edit and Help menus, as well as application-specific menus  
<span id="page-50-2"></span>**Figure 4-6** The menu bar displayed when the Finder is active  
![](images/_page_50_Figure_16.jpeg)  
If there is insufficient room to display all of an application's menus, the menu bar status items are omitted. If there is still insufficient room to display all menus, the application's menus may be omitted, starting with the rightmost menu.  
If your application can display full-screen images (such as slide shows), you may allow users to hide the menu bar. If you implement this feature, provide a clearly visible way, such as a button, for the user to make the menu bar reappear. If there is no button visible, pressing the Escape key or moving the mouse to the top of the screen should display the menu bar.  
<span id="page-51-4"></span><span id="page-51-3"></span>If *all* of a menu's commands are unavailable (dimmed) at the same time, dim the menu title. (The Menu Manager in Carbon does this automatically if you set the kMenuAttrAutoDisable attribute.) Users should still be able to open a dimmed menu to see its contents.  
For information about keyboard equivalents for pull-down menu commands, see ["Keyboard Equivalents" \(page 172\)](#page-171-0).