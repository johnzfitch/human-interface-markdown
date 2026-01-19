<!-- Chunk 5 | Source: 1996 Human Interface Guidelines for Mac OS 8 (WWDC Release).pdf | Est. Tokens: 1149 -->
This section describes changes to the document window appearance and utility window appearance introduced with Mac OS 8.  
#### Window Controls 0  
This section describes the new controls that appear in a document window. Figure 1 shows a document window in the Apple Default Appearance.  
**Figure 1** Document wIndow  
![](images/_page_5_Picture_6.jpeg)  
#### Collapse Box 0  
The collapse box is a new control that provides the option to collapse a window so that only the title bar is showing. It replaces the WindowShade feature in System 7.5. You should include a Collapse box in all windows that your create using the document window panel. There may be extenuating circumstances that would compel you not to include a Collapse box, however, these cases should be rare.  
#### <span id="page-6-0"></span>Zoom Boxes 0  
In addition to the standard, zoom there are now two additional versions, a horizontal zoom box and a vertical zoom box. You decide whether to include the standard zoom box, or one of the new zoom boxes in your application's windows depending on the content that a user creates in the windows. The vertical zoom box allows windows to grow vertically when the user clicks the control. The horizontal zoom box allows windows to grow horizontally when the user clicks the control. The zoom boxes are shown in Figure 2 in the Apple Default Appearance.  
**Figure 2** Horizontal and vertical zoom boxes  
![](images/_page_6_Picture_4.jpeg)  
You can use the horizontal or vertical zoom box to reveal more content in a window if there isn't room for a disclosure triangle. For example, in the alarm clock, it's best to use a disclosure triangle to reveal the controls that change the clock's setting, but you could use a horizontal zoom box for this purpose. In general, people won't expect to find a control for progressive disclosure in a window title.  
#### Title Bar Icon 0  
The document window appearance for Mac OS 8 includes an icon in the title bar next to the title of the document. This icon is a proxy for the Finder icon and behaves in the same ways. For example, dragging the icon to a different location in the Finder moves the document to that location. Only items with Finder representations should include the icon in the title bar.  
#### Draggable Border 0  
Document windows now have dimensional borders on all sides so that users can drag a window from any side rather than just by the title bar. See [Figure 1](#page-5-0) for an example.  
Windows **7**  
#### <span id="page-7-0"></span>Placard 0  
You can include the standard placard in your window frame to provide status information. The placard appearance changes per theme so be sure to use the placard panel and don't create your own. The placard appearance is shown in Figure 3.  
![](images/_page_7_Picture_3.jpeg)  
#### Window Header 0  
If your window needs a header, there is now a standard appearance for it that is provided by the Mac OS 8 Toolbox. The basic design for the window header is shown in Figure 4.  
![](images/_page_7_Picture_6.jpeg)  
You can provide status information in the window header such as the Finder does for the columns in its windows.  
#### <span id="page-8-0"></span>Utility Windows 0  
Utility windows have an updated appearance in Mac OS 8. They have a drag region on the frame of the window indicated by the border design. Now users can drag a utility window by any side rather than just the title bar. Figure 5 shows utility windows in the active and inactive states.  
**Figure 5** Basic utility window design  
![](images/_page_8_Picture_4.jpeg)  
You can decide where to put the title bar. It can be on the top of the window or on one of the sides of the utility window. Figure 6 shows a utility window with the title bar across the top and a utility window with a title bar on the left side. You can also specify that the title bar appear on the right side.  
**Figure 6** Title bar placement for utility windows  
![](images/_page_8_Picture_7.jpeg)  
Windows **9**  
**Figure 7** Controls in utility windows  
<span id="page-9-0"></span>You can include a size box, a zoom box, a collapse box, and a close box in a utility window. Figure 7 shows various combinations of controls in the title bar of the utility window.  
**Active utility window with text and with all controls Active title bars with text** Title bars with close box, zoom box, and collapse box Title bars with close box and collapse box Title bars with close box **Active utility window without text and with all controls Active title bars without text**  
Title bars without controls