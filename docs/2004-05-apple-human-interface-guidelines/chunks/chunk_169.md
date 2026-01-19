<!-- Chunk 169 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 517 -->
A **command pop-down menu** is similar to a pull-down menu, but it appears within a window rather than in the menu bar. Use this control only when the window is shared among multiple applications and the menu contains commands that affect the window's contents. For example, the Colors window, which can be used in any application, contains a menu with commands that can be used to change the contents of the Colors window itself. If your application uses the Colors window, don't create your own menu with these same commands.  
<span id="page-174-1"></span>**Figure 10-23** A command pop-down menu  
![](images/_page_174_Picture_9.jpeg)  
Command pop-down menus should contain between 3 and 12 commands. A closed command menu always displays the same text, which acts as the menu title.  
**Carbon:** Mimic the appearance and behavior with a bevel button.  
**Cocoa:** Use the NSPopUpButton widget in Interface Builder and change its type to PullDown.  
#### Command Pop-Down Menu Specifications  
Note that the specifications for command pop-down menus are the same as those for pop-up menus.  
Selection Controls **175**  
<span id="page-175-0"></span>**Figure 10-24** Command pop-down menu dimensions  
#### **Fu -s ze pop-down menu**  
![](images/_page_175_Picture_4.jpeg)  
#### **Sma pop-down menu**  
![](images/_page_175_Picture_6.jpeg)  
#### **M n pop-down menu**  
![](images/_page_175_Picture_8.jpeg)  
#### ■ **Height:**  
❏ Full size: 20 pixels  
❏ Small: 17 pixels  
❏ Mini: 15 pixels  
■ **Width:** Wide enough to accommodate the longest menu item  
#### ■ **Spacing:**  
- ❏ Full size: Leave at least 12 pixels of space between stacked controls.
- ❏ Small: Leave at least 10 pixels.
- ❏ Mini: Leave at least 8 pixels.  
#### ■ **Menu item text:**  
- ❏ Full size: System font, 9 pixels from left edge and at least 9 pixels from the triangle section
- ❏ Small: Small system font, 7 pixels from left edge and at least 7 pixels from the triangle section
- ❏ Mini: Mini system font, 5 pixels from left edge and at least 5 pixels from the triangle section