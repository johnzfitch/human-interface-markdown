<!-- Chunk 210 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 272 -->
<span id="page-178-3"></span>A **placard** is a small section at the bottom of a window used to display information, such as the current page number. You can also use a placard to create the striped background behind controls.  
<span id="page-178-2"></span>Typically placards are used in document windows as a way to quickly modify the view of the contents—for example, to change the current page or the magnification. The most familiar use of the placard is as a pop-up menu placed at the bottom of a window, to the left of the horizontal scroll bar.  
**Figure 10-27** A placard with a pop-up menu  
![](images/_page_178_Picture_9.jpeg)  
Placards are 15 pixels high and use either the small system font or the label font for text.  
**Carbon:** Use the Control Manager CreatePlacardControl function or the function HIThemeDrawPlacard in the Appearance Manager. The standard placard control does not include a menu. If you want to display a menu, override the default behavior of the draw Carbon event and the click Carbon event.  
<span id="page-178-1"></span>**Cocoa:** Not available.