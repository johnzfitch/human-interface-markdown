<!-- Chunk 254 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 610 -->
Utility windows are either application-specific or systemwide. Application-specific utility windows disappear when the application is deactivated.  
Systemwide utility windows, such as the Colors window and the Fonts window, float on top of all open windows.  
<span id="page-195-1"></span>You can create a modeless utility window, such as a tools palette, to present controls or settings that affect the active document window. Utility windows are useful for keeping extremely important controls or information accessible at all times in the context of a user task. Because utility windows take up screen space, however, don't use them when you can meet the need by using a modeless dialog (the user changes settings and then closes the dialog) or by adding a few appropriate controls to a window frame.  
A user can open several utility windows at a time; they float on top of document windows. When a user makes a document active, all of the application's utility windows should be brought to the front, regardless of which document was active when the user opened the utility window. When your application is inactive, its utility windows should be hidden. Utility windows should not be listed in the Window menu as documents, but you may put commands to show or hide all utility windows in the Window menu.  
<span id="page-196-0"></span>**Figure 13-23** Utility windows  
![](images/_page_196_Picture_3.jpeg)  
<span id="page-196-1"></span>A utility window may have a title. An untitled utility window should have a title-bar region for dragging the window.  
A user would never need to minimize a utility window because it is displayed only when needed and disappears when its application is inactive. Therefore, the minimize button is always unavailable.A utility window should have the close and zoom buttons or, if you don't want users to be able to use the zoom button, only the close button. These configurations are shown in Figure 13-23.  
**Carbon:** Specify which of controls are visible with the ChangeWindowAttributes function.  
<span id="page-197-1"></span>**Figure 13-24** Utility window controls  
![](images/_page_197_Picture_3.jpeg)  
For information about designing utility windows, see ["Using Small and Mini Versions of Controls](#page-292-0) ["](#page-292-0) (page 293).  
<span id="page-197-0"></span>**Carbon:** Utility windows are available using kUtilityWindowClass.  
**Cocoa:** Use NSNonactivatingPanelMask