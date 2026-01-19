<!-- Chunk 159 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 323 -->
<span id="page-163-4"></span><span id="page-163-3"></span><span id="page-163-1"></span>The **Help button** opens Help Viewer to a specific help page appropriate for the context of the button. Don't create a custom button; use the standard Help button, which contains the Mac OS X question mark graphic.  
**Figure 10-12** Help button in the Print dialog  
![](images/_page_163_Picture_5.jpeg)  
For information on using help in your application, see *Apple Software Design Guidelines*.  
**Carbon:** The Help button is available in the Enhanced Controls palette of Interface Builder. You can create it programmatically by using the CreateRoundButtonControl function and specifying kHelpIcon in the content parameters (from Icon Services). (See Icons.h in the HIServices framework.)  
**Cocoa:** The Help button is available in the Controls palette of Interface Builder. To create a Help button programmatically, use the NSButtonCell method setBezelStyle with NSHelpButtonBezelStyle as the argument. See *Buttons* in Cocoa User Experience Documentation.  
#### <span id="page-163-2"></span>Help Button Specifications  
**Figure 10-13** Help button dimensions  
![](images/_page_163_Picture_11.jpeg)  
- **Size:** 20 x 20 pixels
- **Spacing:** At least 12 pixels or from other interface elements