<!-- Chunk 201 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 622 -->
When a user presses and holds the mouse button on your application's tile in the Dock, a menu appears. The menu lists the application's open windows and contains the Show In Finder, Hide, and Quit commands. The Show In Finder command displays a Finder window for the folder containing your application. The Hide and Quit commands function as documented in "The [Application](#page-177-0) [Menu"](#page-177-0) (page 178). If the user presses the Option key, Hide changes to Hide Others and Quit changes to Force Quit. If the tile has not been permanently added to the Dock, the command Keep In Dock also appears.  
<span id="page-190-0"></span>**Figure 13-25** The iTunes Dock menu  
![](images/_page_190_Picture_3.jpeg)  
You can customize your application's Dock menu by adding to the default items provided by the Dock. These additional items appear in the Dock menu only when the application is open. Potential additional items include:  
- Common commands to initiate actions in your application when it is not frontmost
- Commands that are applicable when there is no open document window
- Status and informational text  
<span id="page-190-1"></span>For example, a mail application could provide commands to initiate a new message or to check for new messages.  
Any command you add to the Dock menu should also be available in your application's pull-down menus. Application-specific items appear above the standard Dock menu items.  
**C HAPTER 1 3**  
Menus  
<span id="page-192-2"></span><span id="page-192-0"></span>Windows provide a frame for viewing and interacting with applications and data.  
From a developer's perspective, there are several types of windows in Mac OS X. Although users tend to see them all as windows, the distinctions in behavior (layering, zooming, minimizing) and appearance (presence or absence of title bars) among the various types of windows contribute to the Macintosh user experience. It is important that you understand the different types of windows available, general window behavior, and behavior specific to each type of window.  
This chapter first introduces the different types of windows and then focuses on the appearance and behavior of document and application windows and panels. Dialogs and alert windows are unique types of windows with guidelines in addition to those for standard windows. They are discussed in detail in ["Dialogs"](#page-237-0) (page 238). Note that unless explicitlystated, dialogs should behave likewindows.