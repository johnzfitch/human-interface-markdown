<!-- Chunk 87 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 364 -->
A **bevel button** has a beveled edge that gives the button a three-dimensional appearance. A bevel button  
- can display text, an icon, or a picture
- mimics the behavior of other button types; for example, a bevel button can behave like a standard push button. Bevel buttons can be grouped and used like radio buttons or checkboxes.
- can have a menu attached, so the button behaves like a pop-up menu. See ["Pop-Up Bevel Buttons and Pop-Up Icon Buttons" \(page 99\)](#page-98-3)
- can have rounded or square corners. The square buttons work well for tiling together in groups, to be used as radio buttons, for example.  
#### <span id="page-97-1"></span>Bevel Button Specifications  
- **Size:** 20 x 20 pixels minimum
- **Horizontal spacing:** 8 pixels minimum  
If a bevel button has an icon and a label, you can put the text anywhere in relation to the icon. Carbon developers can specify the location with the SetControlData API; Cocoa developers set it in Interface Builder.  
**Figure 7-12** Bevel buttons  
#### <span id="page-98-1"></span>**Rounded corners**  
![](images/_page_98_Picture_4.jpeg)  
Leave at least 5 pixels between edge of icon and edge of button.  
#### **Rounded corners with label below icon**  
![](images/_page_98_Picture_7.jpeg)  
#### **Square corners**  
![](images/_page_98_Picture_9.jpeg)  
**Figure 7-13** Bevel buttons as radio buttons and push buttons  
<span id="page-98-2"></span>![](images/_page_98_Figure_11.jpeg)