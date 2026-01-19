<!-- Chunk 118 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 666 -->
<span id="page-95-7"></span><span id="page-95-6"></span>The **Window menu** contains commands for organizing and managing an application's windows. The menu should list an application's open document windows, including minimized windows, in the order in which they were opened, with the most recently opened document first. If a document contains unsaved changes, a bullet should appear next to its name.  
<span id="page-95-1"></span>**Figure 7-22** A Window menu  
![](images/_page_95_Picture_5.jpeg)  
Mac OS X does not automatically add utility windows to the list in the Window menu. You can add a command to the Window menu to show or hide utility windows in your application.  
The Minimize and Zoom commands are in the Window menu so that people using full keyboard access can implement these functions with the keyboard. Even if your application consists of only one window, include a Window menu for the Minimize and Zoom command.  
<span id="page-95-8"></span>Window menu items should appear in this order: Minimize, Zoom, separator, application-specific window commands, separator, Bring All to Front (optional), separator, list of open documents. The Close command should appear in the File menu, below the Open command.  
<span id="page-95-3"></span>**Carbon:** The Window menu is part of the default menu bar when you create a Carbon application in Interface Builder. To create one programmatically, use the function CreateStandardWindowMenu.  
<span id="page-95-4"></span>**Cocoa:** The Window menu is part of the default menu bar when you create a Cocoa application in Interface Builder.  
<span id="page-95-5"></span>**Minimize (Command-M).** Minimizes the active window to the Dock.  
**Minimize All (Command-Option-M).** Minimizes all the windows of the active application to the Dock.  
<span id="page-95-2"></span>**Zoom.** Toggles between a predefined size appropriate to the window's content and the window size the user has set. This command should *not* expand the window to the full screen size. See ["Resizing](#page-118-0) [and Zooming Windows"](#page-118-0) (page 119).  
**Bring All to Front.** Brings forward all of an application's open windows, maintaining their onscreen location, size, and layering order. This should happen whenever a user clicks the application icon in the Dock. See ["Window Layering"](#page-119-1) (page 120).  
You can make this command an Option-enabled toggle with Arrange in Front.  
<span id="page-96-6"></span><span id="page-96-3"></span>**Arrange in Front.** Brings forward all of the application's windows in their current layering order and changes their location and size so they are neatly tiled.