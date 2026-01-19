<!-- Chunk 291 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 605 -->
A **disclosure triangle** allows the display, or disclosure, of information or functionality associated with the primary information in a window. For example, in a System Preferences authentication dialog (shown in Figure 15-76) a disclosure triangle reveals details that most users don't often choose to see.  
<span id="page-333-0"></span>**Figure 15-76** A disclosure triangle can reveal more dialog contents  
![](images/_page_333_Picture_3.jpeg)  
#### Disclosure Triangle Usage  
Use a disclosure triangle when you want to provide a simple default view of something but need to allow the user to view more details or perform additional actions at times. Specifically, you can use a disclosure triangles in either of the two following ways:  
- To reveal more information in dialogs that have a minimal state and an expanded state. SeeFigure 15-76 for an example of a disclosure triangle in a dialog.
- To reveal subordinate items in a hierarchical list. See [Figure](#page-337-1) 15-80 (page 338) for an example of a disclosure triangle in a hierarchical list.  
Don't use a disclosure triangle to display additional choices associated with a specific control, such as a pop-up menu. If you need to do this, use a disclosure button (see ["Disclosure](#page-334-0) Buttons" (page 335)).  
#### Disclosure Triangle Contents and Labeling  
Disclosure triangles should be in the closed position (that is, pointing to the right) by default. When the user clicks a disclosure triangle, it points down and the additional information is displayed.  
Disclosure triangles in dialogs should have a label indicating what is disclosed or hidden. Ideally, the label changes depending on the position of the disclosure triangle. For example, when closed it might say, "Show advanced settings," and when open, "Hide advanced settings."  
#### Disclosure Triangle Specifications  
<span id="page-334-4"></span><span id="page-334-1"></span>**Control sizes**: Disclosure triangles are available in a single size, 13 x 13 pixels, as shown in Figure 15-77.  
**Figure 15-77** Disclosure triangles  
![](images/_page_334_Picture_8.jpeg)  
#### Disclosure Triangle Implementation  
<span id="page-334-0"></span>Disclosure triangles are available in Interface Builder. To create one using Application Kit programming interfaces, use NSButton and set the bezel style to NSDisclosureBezelStyle and the button type to NSPushOnPushOffButton.