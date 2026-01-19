<!-- Chunk 328 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 238 -->
A **command pop-down menu** is similar to a pull-down menu, but it appears within a window rather than in the menu bar. Use this control only when the window is shared among multiple applications and the menu contains commands that affect the window's contents. For example, the Colors window, which can be used in any application, contains a menu with commands that can be used to change the contents of the Colors window itself. If your application uses the Colors window, don't create your own menu with these same commands.  
<span id="page-244-1"></span>**Figure 14-23** A command pop-down menu  
![](images/_page_244_Picture_8.jpeg)  
Command pop-down menus should contain between 3 and 12 commands. A closed command menu always displays the same text, which acts as the menu title.  
**Carbon:** Mimic the appearance and behavior with a bevel button.  
**Cocoa:** Use the NSPopUpButton widget in Interface Builder and change its type to PullDown.