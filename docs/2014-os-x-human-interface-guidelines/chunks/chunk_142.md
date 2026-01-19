<!-- Chunk 142 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 713 -->
A **bevel button** is a multipurpose button designed for use in the window-body area.  
**Note:** Bevel buttons are not recommended for use in apps that run in OS X v10.7 and later. As an alternative, consider using a segmented control instead (described in [Segmented](#page-198-1) Control (page 199)).  
You can use bevel buttons singly (as a push button) or in groups (as a set of radio buttons or checkboxes). The Preview inspector window uses bevel buttons as push buttons that rotate and crop the current content.  
![](images/_page_229_Picture_6.jpeg)  
Bevel buttons are available in Interface Builder. To create one using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSRegularSquareBezelStyle as the argument. (To create a square-cornered bevel button, use NSShadowlessSquareBezelStyle as the argument for the setBezelStyle: method.)  
Bevel buttons can have square or rounded corners. They can display text, icons, or other images. Bevel buttons can also display a single downward-pointing arrow in addition to text or an image, which indicatesthe presence of a pop-up menu.  
Bevel buttons can behave like push buttons or can be grouped and used like radio buttons or checkboxes.  
You can use a square-cornered bevel button when space is limited or when adjoining a set of bevel buttons.  
If you use a bevel button as a push button, its label should be a verb or verb phrase that describes the action it performs. If you provide a set of bevel buttons to be used as radio buttons or checkboxes, you might label each with a noun that describes a setting or a value.  
If you choose to display an icon or image instead of a text label, be sure the meaning of the image is clear and unambiguous. It's recommended that you create an icon no larger than 32 x 32 pixels. Maintain a margin of between 5 and 15 pixels between the icon and the outer edges of the button. A button that contains both an icon and a label may need a margin around the edge that's closer to 15 pixels than to 5 pixels. Use label font (10-point Lucida Grande Regular) for text labels.  
#### **Rounded corners**  
![](images/_page_230_Picture_3.jpeg)  
![](images/_page_230_Picture_4.jpeg)  
![](images/_page_230_Picture_5.jpeg)  
Leave at least 5 pixels between edge of icon and edge of button.  
#### **Rounded corners with label below icon**  
![](images/_page_230_Picture_8.jpeg)  
![](images/_page_230_Picture_9.jpeg)  
![](images/_page_230_Picture_10.jpeg)  
Bevel button as a push button  
You can also use Interface Builder to add a pop-up menu to a bevel button. First, drag a pop-up button into your window then, in the Attributes pane of the inspector, change the type to Pull Down. Finally, in the same pane, change the style to Bevel (for a standard bevel button look) or Square (for a square-cornered bevel button look).