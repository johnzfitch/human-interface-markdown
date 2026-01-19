<!-- Chunk 9 | Source: 1996 Human Interface Guidelines for Mac OS 8 (WWDC Release).pdf | Est. Tokens: 2240 -->
This section describes changes to the standard menus previously available. The Mac OS 8 Toolbox includes support for tear-off menus with a new appearance, grid menus, flippy menus, and extended keyboard navigation in menus. This section also contains some general information about menus.  
#### Tear-Off Menus 0  
The Mac OS 8 Toolbox provides support for tear-off menus. For information about the contents and behavior of tear-off menus, see *Macintosh Human Interface Guidelines*, pages 92-95. In Mac OS 8, tear-off menus have an indicator between the top of the menu and the menu bar to visually alert the user that the menu can tear off, as shown in [Figure 21](#page-23-0).  
Menus **23**  
<span id="page-23-0"></span>**Figure 21** A tear-off menu  
![](images/_page_23_Picture_2.jpeg)  
When a menu is torn off, it has the appearance of a utility window [\(page 9\)](#page-8-0).  
#### Grid Menus 0  
Grid menus provide support for palette-type features in the menu bar. Grid menus can contain choices such as tools or colors, as shown in Figure 22. Grid menus can be in the menu bar, pop-up from a tool palette as a hierarchical menu, or pop-up from a pop-up button in a dialog box.  
**Figure 22** A grid menu  
![](images/_page_23_Picture_7.jpeg)  
Most grid menus are good candidates to be tear-off menus. (See ["Tear-Off](#page-22-0)  [Menus"](#page-22-0) for more information.) The size of the grid is limited by the placement of the palette when the menu is torn off of the menu bar. Long, narrow menus make better use of screen space when in palette state. Also consider where the user will put the menu when it's torn off. Generally palettes end up near the edge of the screen.  
<span id="page-24-0"></span>Each theme dictates what the bevel that separates cells looks like. The bevel itself is three pixels wide. You should create cells of at least 8 pixels by 8 pixels in order to provide a target that users can easily locate and click. For cells that contain icons, the minimum size should be 18 pixels by 18 pixels so that you can include a 16-pixel by 16-pixel icon plus a one pixel space on each side of the icon to allow a visual affordance. (To create icons for these menus, follow the icon design guidelines in *Macintosh Human Interface Guidelines*.)  
Each cell has three states; available, selected, and active. The available state has no emphasis. The selected state shows a selected mechanism for the cell over which the user has the pointer with the mouse button pressed. The checked state indicates the cell currently in effect (if any). Figure 23 shows the states of cells that contain two different types of content.  
**Figure 23** State changes of cells  
![](images/_page_24_Figure_4.jpeg)  
Menus **25**  
<span id="page-25-0"></span>The state changes and mouse tracking are all handled by the Mac OS 8 Toolbox. Figure 24 shows each of the states of a cell in a menu.  
**Figure 24** States of grid menu cells  
![](images/_page_25_Picture_3.jpeg)  
To create a grid menu, you specify the width and height of the menu, the size of the cells, each cell's content, and if the menu tears off. For more information on implementing grid menus, see the "Introduction to the Mac OS 8 Toolbox" chapter in the document *Human Interface Toolbox*.  
You can implement features such as colors, patterns, or tools in a grid menu or using icon buttons in a toolbar. Grid menus have the tracking behavior of menus and change the current choice when the user releases the mouse button. This behavior is more flexible than icon buttons (the user must press and release the mouse button without moving the mouse). However, you can't include other controls or behaviors for the items, such as checkboxes, in a grid menu.  
With bevel buttons you can implement checkbox behavior. Also, bevel buttons in a toolbar provide better visual feedback than a grid menu since the bevel button appearance shows which elements are active, while a grid menu must be open or torn off to show its status. You can implement a toolbar of bevel buttons in a utility window.  
#### <span id="page-26-0"></span>Flippy Menus 0  
Flippy menus allow you to include extensions to existing menu commands that appear when the user presses the option key before opening the menu. You should only include modifications to existing commands, not entirely different commands. An example of an alternate command is Close and Close All, as shown in Figure 25. For the alternate version of a command, show the keyboard equivalent Command–Option–*key*.  
**Figure 25** A flippy menu  
| File  |            |
|-------|------------|
| New   | <b></b> ₩N |
| Open  | жо         |
| Close | ₩W         |
| Save  | <b>%</b> 5 |
| Print | ЖΡ         |
| Quit  | жQ         |  
![](images/_page_26_Picture_6.jpeg)  
**Pull-down menu Pull-down menu with option key pressed**  
The user can tear off the version of the menu that is currently open.The user can't flip a torn-off menu to display the alternate commands. However, the user can still open the version in the menu bar to show these commands. You need to provide support for the flipping and do the menu tracking while the menu is open.  
When you create a flippy menu, set the menu width to the length of the longest string so that the menu doesn't change width when the user opens the alternate version of it. You can provide support for allowing the user to flip the menu while it is open. This behavior allows the most flexibility for the user.  
Changed items have no distinct visual appearance. Don't change every item in a menu. Only change those items that require a modification and those that  
Menus **27**  
<span id="page-27-0"></span>make sense. Flippy menus are not a means of providing additional space for menu commands. If you have flippy menus in your application, don't use the Option key in other keyboard equivalents because that changes the meaning of the Option key. If the Option key already functions in a specific way with your menus, don't use it to also flip menu commands. Its meaning should be consistent within an application. If a modifier key is used to alter the behavior of push buttons in dialog boxes, make sure that there is a consistent behavior for each modifier key.  
#### Custom Menu Layouts 0  
You can combine different types of menus in one menu using the custom menu layout. This design provides the ability to combine menus with different grids into one menu as shown in Figure 26. A separator distinguishes the choices in each area of the menu, just as a separator distinguishes groups of textual menu commands.  
**Figure 26** Custom menu layout  
![](images/_page_27_Picture_5.jpeg)  
You can use a custom menu layout to create a menu that doesn't use standard commands. For example, you could create a keypad menu using a custom layout. Another use for a custom layout might be to implement a compass  
<span id="page-28-0"></span>menu where a user could choose a direction by clicking the appropriate direction rather than choosing a text command that represented the direction.  
You should only use a custom menu layout when it's essential rather than just for effect. Don't use a custom menu layout when a standard menu works.  
#### Pop-Up Menus 0  
Pop-up menus have a new appearance and new behavior in Mac OS 8. They are now provided by the Mac OS 8 Toolbox. The menu and the arrow are now one control that have the button appearance when closed. The menu always descends from the button regardless of its location on the screen. Figure 27 shows the new pop-up menu appearance.  
**Figure 27** Pop-up menu  
![](images/_page_28_Picture_6.jpeg)  
#### Menu Titles 0  
The menu bar extends across the top of the screen and contains words and icons that serve as the title of each menu. It should be visible and always available to use. Nothing should ever appear on top of the menu bar or obscure it from view. The menu bar should always contain the standard menus—the Apple menu, the File menu, (or the Document menu in OpenDoc), the Edit menu, the Help menu, and the Application menu. The Keyboard menu is an optional standard menu that appears when the user installs a script system other than the Roman Script System. The titles of the standard menus never change.  
The titles of the Apple, Keyboard, and Application menus are icons rather than words. Other menus should have words as titles since most users don't recognize an icon in the menu bar as a menu title.  
Menus **29**  
#### <span id="page-29-0"></span>Icons in Menus 0  
In Mac OS 8 you can include icons in menus where they help to clarify the meaning of a menu item. For example, you could include icons with the menu items for alignment in a text menu, as shown in Figure 28.  
**Figure 28** Icons in menus  
![](images/_page_29_Picture_4.jpeg)  
It may also help to show an icon in a menu item that represents a more complex feature such as rotating to indicate the direction of the movement.