<!-- Chunk 244 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 834 -->
<span id="page-268-1"></span>An **icon button** behaves like a bevel button, but it does not have a visible rectangular edge around it. In other words, the entire button is clickable, not just the icon. Figure 15-10 shows the icon buttons in the System Preferences window.  
**Figure 15-10** Icon button examples  
![](images/_page_268_Picture_14.jpeg)  
#### Icon Button Usage  
Typically, icon buttons are used to display clickable icons in a toolbar (as described in["Window-Frame](#page-254-1) [Controls"](#page-254-1) (page 255), an icon button is one of three standard window-body controls you can use in a toolbar). If you want to use icon buttons in your toolbar, avoid mixing them with rectangular-style or capsule-style toolbar controls. Icon buttons should not be used in a bottom bar.  
An icon button can have a pop-up menu attached. See "Icon [Buttons](#page-287-0) and Bevel Buttons With Pop-Up [Menus"](#page-287-0) (page 288) for more information about this usage.  
#### Icon Button Contents and Labeling  
Icon buttons contain icons; in addition, they can display a text label that users can choose to view. Icon buttons can also contain a single downward-pointing arrow, which indicatesthe presence of a pop-up menu.  
<span id="page-269-1"></span>Icon button labels should name a thing (such as Network or Accounts) or describe an action (such as Mask or Show Art). Remember that users can choose to view the icon without the label, so make sure the meaning of the icon is clear and unambiguous. See ["Designing](#page-152-0) Iconsfor Icon Buttons" (page 153) for more information on designing attractive and useful toolbar icons.  
#### Icon Button Specifications  
**Control sizes**: The outer dimensions of an icon button are not visible, but they determine the hit target area. Typically, the outer dimensions of an icon button include a margin of about 10 pixels all the way around the icon and label.  
**Label spacing and fonts**: Use the small system font for the labels. The text should be below the icon as shown in Figure 15-11.  
<span id="page-269-0"></span>**Icon sizes**: Icons for icon buttons work best when they are between 24 x 24 pixels and 32 x 32 pixels in size. For example, the icon shown in Figure 15-11 is 32 x 32 pixels.  
**Figure 15-11** Example relationships of the icon, button, and hit-target dimensions in an icon button  
![](images/_page_269_Picture_13.jpeg)  
**Control spacing**: For buttons with a 24 x 24 pixel (or larger) icon, leave at least 8 pixels between button edges (not between icon edges), stacked vertically or aligned horizontally.  
#### Icon Button Implementation  
To create an icon button in Interface Builder, drag a bevel button or a square button into your window, add your icon, and deselect the Bordered checkbox in the Attributes pane of the inspector. To create one using Application Kit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSShadowlessSquareBezelStyle as the argument.  
You can also use Interface Builder to create an icon button that includes a pop-up menu. First, drag a pop-up button into your window then, in the Attributes pane of the inspector, change the type to Pull Down. Finally, in the same pane, change the style to either Bevel or Square (it doesn't matter which) and deselect the Bordered checkbox.