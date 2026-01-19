<!-- Chunk 275 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 471 -->
<span id="page-228-3"></span>An **About window**, also called an About box, is an optional window that contains your application's version and copyright information. Unlike other windows, an About window combines some of the behaviors of panels and windows: Like a panel, an About window is not listed in the application's Window menu and like a window, it remains visible when the application is inactive. An About window should be modeless so the user can leave it open and perform other tasksin the application. For example, iCal provides an About window, as shown in Figure 14-45.  
**Figure 14-45** Example of an About window  
![](images/_page_228_Picture_10.jpeg)  
If you decide to provide an About window, it should:  
- Have a title bar with no title
- <span id="page-229-3"></span>■ Be movable
- Include the close button as the only active window control
- Display application branding, such as a logo
- Include the full application name and version number (the version number should be the same as the version number displayed by the Finder)  
It isrecommended to also provide text that briefly describes what the application does, copyright information, and technical support contact information.  
If you want to give the user a convenient way to visit your website or contact your company from your About window, be sure to create buttons that accomplish these tasks. Do not provide a clickable URL or email address because it is not necessarily clear that there is an action associated with it. Of course, it's best to provide most of your company contact information in the first page of your help documentation (see ["The](#page-182-0) Help [Menu"](#page-182-0) (page 183) for more information on Help menu items).  
An About window is the appropriate place for product branding elements; avoid putting such elements (logos or slogans) in document windows and dialogs.