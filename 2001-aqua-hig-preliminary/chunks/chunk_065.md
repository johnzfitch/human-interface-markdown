<!-- Chunk 65 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 532 -->
An **About box** is a modeless window (the user can leave it open and perform other tasks in the application) that contains your application's version and copyright information.  
Your application's About box should  
- have a title bar and be movable
- include the close button as the only active window control (dim the minimize and zoom buttons)
- display a centered application image and application title  
Special Windows **69**  
<span id="page-69-1"></span><span id="page-69-0"></span>**Figure 5-11** Examples of About boxes  
#### **Recommended version Smallest version Application icon** 64 x 64 pixels centered **Application title** Lucida Grande Bold 14 pt. centered **Application title** 19 pixel text height centered **Application version** Label font 10 pt. Lucida Grande Reg. centered **Copyright information** Label font 10 pt. Lucida Grande Reg. centered **Application description** Small system font 11 pt. Lucida Grande Reg. flush left **Label font** 12 pixel text height centered  
All text in an About box is centered, except for the optional descriptive text, which is flush left. If you want to include a scrolling list (for credits, for example), put it between the descriptive text and the copyright information.  
An About box (or splash screen) is the appropriate place for your corporate logo. Avoid putting product branding elements in document windows and dialogs.  
For Cocoa developers, About box support is provided by the Application Kit.  
<span id="page-70-3"></span><span id="page-70-0"></span>A dialog is a window designed to elicit a response from the user. Many dialogs the Print dialog, for example—permit the user to provide many responses at one time.  
<span id="page-70-2"></span>**Alerts** are dialogs that appear when the system or an application needs to communicate information to the user. They provide messages about error conditions and warn users about potentially hazardous situations or actions.  
<span id="page-70-4"></span>For information about using the keyboard to interact with dialogs, see ["Keyboard](#page-140-0)  [Navigation and Focus" \(page 141\).](#page-140-0)