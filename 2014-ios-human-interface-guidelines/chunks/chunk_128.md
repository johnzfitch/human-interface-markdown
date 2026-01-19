<!-- Chunk 128 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 427 -->
A **segmented control** is a linearset ofsegments, each of which functions as a button that can display a different view.  
![](images/_page_190_Picture_5.jpeg)  
**APINote:** To learn more about defining a segmented control in your code,see "Segmented Controls".  
#### A segmented control:  
- Consists of two or more segments whose widths are proportional, based on the total number ofsegments
- Can display text or images  
Use a segmented control to offer choices that are closely related but mutually exclusive.  
**Make sure that each segment is easy to tap.** To maintain a comfortable hit region of 44 x 44 points for each segment, limit the number of segments. On iPhone, a segmented control should have five or fewer segments.  
**As much as possible, make the size of each segment's contents consistent.** Because all segments in a segmented control have equal width, it doesn't look good if the content fills some segments, but not others.  
**Avoid mixing text and images in a single segmented control.** A segmented control can contain text or images. An individual segment can contain either text or an image, but not both. In general, it's best to avoid putting text in some segments and images in other segments of a single segmented control.  
**If necessary, adjust the positioning of content in a customized segmented control.** If you customize the background appearance of a segmented control, make sure that the automatic centering of the control's content still looks good. Use the bar metrics APIs to adjust the positioning of the content inside a segmented control (to learn more about specifying bar metrics, see the appearance-customization APIs described in UISegmentedControl).