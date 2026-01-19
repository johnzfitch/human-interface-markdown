<!-- Chunk 277 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 567 -->
A **disclosure button** expands a dialog or panel to offer the user a wider range of choices related to a specific selection control, such as a pop-up menu, combination box, or command pop-down menu. For example, the minimal Save dialog (shown in [Figure](#page-246-0) 14-57 (page 247)) uses a pop-up menu to provide the user with a list of standard and recently accessed locations in which to save a file. To get a wider range of choices, the user clicksthe disclosure button, which putsthe file system at the user'sfingertips without requiring the user to leave the context of the Save dialog. An example of the expanded Save dialog is shown in Figure 15-78.  
View Controls **331**  
<span id="page-331-0"></span>**Figure 15-78** A disclosure button expands a Save dialog  
![](images/_page_331_Picture_3.jpeg)  
#### Disclosure Button Usage  
Use a disclosure button when you need to provide additional options that are closely related to a specific list of choices. If you need to display additional information or functionality related to the contents of a window or a section of a window, or if you need a way to reveal subordinate items in a hierarchical list, use a disclosure triangle instead. See ["Disclosure](#page-328-1) Triangles" (page 329) for more information on this control.  
#### Disclosure Button Contents and Labeling  
Because a disclosure button is closely associated with a control, it does not need a label. By default, disclosure buttons should be in the closed position, that is, pointing down. When the user clicks a disclosure button, the window expands and the disclosure button changes to point up.  
#### <span id="page-331-1"></span>Disclosure Button Specifications  
**Control sizes**: A disclosure button should be aligned with the pop-up menu or other list-based selection control (such as a command pop-down menu) it affects. In addition, the disclosure button should be close enough to the associated control to clearly indicate a relationship between them.  
#### Disclosure Button Implementation  
Disclosure buttons are available in Interface Builder. To create one using Application Kit programming interfaces, use NSButton and set the bezel style to NSRoundedDisclosureBezelStyle and the button type to NSPushOnPushOffButton.