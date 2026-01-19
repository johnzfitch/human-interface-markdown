<!-- Chunk 152 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 524 -->
<span id="page-148-2"></span>Keep these guidelines in mind when designing dialogs and windows:  
- <span id="page-148-3"></span>■ In general, try for a more centered approach to dialog layout, as opposed to the strongly left-biased approach of the traditional Mac OS 9 dialog. Most of the sample layouts in this document illustrate the center-biased approach.
- All spacing between dialog elements involves a multiple of 2 pixels—2, 4, 6, 8, and so on.  
- Maintain a 20-pixel space between the left and right edge of the window and any controls. Keep 20 pixels of space between the bottom edge and any controls; this can include the shadow of any push buttons in that area. Top spacing is determined by which controls are placed closest to the top of the dialog. For example, Figure 8-6 (page 156) uses a radio button as the topmost control, so the spacing is set to 14 pixels. In contrast, [Figure 8-7 \(page 157\)](#page-156-1) uses a tab control as the topmost element, so the spacing is set to 12 pixels.
- For dialogs that contain a mix of controls, set 16 pixels of vertical space between groups of controls. Vertical spacing between controls is determined by the tallest control in the row.
- Groups of controls should be separated by 20 pixels of vertical spacing and subgroups of controls within groups should be separated by 16 pixels.
- The default button for dismissing a dialog should go in the lower-right corner. If there's a Cancel button, it should be to the left of the default button.  
If there's a third button for dismissing the dialog, it should go to the left of the Cancel button. If the third button could result in data loss—Don't Save, for example—position it at least 12 pixels away from the "safe" buttons (Cancel and Save, for example).  
<span id="page-149-0"></span>A button that affects the contents of the dialog itself, such as Reset, should have its left edge aligned with the main dialog text or 12 pixels to the right of the help button (if there is one).  
**Figure 8-1** Position of buttons at the bottom of a dialog  
![](images/_page_149_Figure_9.jpeg)