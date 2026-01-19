<!-- Chunk 263 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 348 -->
**Control sizes**: The height of a segmented control is fixed for each size, but you determine the width of the control. Be sure to make the width of each segment the same, because a segment of a different width might imply that it has different behavior or is of greater or lesser importance than the others.  
**Label spacing and fonts**: The text in a segmented control and the label text is proportional to the size of the control (Interface Builder automatically supplies the appropriate font for the text within the control):  
- Regular size: System font for text within the control and for label text below it.
- Small: Small system font for text within the control and for label text below it.
- <span id="page-289-1"></span>■ Mini: Mini system font for text within the control and for label text below it.  
**Icon sizes**: If you need to design an icon for each segment, you should constrain the icon to the following dimensions:  
<span id="page-289-0"></span>■ Regular size: 17 x 15 pixels.  
■ Small: 14 x 13 pixels. ■ Mini: 12 x 11 pixels.  
**Figure 15-27** Segmented controls can contain icons or text  
#### **Regular-size segmented control**  
![](images/_page_289_Picture_17.jpeg)  
#### Segmented Control Implementation  
The segmented control is available in Interface Builder. To create one using Application Kit programming interfaces, use the NSSegmentedControl class.