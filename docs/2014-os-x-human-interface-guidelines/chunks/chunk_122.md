<!-- Chunk 122 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 712 -->
A **segmented control** is a linear set of two or more segments, each of which functions as a button.  
![](images/_page_198_Picture_3.jpeg)  
**Important:** The segmented control described in this section is suitable for use in the window body only; it should not be used in the window-frame areas. For information about the segmented control that can be used in the toolbar (or bottom bar), see Some [Controls](#page-176-1) Can Be Used on the Window Frame (page 177).  
To define a segmented control in your code, use the NSSegmentedControl class.  
A segmented control:  
- Contains either images or text, but not a mixture of both
- Can behave as either a collection of radio buttons or checkboxes(that is,segmentselection can be mutually exclusive or inclusive)  
Use a segmented control to offer users a few closely related choices that affect a selected object, or to help users change views or panes in a window. (Note that a view-changer segmented control looks similar to a tab view control, but it doesn't behave the same; for more information about tab views, see Tab [View](#page-226-0) (page 227).)  
**Don't use a segmented control to enable addition or deletion of objects in a source list or split view.** If you need to provide a way for users to add and delete objects in a source list or other split view, use a gradient button (described in [Gradient](#page-183-0) Button (page 184)) in the window body. If you need to put an add-delete control in a bottom bar, use a toolbar control (described in Some [Controls](#page-176-1) Can Be Used on the Window Frame (page 177)).  
**Make the width of each segment the same.** If segments have different widths, users are likely to wonder if different segments have different behaviors or different degrees of importance.  
**Use a noun or short noun phrase for the text inside each segment.** The text you provide should describe a view or an object and use title-style capitalization (described in [Capitalizing](#page-46-0) Labels and Text (page 47)). A segmented control that contains text inside each segment probably doesn't need an introductory label.  
**As much as possible, use the system-provided images, instead of custom images, inside a segmented control.** If you need to design your own images, try to imitate the clarity and simple lines of the system-provided images. Forsome tips on how to create custom images of thistype,see [Toolbar](#page-323-0) Icons (page 324). To learn more about the system-provided images, see [System-Provided](#page-328-0) Icons (page 329).  
If you decide to design custom images for a segmented control, use the following sizes:  
● Regular size: 17 x 15 pixels.  
● Small: 14 x 13 pixels.  
● Mini: 12 x 11 pixels.  
If you choose to put images inside the segments of a segmented control, you can provide a text label below the control.