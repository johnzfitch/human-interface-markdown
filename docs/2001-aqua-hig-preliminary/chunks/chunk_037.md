<!-- Chunk 37 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 343 -->
The **menu bar** extends across the top of the main screen and contains pull-down menus. The menu bar  
- is always visible and available, except in circumstances such as a slide show (see discussion below)
- always has the Apple menu (provided by the operating system), an application menu containing items that apply to the whole application, a File menu, and a Window menu
- can also contain Edit and Help menus, as well as application-specific menus  
<span id="page-40-2"></span>**Figure 4-6** The menu bar displayed when the Finder is active  
![](images/_page_40_Picture_3.jpeg)  
If there is insufficient room to display all of an application's menus, menus are omitted, starting with the rightmost menu.  
If your application can display full-screen images (such as slide shows), you may allow users to hide the menu bar. If you implement this feature, provide a clearly visible way, such as a button, for the user to make the menu bar reappear. If there is no button visible, pressing the Escape key or Command-Q should display the menu bar.  
If *all* of a menu's commands are unavailable (dimmed) at the same time, dim the menu title. The Menu Manager in Carbon does this automatically if you set the kMenuAttrAutoDisable attribute.  
For information about keyboard equivalents for pull-down menu commands, see ["Keyboard Equivalents" \(page 138\)](#page-137-0).