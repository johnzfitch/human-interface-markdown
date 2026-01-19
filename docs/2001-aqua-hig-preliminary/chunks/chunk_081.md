<!-- Chunk 81 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 821 -->
A **push button** is a rounded rectangle with a text label on it. Clicking a push button performs an instantaneous action, such as saving a document, completing operations defined by a dialog, or acknowledging an error message. Button names should be verbs that describe the action performed—Save, Close, Print, Delete, and so on. Don't use push buttons to indicate a state such as On or Off.  
In some circumstances, it's appropriate to implement an Apply button—for example, to permit a user to see the effect of multiple text attributes before committing to them. In cases like these, clicking Cancel should undo any of the applied changes. Be cautious about using an Apply button for operations that take a long time to implement or undo; it might not be obvious to users that they can interrupt or reverse the process.  
<span id="page-89-3"></span><span id="page-89-2"></span>**Figure 7-1** Example of standard push buttons  
**Standard push button:** The button width is 69 pixels.  
![](images/_page_89_Picture_9.jpeg)  
#### <span id="page-90-0"></span>Push Button Specifications  
- **Height:** 20 pixels (fixed)
- **End caps:** 14 pixels wide (fixed)
- **Width:** Depends on button text. If you don't specify a wide enough button, the end caps clip the text. The standard width for OK and Cancel buttons is 69 pixels, as shown in [Figure 7-1.](#page-89-3) Push buttons used in other contexts may be sized differently if appropriate.
- **Text:** System font (13-point Lucida Grande). If you need to use a font larger than the system font, use a bevel button instead.
- **Color:** All push buttons are clear except the default button—the button selected by pressing the Return key—which uses the default color (in addition to pulsing). For example, in a dialog containing a default OK button and a Cancel button, the Cancel button is clear and the OK button uses color and pulses. When the user presses a nondefault button such as Cancel, the button acquires color and the default button loses its color. If you use standard controls, this behavior is automatic.
- **Spacing:** Leave at least 12 pixels of space between buttons placed horizontally or stacked.
- **Positioning:** The default button should go in the lower-right corner of the dialog. If there's a Cancel button, it should be to the left of the default button. If there's a third, or alternate, button (Don't Save, for example), it should go to the left of the Cancel button. Leave more than 12 pixels between the alternate button and Cancel; you may want to align the left edge of the button with the main dialog text, or put it 12 pixels to the right of the Help button, if there is one.  
<span id="page-90-1"></span>**Figure 7-2** Push button specifications  
**Push button:** The button height is 20 pixels.  
Parts of control not adjustable  
Text added to middle  
**Small push button:** The button height is 17 pixels.  
![](images/_page_90_Picture_16.jpeg)  
Nonadjustable end caps should be 10 pixels.  
<span id="page-91-2"></span>**Figure 7-3** Stacked push buttons  
![](images/_page_91_Picture_3.jpeg)  
If stacking vertically, leave a minimum of 12 pixels in between.  
![](images/_page_91_Picture_5.jpeg)  
<span id="page-91-3"></span>If stacking vertically, leave a minimum of 8 pixels in between.