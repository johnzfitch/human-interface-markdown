<!-- Chunk 284 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 1204 -->
A **text input field**, also called an editable text field, is a rectangular area in which the user enters text or modifies existing text. The text input field can be active or disabled. It supports keyboard focus and password entry. For example, iTunes preferences allows the user to specify a library name for sharing, as shown in Figure 15-70.  
<span id="page-326-0"></span>**Figure 15-70** A text input field allows the user to supply information  
![](images/_page_326_Picture_3.jpeg)  
Be sure to use a combination box control when you want a text input field combined with a menu or list of choices; don't try to create one by putting a text input field and a menu together. See ["Combination](#page-297-0) Boxes" (page 298) for more information about combination boxes.  
#### Text Input Field Usage  
Use a text input field when you need to get information from the user. When you receive user input, be sure to perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, an application should issue an alert if the user types characters other than digits. In most cases, the appropriate time to check the data in the field is when the user clicks outside the field or presses the Return, Enter, or Tab key.  
#### Text Input Field Contents and Labeling  
A text input field contains user-supplied text in a system font that is appropriate for the size of the control. In addition, a text input field can contain a token field control, which displays the user input in the form of a draggable token (see ["Token](#page-328-0) Fields" (page 329) for more information on tokens).  
It's a good idea to display an introductory label with a text input field to help users understand what type of information they should enter. Generally, these labels should have title-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and Text" (page 136) for more information on this style).  
Text Controls **327 2008-01-15 | © 1992, 2001-2003, 2008 Apple Inc. All Rights Reserved.**  
#### Text Input Field Specifications  
**Control sizes**: Text input fields are available in regular, small, and mini sizes. The height is fixed for each size, but you decide how long to make the control. In general, try to ensure that the length of the text input field comfortably accommodates the average length of the expected input. In addition, ifyou display multiple text input fields in awindow, be sure theyall have the same length. The height of each size of text input field is listed below (Figure 15-71 shows a regular-size text input field in different states):  
■ Regular size: 22 pixels high.  
<span id="page-327-0"></span>■ Small: 19 pixels high. ■ Mini: 15 pixels high.  
**Figure 15-71** A regular-size text input field in various states  
![](images/_page_327_Picture_7.jpeg)  
**Label spacing and fonts**: The introductory label for a text input field should be in a font that is proportional to the size of the control. In addition, the space between the introductory label and the input field should be consistent. Use the following metrics when you use a text input field in your window layout:  
- Regular size: Use system font for the introductory label. Leave 8 pixels between the end of the introductory label (the colon) and the left edge of the text input field.
- Small: Use small system font for the introductory label. Leave 6 pixels between the end of the introductory label (the colon) and the left edge of the text input field.
- Mini: Use mini system font for the introductory label. Leave 5 pixels between the end of the introductory label (the colon) and the left edge of the text input field.  
For more information about highlighting selections in text fields, see ["Keyboard](#page-108-0) Focus and [Navigation"](#page-108-0) (page 109) and ["Selections](#page-113-0) in Text" (page 114).  
**Control spacing**: If you want to use more than one text input field in a window, you need to leave enough space between them so users can easily see which input field belongs with each introductory label. If you need to position more than one text input field at the same height (that is, in a horizontal line), be sure to leave plenty of space between the end of one text field and the introductory label of the next. Typically, however, multiple text input fields are stacked vertically, as in a form users fill out. When you position text input fields in a vertical stack, be sure to leave the following amounts of space between them:  
■ Regular size: At least 10 pixels.  
■ Small: At least 8 pixels.  
■ Mini: At least 8 pixels.  
#### Text Input Field Implementation  
Text input fields are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSTextField class.