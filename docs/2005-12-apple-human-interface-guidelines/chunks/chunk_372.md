<!-- Chunk 372 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 487 -->
A **disclosure triangle** allows the display, or disclosure, of information or functionality associated with the primary information in a window. A disclosure triangle is not used to display additional choices associated with a specific control, such as a pop-up menu. If you need to do this, use a disclosure button (see ["Disclosure Buttons"](#page-267-0) (page 268)).  
Disclosure triangles have two uses: in dialogs that have a minimal state and an expanded state and in hierarchical lists. See Figure 14-52 for an example in a dialog and [Figure 14-55](#page-268-1) (page 269) for an example in a hierarchical list.  
Use a disclosure triangle when you want to provide a simple default view of something but need to allow the user to view more details or perform additional actions at times.  
Disclosure triangles should be in the closed position, pointing to the right, by default. When the user clicks a disclosure triangle, it points down and the additional information is displayed.  
Controls  
Disclosure triangles in dialogs should have a label indicating what is disclosed or hidden. An ideal label changes depending on the position of the disclosure triangle. For example, when closed it might say, "Show advanced settings," and when open, "Hide advanced settings."  
<span id="page-266-0"></span>**Figure 14-52** Disclosure triangle used to progressively reveal dialog contents  
![](images/_page_266_Picture_4.jpeg)  
![](images/_page_266_Picture_5.jpeg)  
**Carbon:** Disclosure triangles are available in Interface Builder. To create one programmatically, you can use the Control Manager function CreateDisclosureTriangleControl or the Appearance Manager function HIThemeDrawButton.  
**Cocoa:** Disclosure triangles are available in Interface Builder. To create one programmatically, set the bezel style to NSDisclosureBezelStyle and the button type to NSPushOnPushOffButton. See *Buttons* in Cocoa User Experience Documentation.