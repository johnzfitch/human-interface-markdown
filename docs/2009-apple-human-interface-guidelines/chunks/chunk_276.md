<!-- Chunk 276 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 620 -->
A **disclosure triangle** allows the display, or disclosure, of information or functionality associated with the primary information in a window. For example, in a System Preferences authentication dialog (shown in Figure 15-76) a disclosure triangle reveals details that most users don't often choose to see.  
View Controls **329**  
<span id="page-329-0"></span>**Figure 15-76** A disclosure triangle can reveal more dialog contents  
![](images/_page_329_Picture_3.jpeg)  
![](images/_page_329_Figure_4.jpeg)  
#### Disclosure Triangle Usage  
Use a disclosure triangle when you want to provide a simple default view of something but need to allow the user to view more details or perform additional actions at times. Specifically, you can use a disclosure triangle in either of the two following ways:  
- To reveal more information in dialogs that have a minimal state and an expanded state. See Figure 15-76 for an example of a disclosure triangle in a dialog.
- To revealsubordinate itemsin a hierarchical list. See [Figure](#page-333-1) 15-80 (page 334) for an example of a disclosure triangle in a hierarchical list.  
Don't use a disclosure triangle to display additional choices associated with a specific control, such as a pop-up menu. If you need to do this, use a disclosure button (see ["Disclosure](#page-330-0) Buttons" (page 331)).  
#### Disclosure Triangle Contents and Labeling  
Disclosure triangles should be in the closed position (that is, pointing to the right) by default. When the user clicks a disclosure triangle, it points down and the additional information is displayed.  
Disclosure triangles in dialogs should have a label indicating what is disclosed or hidden. Ideally, the label changes depending on the position of the disclosure triangle. For example, when closed it might say, "Show advanced settings," and when open, "Hide advanced settings."  
#### <span id="page-330-4"></span>Disclosure Triangle Specifications  
<span id="page-330-1"></span>**Control sizes**: Disclosure triangles are available in a single size, 13 x 13 pixels, as shown in Figure 15-77.  
**Figure 15-77** Disclosure triangles  
![](images/_page_330_Picture_8.jpeg)  
#### Disclosure Triangle Implementation  
<span id="page-330-0"></span>Disclosure triangles are available in Interface Builder. To create one using Application Kit programming interfaces, use NSButton and set the bezel style to NSDisclosureBezelStyle and the button type to NSPushOnPushOffButton.