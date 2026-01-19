<!-- Chunk 192 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 248 -->
<span id="page-163-1"></span>The **Help button** opens Help Viewer to a specific help page appropriate for the context of the button. Don't create a custom button; use the standard Help button, which contains the Mac OS X question mark graphic.  
**Figure 10-12** Help button in the Print dialog  
![](images/_page_163_Picture_6.jpeg)  
For information on using help in your application, see *Apple Software Design Guidelines*.  
**Carbon:** The Help button is available in the Enhanced Controls palette of Interface Builder. You can create it programmatically by using the CreateRoundButtonControl function and specifying kHelpIcon in the content parameters (from Icon Services). (See Icons.h in the HIServices framework.)  
**Cocoa:** The Help button is available in the Controls palette of Interface Builder. To create a Help button programmatically, use the NSButtonCell method setBezelStyle with NSHelpButtonBezelStyle as the argument. See *Buttons* in Cocoa User Experience Documentation.