<!-- Chunk 97 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 557 -->
The **About window,** also called an About box, is a window that contains your application's version and copyright information. It should be modeless so the user can leave it open and perform other tasks in the application.  
Your application's About window should  
- <span id="page-87-2"></span>■ have a title bar and be movable
- include the close button as the only active window control (if you include the minimize and zoom buttons, dim them)
- display a centered application icon and the full application title  
You can also provide text that briefly describes what the application does. The recommended version in Figure 5-14 (page 89) has an application description.  
<span id="page-88-1"></span><span id="page-88-0"></span>**Figure 5-14** Examples of About windows (all specifications apply to both versions)  
![](images/_page_88_Figure_3.jpeg)  
All text in an About window is centered, except for the optional descriptive text, which is flush left. If you want to include a scrolling list (for credits, for example), put it between the descriptive text and the copyright information.  
An About window (or splash screen) is the appropriate place for your corporate logo. Avoid putting product branding elements in document windows and dialogs.  
For Cocoa developers, About window support is provided by the Application Kit. Carbon developers need to create their own or use a ".nib" file.  
Special Windows **89**  
Windows  
<span id="page-90-3"></span><span id="page-90-0"></span>A **dialog** is a window designed to elicit a response from the user. Many dialogs the Print dialog, for example—permit the user to provide many responses at one time.  
<span id="page-90-2"></span>**Alerts** are dialogs that appear when the system or an application needs to communicate information to the user. They provide messages about error conditions and warn users about potentially hazardous situations or actions.  
For information about using the keyboard to interact with dialogs, see ["Keyboard](#page-167-0)  [Focus and Navigation" \(page 168\).](#page-167-0)  
<span id="page-90-4"></span>For specific design information on how to lay out dialogs, see ["Layout Guidelines"](#page-142-0) [\(page 143\).](#page-142-0)