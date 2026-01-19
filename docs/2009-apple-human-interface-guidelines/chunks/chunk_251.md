<!-- Chunk 251 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1068 -->
<span id="page-279-2"></span>A group of **radio buttons** provides users with a set of mutually exclusive, but related, choices. For example, Security preferences uses radio buttons to allow users to choose which connections can get through the firewall, as shown in Figure 15-20.  
**Figure 15-20** Radio buttons offer mutually exclusive choices  
![](images/_page_279_Picture_11.jpeg)  
#### Radio Button Usage  
Use a group of radio buttons when you need to display a set of choices from which the user can choose only one. If you need to display a set of choices from which the user can choose more than one at the same time, use checkboxesinstead. Also, if you need to display a single setting,state, or choice the user can either accept or reject, don't use a single radio button; instead you can use a checkbox. To learn more about checkboxes, see ["Checkboxes"](#page-282-0) (page 283).  
A group of radio buttons should contain at least two items and a maximum of about five. If you need to display more than five items, consider using a pop-up menu (described in ["Pop-Up](#page-288-0) Menus" (page 289)).  
<span id="page-280-0"></span>A radio button should never initiate an action, although the choice of a radio button can change the state of the application. For example, Speech preferences allowsthe user to choose between two listening methods, asshown in Figure 15-21. If the user choosesthe second listening method ("Listen continuously with keyword"), the keyword setup preferences are automatically enabled.  
**Figure 15-21** A radio button can change the state of an application  
![](images/_page_280_Picture_7.jpeg)  
#### Radio Button Contents and Labeling  
The selected and unselected appearances of a radio button are provided automatically; you cannot display any text or images in a radio button.  
Radio buttons should be accompanied by text labels that describe the choice associated with each button. These labels should have sentence-style capitalization, as described in ["Capitalization](#page-135-0) of Interface Element [Labels](#page-135-0) and Text" (page 136).  
A set of radio buttons is never dynamic; that is, the contents and labels shouldn't change depending on the context.  
#### Radio Button Specifications  
**Control sizes**: The dimensions of the radio button itself are fixed for each size, but you determine the length of the label that introduces the group and the length of each radio button label.  
**Label spacing and fonts**: Radio button text (both the introductory label and control label) should be in a font that is proportional to the size of the control. The following fonts are supplied automatically by Interface Builder:  
- Regular size: System font.
- Small: Small system font.
- Mini: Mini system font.  
Use the following metrics to position the introductory labels correctly:  
- Regular size: 8 pixels from the end of the label (the colon) to the control.
- <span id="page-281-1"></span>● Small: 6 pixels from the end of the label (the colon) to the control.
- Mini: 5 pixels from the end of the label (the colon) to the control.  
**Control spacing**: Radio buttons can be arranged vertically or horizontally, depending on the overall layout of your window or dialog. Typically, however, radio buttons are stacked vertically to emphasize the mutually exclusive relationship among the buttons.  
If you position a group of radio buttons horizontally, measure the space needed to accommodate the longest radio button label. Use that measurement to make the space between each pair of radio buttons consistent.  
Use the following metrics when you position radio buttons vertically:  
- Regular size: 6 pixels between controls.
- Small: 6 pixels between controls.
- <span id="page-281-0"></span>● Mini: 5 pixels between controls.  
For radio buttons stacked vertically or horizontally, be sure to align the baseline of the introductory label with the baseline of the first button's label, as shown in Figure 15-22.  
**Figure 15-22** Radio button label alignment  
![](images/_page_281_Figure_20.jpeg)  
#### Radio Button Implementation  
Radio buttons are available in Interface Builder. To create one using Application Kit programming interfaces, create an NSButton object with type NSRadioButton.