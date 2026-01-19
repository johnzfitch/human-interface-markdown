<!-- Chunk 223 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 679 -->
<span id="page-174-2"></span>When a user presses and holds the mouse button on your application's tile in the Dock, a menu appears. The menu lists the application's open windows and contains the Show In Finder, Hide, and Quit commands. The Show In Finder command displays a Finder window for the folder containing your application. The Hide and Quit commands function as documented in "The [Application](#page-161-0) [Menu"](#page-161-0) (page 162). If the user presses the Option key, Hide changes to Hide Others and Quit changes to Force Quit. If the tile has not been permanently added to the Dock, the command Keep In Dock also appears.  
<span id="page-174-1"></span>**Figure 12-25** The iTunes Dock menu  
![](images/_page_174_Picture_5.jpeg)  
You can customize your application's Dock menu by adding to the default items provided by the Dock. These additional items appear in the Dock menu only when the application is open. Potential additional items include:  
- Common commands to initiate actions in your application when it is not frontmost
- Commands that are applicable when there is no open document window
- Status and informational text  
For example, a mail application could provide commands to initiate a new message or to check for new messages.  
#### **C HAPTER 1 2**  
Menus  
Any command you add to the Dock menu should also be available in your application's pull-down menus. Application-specific items appear above the standard Dock menu items.  
<span id="page-175-0"></span>**Carbon:** See *Customizing Your Application Dock Tile* in Carbon User Experience Documentation. **Cocoa:** See NSApplication reference documentation for information on customizing the Dock menu.  
<span id="page-176-2"></span><span id="page-176-0"></span>Windows provide a frame for viewing and interacting with applications and data.  
From a developer's perspective, there are many types of windows in Mac OS X. Although a user might see them all as windows, the distinctions in behavior (layering, zooming, minimizing) and appearance (presence or absence of title bars) among the various types of windows contribute to the Macintosh user experience. It is important that you understand the different types of windows available, general window behavior, and behavior specific to each type of window.  
This chapter first introduces the different types of windows and then focuses on the appearance and behavior of document, application, and utilitywindows. Dialogs and alertwindows are unique types of windows with guidelines in addition to those for standard windows. They are discussed in detail in ["Dialogs"](#page-206-1) (page 207). Note that unless explicitly stated, dialogs should behave like windows.