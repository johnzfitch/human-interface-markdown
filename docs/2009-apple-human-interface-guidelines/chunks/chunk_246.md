<!-- Chunk 246 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 754 -->
A **gradient button** performs an instantaneous action related to a view, such as a source list. For example, in Keyboard & Mouse preferences (shown in Figure 15-14), gradient buttons allow the user to add and remove keyboard shortcuts for specific applications.  
<span id="page-273-0"></span>**Figure 15-14** Gradient buttons used to add and remove items in a list  
![](images/_page_273_Picture_3.jpeg)  
#### Gradient Button Usage  
Use a gradient button when you need to offer functionality that is directly related to a source list or other view, such as a column view. Gradient buttons can have push-button, toggle, and pop-up menu behavior. For example, Mail uses gradient buttons at the bottom of the sidebar to offer New Mailbox, Show/Hide Mail Activity, and Action menu functionality, as shown in Figure 15-15.  
<span id="page-274-0"></span>**Figure 15-15** Gradient buttons can behave in different ways  
![](images/_page_274_Figure_3.jpeg)  
Gradient buttons with toggle and pop-up menu behavior  
Gradient buttons do not belong in the window-frame areas. If you need to offer an Action menu or other functionality in a bottom bar, use a rectangular-style toolbar control instead (see ["Rectangular-Style](#page-256-0) Toolbar [Controls"](#page-256-0) (page 257) for more information).  
#### Gradient Button Contents and Labeling  
Gradient buttons should contain images; they should not contain text. Because the function of a gradient button is closely tied to the view with which it's associated, there's little need to describe its action using a label.  
When possible, you should use the system-provided images, such as the Action menu image and the Add image, because their meaning is familiar to users. You should create a custom image only when none of the system-provided images is suitable. See ["System-Provided](#page-154-0) Images" (page 155) for more information on the system-provided images available to you. If you decide to create your own icons to use in a gradient button, see "Designing Icons for [Rectangular-Style](#page-153-1) Toolbar Controls" (page 154) for some guidelines on how to do this.  
#### Gradient Button Specifications  
**Control sizes**: Gradient buttons are available in regular size only.  
**Control spacing**: Although you can use a single gradient button by itself, it is more common for multiple gradient buttons to be displayed in a row. If you display more than one gradient button in a row, such as below a source list or other view, the buttonsshould abut each other. If the gradient buttons are not attached to a source list or other view within a window, leave 12 pixels between the bottom edge of the source list (or other view) and the gradient buttons associated with it.  
#### Gradient Button Implementation  
<span id="page-275-0"></span>Gradient buttons are available in Interface Builder. To create one using Application Kit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSSmallSquareBezelStyle as the argument.