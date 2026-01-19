<!-- Chunk 112 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 2077 -->
You can add your own app-specific menus as appropriate. These menus should be between the View menu and the Window menu. For example, the Safari-specific History and Bookmarks menus appear between the View and Window menus.  
![](images/_page_158_Picture_6.jpeg)  
#### <span id="page-158-1"></span>The Window Menu  
The **Window menu** contains commands for organizing and managing an app's windows.  
Other than Minimize and Zoom (discussed below), the Window menu does not contain commands that affect the way a user views a window's contents. The View menu (described in "The View [Menu"](#page-157-0) (page 158)) contains all commands that adjust how a user views a window's contents.  
![](images/_page_158_Picture_10.jpeg)  
The Window menu includes the following standard items, listed in the order in which they should appear:  
| Menu item | Expected | Keyboard shortcut | Meaning                                                    |  |
|-----------|----------|-------------------|------------------------------------------------------------|--|
| Minimize  | Yes      | Command-M         | Minimizes<br>the<br>active<br>window<br>to<br>the<br>Dock. |  |  
| Menu item                   | Expected | Keyboard shortcut | Meaning                                                                                                                                                                                                                                                                                                                                                                               |
|-----------------------------|----------|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Minimize<br>All             | No       | Command-Option-M  | Minimizes<br>all<br>the<br>windows<br>of<br>the<br>active<br>app<br>to<br>the<br>Dock.                                                                                                                                                                                                                                                                                                |
| Zoom                        | Yes      |                   | Toggles<br>between<br>a<br>predefined<br>size<br>appropriate<br>to<br>the<br>window's<br>content<br>and<br>the<br>window<br>size<br>the<br>user<br>has<br>set.                                                                                                                                                                                                                        |
| Bring<br>All<br>to<br>Front | No       |                   | Brings<br>forward<br>all<br>of<br>an<br>app's<br>open<br>windows,<br>maintaining<br>their<br>onscreen<br>location,<br>size,<br>and<br>layering<br>order.<br>(This<br>should<br>happen<br>when<br>the<br>user<br>clicks<br>the<br>app<br>icon<br>in<br>the<br>Dock.)<br>Note<br>that<br>this<br>item<br>can<br>be<br>an<br>Option-enabled<br>toggle<br>with<br>Arrange<br>in<br>Front. |
| Arrange<br>in<br>Front      | No       |                   | Bringsforward<br>all<br>of<br>the<br>app's<br>windowsin<br>their<br>current<br>layering<br>order<br>and<br>changes<br>their<br>location<br>and<br>size<br>so<br>that<br>they<br>are<br>neatly<br>tiled.<br>Note<br>that<br>this<br>item<br>can<br>be<br>an<br>Option-enabled<br>toggle<br>with<br>Bring<br>All<br>to<br>Front.                                                        |  
**Note:** When you use the programming interfaces to allows users to take windows full screen, you add the Enter Full Screen menu item to the View menu. If you do not include a View menu, you can add the Enter Full Screen menu item to the Window menu instead.  
The following guidelines help you provide a Window menu that helps users organize windows in your app.  
**List open windows appropriately.** The Window menu should list your app's open windows(including minimized windows) in the order in which they were opened, with the most recently opened window first. If a document contains unsaved changes, a dot can appear next to its name.  
**Avoid listing open panels in the Window menu.** You can, however, add a command to the Window menu to show or hide panels in your app. (For more information about panels, see ["Panels"](#page-208-0) (page 209).)  
**Include a Window menu for the Minimize and Zoom commands.** Even if your app consists of only one window, you should provide the Minimize and Zoom commands so that people using full keyboard access can implement these functions with the keyboard.  
**Use the correct order for items in the Window menu.** Specifically, items should appear in this order:  
Minimize  
Zoom  
A separator  
App-specific window commands  
Bring All to Front (optional)  
A separator  
A list of open windows  
Note that the Close command should appear in the File menu, below the Open command (see ["The](#page-148-0) File [Menu"](#page-148-0) (page 149)).  
**Avoid using Zoom to expand the window to the full screen size.** Users expect Zoom to toggle the window between two useful sizes. For more information about implementing zoom, see "Resizing and [Zooming](#page-199-0) [Windows"](#page-199-0) (page 200).  
#### <span id="page-160-0"></span>The Help Menu  
If your app provides onscreen help, the **Help menu** should be the rightmost menu of your app's menus.  
![](images/_page_160_Picture_10.jpeg)  
If you have registered your help book, the system provides the Spotlight For Help search field as the first item in the menu (for information on how to register your help book, see *Apple Help Programming Guide* ).  
The next menu item is *AppName* **Help**, which opens Help Viewer to the first page of your app's help book. For some guidelines on creating useful help content, see "User [Assistance"](#page-106-0) (page 107).  
**As much as possible, display only one custom item in the Help menu.** That is, it's best to display only the *AppName* Help item. If you do have more items, display them below this item. If you have additional items that are unrelated to help content, such as arbitrary website links, registration information, or release notes, link to these within your help book instead of listing them as separate items in the Help menu.  
**Avoid using the Help menu as a table of contents for your help book.** When users choose the *AppName* Help item, they can see the sections in your help book in the Help Viewer window. If you choose to provide additional links into your help content within the Help menu, be sure they are distinct.  
#### <span id="page-161-0"></span>Menu Bar Extras  
As described in "All Apps Use the [Single](#page-15-0) Menu Bar" (page 16), users decide to place menu bar extras in the menu bar. Typically, users decide to hide or show a menu bar extra by changing a setting in the appropriate preferences pane.  
If there is not enough room in the menu bar to display all menus, OS X automatically removes menu bar extras to make room for app menus, which take precedence. Similarly, if there are too many menu bar extras, OS X may remove some of them to avoid crowding app menus.  
**Don't rely on the presence of menu bar extras.** The system might change which menu bar extras are visible, and you can't be sure which menu bar extras users have chosen to show or hide.  
**Avoid creating a popover that emerges from a menu bar extra.** Popovers emerge from controls and specific window areas (for guidelines on how to use a popover in your app, see ["Popovers"](#page-204-0) (page 205)). A menu bar extra can open a menu, such as the Keyboard & Character Viewer menu.  
![](images/_page_161_Picture_6.jpeg)  
<span id="page-161-1"></span>**Consider alternatives to creating a menu bar extra.** For example, you can use the Dock menu functions to open a menu from your app's icon in the Dock. For some guidelines on how to create a Dock menu, see ["Designing](#page-165-0) a Dock Menu" (page 166).