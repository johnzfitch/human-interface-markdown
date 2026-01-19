<!-- Chunk 302 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 233 -->
An **icon button** behaves like a bevel button, but does not have a rectangular edge around it; the entire button is clickable, not just the icon.  
Controls  
Icon buttons may have pop-up menus attached. See ["Icon Buttons and Bevel Buttons With Pop-Up](#page-239-0) [Menus "](#page-239-0) (page 240) for more information.  
<span id="page-231-1"></span>**Figure 14-8** Icon buttons used in a toolbar  
![](images/_page_231_Picture_4.jpeg)  
**Carbon:** Create icon buttons programmatically with the function CreateIconControl. **Cocoa:** To create an icon button in Interface Builder, use the bevel button widget (NSButton) from the Controls palette. Add the appropriate icon, then select the button and in the Attributes inspector, deselect Bordered. To create one programmatically, use the NSButtonCell method setBezelStyle with NSShadowlessSquareBezelStyle as the argument. See *Buttons* in Cocoa User Experience Documentation.