<!-- Chunk 188 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 237 -->
<span id="page-161-3"></span>An **icon button** behaves like a bevel button, but does not have a rectangular edge around it; the entire button is clickable, not just the icon.  
<span id="page-161-1"></span>Icon buttons may have pop-up menus attached. See ["Icon Buttons and Bevel Buttons With Pop-Up](#page-169-0) [Menus"](#page-169-0) (page 170) for more information.  
**Figure 10-8** Icon buttons used in a toolbar  
![](images/_page_161_Picture_6.jpeg)  
**Carbon:** Create icon buttons programmatically with the function CreateIconControl.  
**Cocoa:** To create an icon button in Interface Builder, use the bevel button widget (NSButton) from the Controls palette. Add the appropriate icon, then select the button and in the Attributes inspector, deselect Bordered. To create one programmatically, use the NSButtonCell method setBezelStyle with NSShadowlessSquareBezelStyle as the argument. See *Buttons* in Cocoa User Experience Documentation.