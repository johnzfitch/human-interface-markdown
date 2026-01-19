<!-- Chunk 294 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 208 -->
A **segmented control** is divided into two or more segments and behaves as a collection of radio buttons (or checkboxes). It is used to change the mode or view of your application or parent window.  
- A segmented control may contain icons or text but not both.
- When the control contains icons, you may place a text label below the control.
- Segmented controls may be used in regular or brushed metal windows.
- Like a push button, the segmented control should initiate an immediate action. When the user presses one of the segments, something should happen.  
**Carbon:** The segmented control is available in Interface Builder. Create it programmatically with the function HISegmentedViewCreate.  
**Cocoa:** The segmented control is available in Interface Builder. Create it programmatically using the NSSegmentedControl class.