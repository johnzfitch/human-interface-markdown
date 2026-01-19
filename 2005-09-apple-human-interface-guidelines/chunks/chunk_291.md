<!-- Chunk 291 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 331 -->
<span id="page-235-4"></span><span id="page-235-3"></span>A bevel button or an icon button containing a pop-up menu has a single downward-pointing arrow. The button can behave like a standard pop-up menu, in which the image on the button is the current selection, or the button can represent the menu title and always display the same image.  
See "Bevel [Buttons"](#page-225-0)(page 226) and "Icon [Buttons"](#page-226-0)(page 227) for specifications forthe buttons themselves.  
**Carbon:** Create this in Interface Builder by using a bevel button and selecting the Has Menu option in the Attributes pane of the inspector.  
**Cocoa:** Select the NSPopUpButton widget in Interface Builder. In the inspector, change its type to PullDown. Change the Style to Square or Shadowless Square for a Rounded or Square Bevel Button, respectively. For an icon button, it doesn't matter which one you choose, just deselect the Bordered checkbox. Resize the button as needed.  
<span id="page-235-1"></span>**Figure 14-17** Pop-up icon button  
![](images/_page_235_Picture_8.jpeg)  
**Figure 14-18** Pop-up bevel button with square corners  
<span id="page-235-2"></span>![](images/_page_235_Picture_10.jpeg)  
<span id="page-236-1"></span>**Figure 14-19** Pop-up bevel button with rounded corners  
![](images/_page_236_Picture_3.jpeg)