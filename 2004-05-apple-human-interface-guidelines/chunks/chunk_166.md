<!-- Chunk 166 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 339 -->
<span id="page-169-3"></span><span id="page-169-2"></span>A bevel button or a icon button containing a pop-up menu has a single downward-pointing arrow. The button can behave like a standard pop-up menu, in which the image on the button is the current selection, or the button can represent the menu title and always display the same image.  
See ["Bevel Buttons"](#page-159-0) (page 160) and ["Icon Buttons"](#page-161-0) (page 162) for specifications for the buttons themselves.  
**Carbon:** Create this in Interface Builder by using a bevel button and selecting the Has Menu option in the Attributes pane of the inspector.  
<span id="page-169-1"></span>**Cocoa:** Select the NSPopUpButton widget in Interface Builder. In the inspector, change its type to PullDown. Change the Style to Square or Shadowless Square for a Rounded or Square Bevel Button, respectively. For an icon button, it doesn't matter which one you choose, just deselect the Bordered checkbox. Resize the button as needed.  
**Figure 10-17** Pop-up icon button  
![](images/_page_169_Picture_8.jpeg)  
<span id="page-170-1"></span>**Figure 10-18** Pop-up bevel button with square corners  
![](images/_page_170_Picture_3.jpeg)  
**Figure 10-19** Pop-up bevel button with rounded corners  
<span id="page-170-3"></span><span id="page-170-2"></span>![](images/_page_170_Picture_5.jpeg)