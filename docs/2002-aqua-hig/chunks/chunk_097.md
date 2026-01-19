<!-- Chunk 97 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 593 -->
The **About window,** also called the About box, is a window that contains your application's version and copyright information. It should be modeless so the user can leave it open and perform other tasks in the application.  
At a minimum, your application's About window should  
- <span id="page-92-2"></span>■ have a title bar and be movable
- include the close button as the only active window control (if you include the minimize and zoom buttons, dim them)
- display a centered application icon and the full application title  
It is recommended to also provide text that briefly describes what the application does, as shown in Figure 5-17.  
<span id="page-92-1"></span><span id="page-92-0"></span>**Figure 5-17** Examples of About windows (all specifications apply to both versions)  
![](images/_page_92_Figure_8.jpeg)  
#### **CHAPTER 5**  
#### Windows  
All text in an About window should be centered, except for the optional descriptive text, which is flush left. If you want to include a scrolling list (for credits, for example), put it between the descriptive text and the copyright information.  
An About window (or splash screen) is the appropriate place for product branding elements; avoid putting them in document windows and dialogs.  
For Cocoa developers, About windows are automatically defined by the Application Kit. Carbon developers need to create their own (using a .nib file, for example).  
<span id="page-94-3"></span><span id="page-94-0"></span>A **dialog** is a window designed to elicit a response from the user. Many dialogs the Print dialog, for example—permit the user to provide many responses at one time.  
<span id="page-94-2"></span>**Alerts** are dialogs that appear when the system or an application needs to communicate information to the user. They provide messages about error conditions and warn users about potentially hazardous situations or actions.  
For information about using the keyboard to interact with dialogs, see ["Keyboard](#page-181-0)  [Focus and Navigation" \(page 182\).](#page-181-0)  
For specific design information on how to lay out dialogs, see ["Layout Guidelines"](#page-148-0) [\(page 149\).](#page-148-0)  
<span id="page-94-5"></span>For implementation information, Carbon developers should see *Handling Carbon Windows and Controls,* available on the Mac OS X developer documentation website.