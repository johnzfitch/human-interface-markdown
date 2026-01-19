<!-- Chunk 273 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 653 -->
<span id="page-305-2"></span>A **command pop-down menu** is similar to a pull-down menu, but it appears within a window rather than in the menu bar. A command pop-down menu presents a list of commands that affect the containing window's contents. For example, the Colors window (shown in Figure 15-45) contains a menu with commands that can be used to change the contents of the Colors window itself. (If your application uses the Colors window, don't create your own menu with these same commands; see "Fonts Window and Colors [Window"](#page-236-0) (page 237) for more information on the Colors window.)  
**Figure 15-45** A command pop-down menu in the Colors window  
![](images/_page_305_Picture_9.jpeg)  
#### Command Pop-Down Menu Usage  
Use a command pop-down menu only when the containing window is shared among multiple windows or applications and the menu contains commands that affect the window's contents. For example, the Colors window (shown in Figure 15-45) can be used in any application. The items in its command pop-down menu allowusers to make newpalettes of colors available in the Colorswindow (the open command pop-down menu in the Colors window is shown in Figure 15-46).  
<span id="page-306-0"></span>**Figure 15-46** An open command pop-down menu  
![](images/_page_306_Picture_5.jpeg)  
Command pop-down menus should contain between 3 and 12 commands. The items in a command pop-down menu do not have to be mutually exclusive.  
#### Command Pop-Down Menu Contents and Labeling  
Command pop-down menus do not require an introductory label. A closed command pop-down menu always displays the same text,which acts as the menu title. This is in contrast to a closed pop-up menu, which displays the currently selected item.  
Command pop-down menus contain a single, downward-pointing arrow and may display check marks to the left of all currently active selections.  
#### <span id="page-306-1"></span>Command Pop-Down Menu Specifications  
The specifications for command pop-down menus are the same as those for pop-up menus; see "Pop-Up Menu [Specifications"](#page-293-1) (page 294) for the appropriate metrics. Figure 15-47 shows how the command pop-down menu text is positioned.  
**Figure 15-47** A command pop-down menu  
![](images/_page_306_Picture_13.jpeg)  
#### Command Pop-Down Implementation  
You can use Interface Builder to create a command pop-down menu: select an NSPopUpButton object and change its type to Pull Down in the Attributes pane of the inspector. To create a command pop-down menu using Application Kit programming interfaces, use the NSPopUpButton class.