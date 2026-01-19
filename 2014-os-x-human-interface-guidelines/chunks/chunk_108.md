<!-- Chunk 108 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 865 -->
A **push button** performs an app-specific action.  
![](images/_page_178_Picture_3.jpeg)  
**API Note:** To define a push button in your code, create an NSButton object of type NSMomentaryPushInButton or NSMomentaryLightButton. (Note that the NSTexturedRoundedBezelStyle style of NSButton is designed for use in the window frame.)  
#### A push button:  
- Is designed for use in the window body only, not in the window-frame areas. To learn about controls that you can use in window-frame areas, see Some [Controls](#page-176-1) Can Be Used in the Window Frame (page 177).
- Always contains text, never an image.
- Is white, unlessit'sthe default button in a dialog. For more information about dialog controls,see [Dismissing](#page-155-0) [Dialogs](#page-155-0) (page 156).
- May open another window to complete its operation.  
Use a push button in the window body to perform an instantaneous action, such as Print or Delete.  
**Avoid using a push button to mimic the behavior of other controls.** Users expect an immediate action to occur when they click a push button, including the opening of another window or the dismissal of a dialog. In particular:  
- Don't use a push button to indicate a state, such as on or off. Instead, you can use checkboxes to indicate state, as described in [Checkbox](#page-181-0) (page 182).
- Don't use a push button as a label. Instead, use static text to label elements and provide information in the interface, as described in [Static](#page-212-1) Text Field (page 213).  
● Avoid associating a menu with a push button.  
**Use enough space between buttons so that users can click a specific one easily.** In particular, if a push button can lead to a potentially dangerous or destructive action (such as Delete), place it far enough away from safe buttons so that users are unlikely to click it accidentally.  
**Avoid displaying an image in a standard push button.** A standard push button should contain text that describes the action it performs.  
**Use a verb or verb phrase and title-style capitalization forthe title of a push button.** The title should describe the action the button performs—Save, Close, Print, Delete, Change Password, and so on. If a push button acts on a single setting or entity, name the button as specifically as possible; "Choose Picture…," for example, is more helpful than "Choose…" Because buttons initiate an immediate action, there's no need to include "now" in the button title. To learn more about title-style capitalization, see Use the Right [Capitalization](#page-46-0) Style in Labels and [Text](#page-46-0) (page 47).  
**Add an ellipsis to the title if the button immediately opens another window, dialog, or app to perform its action.** An ellipsis prepares users to expect another window to open in which they complete the action the button initiates. For example, the Print & Scan preferences pane uses ellipsis charactersin the names of buttons that open the print queue window and show information about the printer's options and supplies.  
![](images/_page_179_Picture_6.jpeg)  
**Resize a button's width to accommodate the title.** If you don't make a button wide enough, the end caps clip the text. Note that the height of a push button is fixed for each size.  
<span id="page-179-0"></span>**In general, don't use a static text label to introduce a push button.** Avoid an introductory label by clearly describing the push button action in the button title.