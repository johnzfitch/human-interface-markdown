<!-- Chunk 246 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 1252 -->
A **push button** performs an instantaneous action, such as saving a document, completing operations defined by a dialog, or acknowledging an error message. Push buttons are designed for use in the window body only, not in the window-frame areas (for more information about these window parts, see "Window [Elements"](#page-195-0) (page 196)). Figure 15-7 shows several different usages of the push button.  
<span id="page-269-0"></span>**Figure 15-7** Examples of push buttons in different types of windows  
![](images/_page_269_Picture_3.jpeg)  
#### Push Button Usage  
Because users expect an immediate action to occur when they press a push button, it is important to avoid using push buttons to merely display information or to mimic the behavior of other controls. In particular:  
- Do not use a push button to indicate a state, such as on or off. Instead, you can use checkboxes to indicate state, as described in ["Checkboxes"](#page-285-0) (page 286).
- Do not use a push button as a label. Instead, use static text to label elements and provide information in the interface (for more information, see ["Static](#page-324-1) Text" (page 325)).
- Avoid associating a menu with a push button. If you need to associate a menu with a button, use a bevel button instead (see "Bevel [Buttons"](#page-279-0) (page 280) to learn how to do this).  
#### Push Button Contents and Labeling  
A push button always contains text, it does not contain an image. If you need to display an icon or other image on a button, use instead a bevel button, described in "Bevel [Buttons"](#page-279-0) (page 280).  
The label on a push button should be a verb or verb phrase that describes the action it performs—Save, Close, Print, Delete, Change Password, and so on. If a push button acts on a single setting, label the button as specifically as possible; "Choose Picture…," for example, is more helpful than "Choose…" Because buttons initiate an immediate action, it shouldn't be necessary to use "now" (Scan Now, for example) in the label.  
Push button labels should have title-style capitalization, as described in ["Capitalization](#page-135-0) of Interface [Element](#page-135-0) Labels and Text" (page 136). If the push button immediately opens another window, dialog, or application to perform its action, you can use an ellipsis in the label. For example, Mail preferences displays a push button that includes an ellipsis because it opens .Mac system preferences, as shown in Figure 15-8.  
<span id="page-270-0"></span>**Figure 15-8** A push button label can include an ellipsis  
![](images/_page_270_Picture_7.jpeg)  
<span id="page-270-1"></span>All push buttons should be clear in appearance, that is, without color, except the default button. The default button is the button that performs a safe action in a dialog and is activated when the user presses Return or Enter(for more information about the default button, see ["Dismissing](#page-243-0) Dialogs" (page 244)). When the user presses a nondefault button, such as Cancel, that button acquires color and the default button loses its color. If you use system-provided push buttons, this behavior is automatic.  
#### Push Button Specifications  
**Control sizes**: Push buttons are available in regular, small, and mini sizes. The height of a push button is fixed for each size, but you specify the width, depending on the length of the label text you supply. If you don't specify a wide enough button, the end caps clip the text. Note that the standard width for OK and Cancel buttons is 68 pixels.  
<span id="page-271-1"></span>**Figure 15-9** OK and Cancel buttons  
![](images/_page_271_Picture_5.jpeg)  
**Label spacing and fonts**: Push button label text should not have a shadow or any other effects on it, and it should be in the system font appropriate for the button size (these fonts are automatically supplied by Interface Builder):  
- Regular size: System font.
- Small: Small system font.
- Mini: Mini system font.  
**Control spacing**: Push buttons should be placed far enough from each other to allow the user to click a specific one easily. In particular, note that a push button that could lead to a potentially dangerous or destructive action (such as Delete) should be farther away from safe buttons than the distances recommended in this section (see ["Dismissing](#page-243-0) Dialogs" (page 244) for more information).  
- Regular size: Leave at least 12 pixels of space between buttons aligned horizontally or stacked vertically.
- Small: Leave at least 10 pixels of space between buttons aligned horizontally or stacked vertically.
- Mini: Leave at least 8 pixels of space between buttons aligned horizontally or stacked vertically.  
#### Push Button Implementation  
<span id="page-271-2"></span><span id="page-271-0"></span>Push buttons are available in Interface Builder. To create one using Application Kit programming interfaces, create an NSButton object of type NSMomentaryPushInButton or NSMomentaryLightButton.