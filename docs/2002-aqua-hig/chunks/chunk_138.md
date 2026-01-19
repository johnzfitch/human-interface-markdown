<!-- Chunk 138 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 399 -->
<span id="page-131-1"></span>**Figure 7-14** Bevel button specifications  
#### **Rounded corners**  
![](images/_page_131_Picture_5.jpeg)  
Leave at least 5 pixels between edge of icon and edge of button.  
#### **Rounded corners with label below icon**  
![](images/_page_131_Figure_8.jpeg)  
#### **Square corners**  
![](images/_page_131_Figure_10.jpeg)  
- **Size of button:** 20 x 20 pixels minimum
- **Size of icon:** 32 x 32 pixels recommended, with at least 5 pixels between icon and button edge  
- **Spacing:** For buttons with rounded corners that contain a 24 x 24 (or larger) icon, leave at least 8 pixels between buttons, stacked vertically or aligned horizontally. Otherwise, buttons should butt up against each other.
- **Text:** Label font (10-point Lucida Grande Regular)  
If a bevel button has an icon and a label, you can put the text anywhere in relation to the icon. Carbon and Cocoa developers can specify the location in Interface Builder or programmatically. Cocoa developers can create square bevel buttons with the NSButton class. Carbon developers can use the CreateBevelButtonControl function or, in Appearance Manager, the DrawThemeButton function with the kThemeBevelButton constant.  
In some situations—providing text-alignment options in a toolbar, for example—it is appropriate to use bevel buttons to graphically represent several mutually exclusive choices. You can also use bevel buttons for nonstandard-size push buttons.  
<span id="page-132-1"></span>**Figure 7-15** Bevel buttons as radio buttons and push buttons  
![](images/_page_132_Picture_7.jpeg)