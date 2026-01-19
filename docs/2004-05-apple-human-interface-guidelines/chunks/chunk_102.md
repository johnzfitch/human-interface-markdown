<!-- Chunk 102 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 676 -->
When a user presses and holds the mouse button on your application's tile in the Dock, a menu appears. The menu lists the application's open windows and contains the Show In Finder, Hide, and Quit commands. The Show In Finder command displays a Finder window for the folder containing your application. The Hide and Quit commands function as documented in ["The](#page-86-1) [Application Menu"](#page-86-1) (page 87). If the user presses the Option key, Hide changes to Hide Others and Quit changes to Force Quit. If the tile has not been permanently added to the Dock, the command Keep In Dock also appears.  
Dock Menus **99**  
<span id="page-99-0"></span>**Figure 7-25** The iTunes Dock menu  
![](images/_page_99_Picture_3.jpeg)  
You can customize your application's Dock menu by adding to the default items provided by the Dock. These additional items appear in the Dock menu only when the application is open. Potential additional items include:  
- Common commands to initiate actions in your application when it is not frontmost
- Commands that are applicable when there is no open document window
- Status and informational text  
For example, a mail application could provide commands to initiate a new message or to check for new messages.  
<span id="page-99-1"></span>Any command you add to the Dock menu should also be available in your application's pull-down menus. Application-specific items appear above the standard Dock menu items.  
**Carbon:** See *Customizing Your Application Dock Tile* in Carbon User Experience Documentation. **Cocoa:** See NSApplication reference documentation for information on customizing the Dock menu.  
<span id="page-100-4"></span><span id="page-100-2"></span><span id="page-100-0"></span>Windows provide a frame for viewing and interacting with applications and data.  
From a developer's perspective, there are many types of windows in Mac OS X. Although a user might see them all as windows, the distinctions in behavior (layering, zooming, minimizing) and appearance (title bars) among the various types of windows contribute to the Macintosh user experience. It is important that you understand the different types of windows available, general window behavior, and behavior specific to one type of window.  
This chapter first introduces the different types of windows and then focuses on the appearance and behavior of document, application, and utility windows. Dialogs and alert windows are unique types of windows with guidelines in addition to those for standard windows. They are discussed in detail in ["Dialogs"](#page-132-2) (page 133). Note that unless explicitly stated, dialogs should behave like the windows discussed in this chapter.