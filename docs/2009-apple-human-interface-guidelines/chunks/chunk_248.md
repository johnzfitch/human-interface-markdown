<!-- Chunk 248 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1249 -->
<span id="page-276-1"></span>A **bevel button** is a multipurpose button designed for use in the window-body area. You can use bevel buttons singly (as a push button) or in groups (as a set of radio buttons or checkboxes). Figure 15-17 shows bevel buttons used as push buttons in the Preview inspector window.  
**Figure 15-17** Bevel buttons in an inspector window  
![](images/_page_276_Picture_7.jpeg)  
Bevel buttons can have square or rounded corners. The square-cornered variation can be used when space is limited or when adjoining a set of bevel buttons. You may notice, however, that bevel buttons are not very frequently used in applications running in Mac OS X v10.4 and later. This is due in part to user interface style changes and in part to alternative controls that became available. You can still use bevel buttons if they provide exactly the look you need, but you should consider alternatives, such as gradient buttons and segmented controls (described in ["Gradient](#page-272-0) Buttons" (page 273) and ["Segmented](#page-285-0) Controls" (page 286), respectively).  
#### Bevel Button Usage  
Bevel buttons can behave like push buttons or can be grouped and used like radio buttons or checkboxes. For example, you could use bevel buttons to graphically represent text-alignment options.  
Use bevel buttons in the window body. If you need a similarly versatile button for use in the window-frame areas, consider using a rectangular-style toolbar button (described in ["Controls](#page-256-0) for Toolbars and Bottom [Bars"](#page-256-0) (page 257)).  
#### Bevel Button Contents and Labeling  
Bevel buttons are very versatile and can display text, icons, or other images. Bevel buttons can also display a single downward-pointing arrow in addition to text or an image, which indicates the presence of a pop-up menu. See "Icon Buttons and Bevel [Buttons](#page-287-0) With Pop-Up Menus" (page 288) for more information about this usage.  
If you choose to display an icon or image instead of a text label, be sure the meaning of the image is clear and unambiguous (see ["Cultural](#page-46-2) Values" (page 47) for some advice on choosing appropriate imagery). Interface Builder provides several built-in images you can use on a bevel button; see ["System-Provided](#page-154-0) [Images"](#page-154-0) (page 155) for more information about system-provided images.  
You can also combine an icon (or image) and a text label on a bevel button. You can place the text anywhere on the button in relation to the icon (you specify the location in Interface Builder or programmatically). Use label font (10-point Lucida Grande Regular) for text labels.  
If you use a bevel button as a push button, its label should be a verb or verb phrase that describes the action it performs. If you provide a set of bevel buttons to be used as radio buttons or checkboxes, you might label each with a noun that describes a setting or a value.  
#### Bevel Button Specifications  
**Control sizes**: The dimensions of bevel buttons vary; 20 x 20 pixels is the recommended size for use in a tool panel (see ["Panels"](#page-226-0) (page 227) for more information on panels).  
**Icon sizes**: 32 x 32 pixels is the largest recommended icon size. Maintain a margin of between 5 and 15 pixels between the icon and the outer edges of the button. A button that contains an icon and label combined may need a margin around the edge that's closer to 15 pixels than to 5 pixels.  
<span id="page-277-0"></span>**Control spacing**: For bevel buttons with rounded corners that contain a 24 x 24 pixel (or larger) icon, leave at least 8 pixels between buttons, stacked vertically or aligned horizontally. Otherwise, buttons should butt up against each other.  
Figure 15-18 shows some examples of these configurations.  
**Figure 15-18** Bevel button examples  
#### **Rounded corners**  
![](images/_page_277_Picture_14.jpeg)  
![](images/_page_277_Picture_15.jpeg)  
![](images/_page_277_Picture_16.jpeg)  
Leave at least 5 pixels between edge of icon and edge of button.  
#### **Rounded corners with label below icon**  
![](images/_page_277_Picture_19.jpeg)  
![](images/_page_277_Picture_20.jpeg)  
![](images/_page_277_Picture_21.jpeg)  
Bevel button as a push button  
#### Bevel Button Implementation  
<span id="page-278-2"></span>Bevel buttons are available in Interface Builder. To create one using Application Kit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSRegularSquareBezelStyle asthe argument. To create a square-cornered bevel button, use NSShadowlessSquareBezelStyle as the argument for the setBezelStyle: method.  
You can also use Interface Builder to add a pop-up menu to a bevel button. First, drag a pop-up button into your window then, in the Attributes pane of the inspector, change the type to Pull Down. Finally, in the same pane, change the style to Bevel (for a standard bevel button look) or Square (for a square-cornered bevel button look).