<!-- Chunk 63 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 336 -->
You can create a modeless utility window, such as a tools palette, to present controls or settings that affect the active document window. A user can open several utility windows at a time; they float on top of document windows. When a user makes a document active, all of the application's utility windows are brought to the front, regardless of which document was active when the user opened the utility window.  
<span id="page-66-2"></span>**Figure 5-9** Examples of tool palettes (utility windows)  
![](images/_page_66_Picture_8.jpeg)  
Utility windows are useful for keeping extremely important controls or information accessible at all times in the context of a user task. Because utility windows take up screen space, however, don't use them when you can solve the need with a modeless dialog (the user changes settings and then closes the dialog) or by adding a few appropriate controls to a window frame.  
Special Windows **67**  
#### Windows  
You need to create and maintain any utility windows for your application. Whenever your application is in the background, hide all utility windows.  
Most utility windows don't have titles, but they do have an 11-pixel-high drag region at the top.  
For information about designing Aqua palette windows, see ["Using Small Versions](#page-122-0)  [of Controls" \(page 123\)](#page-122-0).