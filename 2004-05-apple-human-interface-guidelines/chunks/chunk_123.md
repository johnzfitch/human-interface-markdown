<!-- Chunk 123 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 615 -->
Utility windows are either application-specific or systemwide. Application-specific utility windows disappear when the application is deactivated.  
Systemwide utility windows, such as the Colors window and the Fonts window, float on top of all open windows.  
<span id="page-126-2"></span>You can create a modeless utility window, such as a tools palette, to present controls or settings that affect the active document window. Utility windows are useful for keeping extremely important controls or information accessible at all times in the context of a user task. Because utility windows take up screen space, however, don't use them when you can meet the need by using a modeless dialog (the user changes settings and then closes the dialog) or by adding a few appropriate controls to a window frame.  
<span id="page-126-1"></span>A user can open several utility windows at a time; they float on top of document windows. When a user makes a document active, all of the application's utility windows should be brought to the front, regardless of which document was active when the user opened the utility window. When your application is inactive, its utility windows should be hidden. Utility windows should not be listed in the Window menu as documents, but you may put commands to show or hide utility windows in the Window menu.  
**Figure 8-23** Utility windows  
![](images/_page_126_Picture_7.jpeg)  
A utility window may have a title. An untitled utility window should have a title-bar region for dragging the window.  
Utility Windows **127**  
<span id="page-127-3"></span>A user would never need to minimize a utility window because they are displayed only when needed and disappear when their application is inactive. Therefore, the minimize button is always unavailable.A utility window should have the close and zoom buttons or, if you don't want users to be able to use the zoom button, only the close button. These configurations are shown in Figure 8-23.  
<span id="page-127-1"></span>**Carbon:** Specify which of controls are visible with the ChangeWindowAttributes function.  
**Figure 8-24** Utility window controls  
![](images/_page_127_Picture_5.jpeg)  
For information about designing utility windows, see ["Using Small and Mini Versions of](#page-213-0) [Controls"](#page-213-0) (page 214).  
**Carbon:** Utility windows are available using kUtilityWindowClass.  
<span id="page-127-4"></span>**Cocoa:** use NSNonactivatingPanelMask