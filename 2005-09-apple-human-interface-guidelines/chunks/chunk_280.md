<!-- Chunk 280 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 311 -->
The **Help button** opens Help Viewer to a specific help page appropriate for the context of the button. Don't create a custom button; use the standard Help button, which contains the Mac OS X question mark graphic.  
In dialogs, sheets, and drawers, the Help button typically is located in the lower left corner and is verticallyalignedwith the OK and Cancel buttons, if theyare present. Figure 14-12 shows an example of a dialog that includes a Help button.  
<span id="page-229-1"></span>**Figure 14-12** Help button in the Page Setup dialog  
![](images/_page_229_Picture_3.jpeg)  
For information on using help in your application, see "User [Assistance"](#page-73-0) (page 74).  
**Carbon:** The Help button is available in the Enhanced Controls palette of Interface Builder. You can create it programmaticallyby usingthe CreateRoundButtonControl function and specifying kHelpIcon in the content parameters (from Icon Services). (See Icons.h in the HIServices framework.)  
**Cocoa:** The Help button is available in the Controls palette of Interface Builder. To create a Help button programmatically, use the NSButtonCell method setBezelStyle with NSHelpButtonBezelStyle as the argument. See *Buttons*in Cocoa User Experience Documentation.