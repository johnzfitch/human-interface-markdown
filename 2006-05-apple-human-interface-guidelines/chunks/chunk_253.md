<!-- Chunk 253 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 493 -->
<span id="page-205-2"></span>An **About window,** also called an About box, is an Info window that contains your application's version and copyright information. It should be modeless so the user can leave it open and perform other tasks in the application.  
You should always provide an About window and make it accessible from the application menu.  
At a minimum, your application's About window should:  
- <span id="page-205-3"></span>■ Have a title bar with no title
- Be movable
- Include the close button as the only active window control
- Display application branding
- Include the full application name and version number (the version number should be the same as the version number in the application's Info window and displayed by the Finder)  
It is recommended to also provide text that briefly describes what the application does, copyright information, as well as technical support contact information.  
<span id="page-205-1"></span>If you want to give the user a convenient way to visit your website or contact your company from your About window, be sure to create buttons that accomplish these tasks. Do not provide a clickable URL or email address because it is not necessarily clear that there is an action associated with it. Of course, it's best to provide most of your company contact information in the first page of your help documentation (see "The Help [Menu"](#page-171-0) (page 172) for more information on Help menu items).  
**Figure 13-27** Example of an About window  
![](images/_page_205_Picture_15.jpeg)  
An About window (or a splash screen) is the appropriate place for product branding elements; avoid putting them in document windows and dialogs.  
**Carbon:** Use HIAboutBox to provide a default Aboutwindow. You can designate specific settings in your application's Info.plist file.  
**Cocoa:** An About window is provided automatically by the Application Kit; set the relevant information in your application's Info.plist file.