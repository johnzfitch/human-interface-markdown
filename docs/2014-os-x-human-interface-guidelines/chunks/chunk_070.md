<!-- Chunk 70 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 1341 -->
The **Window menu** contains commands for organizing and managing an app's windows.  
Other than Minimize and Zoom (discussed below), the Window menu does not contain commands that affect the way a user views a window's contents. The View menu (described in The View [Menu](#page-98-0) (page 99)) contains all commands that adjust how a user views a window's contents.  
![](images/_page_100_Picture_2.jpeg)  
The Window menu includes the following standard items, listed in the order in which they should appear.  
| Menu item                   | Expected | Keyboard shortcut<br>Meaning |                                                                                                                                                                                                                                                                                                                                |
|-----------------------------|----------|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Minimize                    | Yes      | Command-M                    | Minimizes<br>the<br>active<br>window<br>to<br>the<br>Dock.                                                                                                                                                                                                                                                                     |
| Minimize<br>All             | No       | Option-Command-M             | Minimizes<br>all<br>the<br>windows<br>of<br>the<br>active<br>app<br>to<br>the<br>Dock.                                                                                                                                                                                                                                         |
| Zoom                        | Yes      |                              | Toggles<br>between<br>a<br>predefined<br>size<br>appropriate<br>to<br>the<br>window's<br>content<br>and<br>the<br>window<br>size<br>the<br>user<br>has<br>set.                                                                                                                                                                 |
| Bring<br>All<br>to<br>Front | No       |                              | Brings<br>forward<br>all<br>of<br>an<br>app's<br>open<br>windows,<br>maintaining<br>their<br>onscreen<br>location,<br>size,<br>and<br>layering<br>order.<br>(This<br>should<br>happen<br>when<br>the<br>user<br>clicks<br>the<br>app<br>icon<br>in<br>the<br>Dock.)                                                            |
|                             |          |                              | Note<br>that<br>this<br>item<br>can<br>be<br>an<br>Option-enabled<br>toggle<br>with<br>Arrange<br>in<br>Front.                                                                                                                                                                                                                 |
| Arrange<br>in<br>Front      | No       |                              | Bringsforward<br>all<br>of<br>the<br>app's<br>windowsin<br>their<br>current<br>layering<br>order<br>and<br>changes<br>their<br>location<br>and<br>size<br>so<br>that<br>they<br>are<br>neatly<br>tiled.<br>Note<br>that<br>this<br>item<br>can<br>be<br>an<br>Option-enabled<br>toggle<br>with<br>Bring<br>All<br>to<br>Front. |  
**Note:** When you enable users to take windows full screen, you add the Enter Full Screen menu item to the View menu. If you don't include a View menu, add the Enter Full Screen menu item to the Window menu instead, placing it after the app-specific commands and before the Bring All to Front menu item.  
The following guidelines help you provide a Window menu that helps users organize windows in your app.  
**List open windows appropriately.** The Window menu should list your app's open windows(including minimized windows) in the order in which they were opened, with the most recently opened window first. If a document contains unsaved changes, a dot can appear next to its name.  
**Avoid listing open panels in the Window menu.** You can, however, add a command to the Window menu to show or hide panels in your app. (For more information about panels, see [Panels](#page-144-0) (page 145).)  
**Include a Window menu for the Minimize and Zoom commands.** Even if your app consists of only one window, you should provide the Minimize and Zoom commands so that people using full keyboard access can implement these functions with the keyboard.  
**Use the correct order for items in the Window menu.** Specifically, items should appear in this order:  
Minimize  
Zoom  
A separator  
App-specific window commands  
A separator  
Bring All to Front (optional)  
A separator  
A list of open windows  
Note that the Close command should appear in the File menu, below the Open command (see [The](#page-89-0) File [Menu](#page-89-0) (page 90)).  
**Avoid using Zoom to expand the window to the full screen size.** Users expect Zoom to toggle the window between two useful sizes.