<!-- Chunk 124 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 329 -->
The **About window,** also called the About box, is a window that contains your application's version and copyright information. It should be modeless so the user can leave it open and perform other tasks in the application.  
You should always provide an About window and make it accessible from the application menu.  
At a minimum, your application's About window should:  
- Have a title bar with no title
- <span id="page-128-2"></span>■ Be movable
- Include the close button as the only active window control
- Display application branding
- Include the full application name and version number  
<span id="page-128-1"></span>It is recommended to also provide text that briefly describes what the application does, copyright information, as well as technical support contact information.  
**Figure 8-25** Example of an About windows  
![](images/_page_128_Picture_10.jpeg)  
The About window (or the splash screen) is the appropriate place for product branding elements; avoid putting them in document windows and dialogs.  
**Carbon:** Use HIAboutBox to provide a default About window. You can designate specific settings in your application's Info.plist file.  
**Cocoa:** The About window is provided automatically by the Application Kit; set the relevant information in your application's Info.plist file.