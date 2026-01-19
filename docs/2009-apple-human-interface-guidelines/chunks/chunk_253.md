<!-- Chunk 253 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1162 -->
A **segmented control** is divided into two or more segments and behaves as a collection of radio buttons or checkboxes. Like a push button, a segmented control initiates an immediate action—that is, when the user clicks one of the segments, something should happen.  
Mac OS X offers different styles of segmented controls for use in different window areas. The segmented control described in this section is suitable for use in the window body; it should not be used in the window-frame areas. For information on styles of segmented controls that are available for use in the window-frame areas(the toolbar and the bottom bar),see ["Window-Frame](#page-254-1) Controls" (page 255). Figure 15-26 shows an example of segmented controls in a window-body area.  
<span id="page-285-1"></span>**Figure 15-26** Segmented controls can be used as radio buttons  
![](images/_page_285_Picture_8.jpeg)  
#### Segmented Control Usage  
Use a segmented control when you want to offer the user a few closely related choices that affect a selected object. You can also use a segmented control to change views or panes in a window. Note that although a segmented control used as a view-changer looks similar to a tab view control, it does not behave the same: A segmented control is not attached to the panes, whereas a tab view control is attached to them. See ["Tab](#page-337-0) [Views"](#page-337-0) (page 338) for more information about tab views.  
If you need to provide a way for users to add and delete objects in a source list or other split view, don't use a segmented control that contains the plus and minus symbols. Instead, if you need to put an add-delete control in a bottom bar, use a rectangular-style toolbar control (described in ["Controls](#page-256-0) for Toolbars and [Bottom](#page-256-0) Bars" (page 257)). If you need to put an add-delete control in the window body, use a gradient button  
(described in ["Gradient](#page-272-0) Buttons" (page 273)). Also, you don't need to create the plus and minusiconsfor these controls, because Mac OS X v10.5 and later provides these and many other icons for your use (see ["System-Provided](#page-154-0) Images" (page 155) for more information).  
#### Segmented Control Contents and Labeling  
A segmented control can contain either icons or text, but not a mixture of both. However, when the control contains icons, you can place a text label below the control.  
For the text in each segment, or the label below it, use a noun (or short noun phrase) that describes a view or an object, and use title-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and Text" (page 136) for more on this style).  
If you choose to use icons in a segmented control, be sure to consider using the images that are available in Mac OS X v10.5 and later (see ["System-Provided](#page-154-0) Images" (page 155) for more information on these). If you need to design your own images, try to imitate the clarity and simple lines of the system-provided images. Forsome tips on how to create custom images of thistype,see "Designing Iconsfor [Rectangular-Style](#page-153-1) Toolbar [Controls"](#page-153-1) (page 154).  
#### Segmented Control Specifications  
**Control sizes**: The height of a segmented control is fixed for each size, but you determine the width of the control. Be sure to make the width of each segment the same, because a segment of a different width might imply that it has different behavior or is of greater or lesser importance than the others.  
**Label spacing and fonts**: The text in a segmented control and the label text is proportional to the size of the control (Interface Builder automatically supplies the appropriate font for the text within the control):  
- Regular size: System font for text within the control and for label text below it.
- Small: Small system font for text within the control and for label text below it.
- <span id="page-286-1"></span>● Mini: Mini system font for text within the control and for label text below it.  
**Icon sizes**: If you need to design an icon for each segment, you should constrain the icon to the following dimensions:  
- Regular size: 17 x 15 pixels.
- <span id="page-286-0"></span>● Small: 14 x 13 pixels.
- Mini: 12 x 11 pixels.  
**Figure 15-27** Segmented controls can contain icons or text  
#### **Regular-size segmented control**  
![](images/_page_286_Picture_19.jpeg)  
Selection Controls **287**  
#### Segmented Control Implementation  
The segmented control is available in Interface Builder. To create one using Application Kit programming interfaces, use the NSSegmentedControl class.