<!-- Chunk 145 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 4258 -->
A **push button** performs an app-specific action.  
![](images/_page_243_Picture_7.jpeg)  
Push buttons are designed for use in the window body only, not in the window-frame areas. To learn about the controls that you can use in a toolbar or bottom bar, see ["Window-Frame](#page-240-0) Controls" (page 241).  
<span id="page-243-2"></span>Push buttons are available in Interface Builder. To create one programmatically, create an NSButton object of type NSMomentaryPushInButton or NSMomentaryLightButton. Note that the NSTexturedRoundedBezelStyle style of NSButton is designed for use in the window frame.  
#### Appearance and Behavior  
A push button always contains text, it does not contain an image.  
All push buttons are clear in appearance, that is, without color, except the default button in a dialog. (The default button performs a safe action and is activated when users press Return or Enter; for more information, see ["Dismissing](#page-218-0) Dialogs" (page 219)). You can see the two different button colorsin the standard OK and Cancel buttons.  
![](images/_page_244_Picture_2.jpeg)  
When the user clicks a nondefault button, such as Cancel, that button acquires color and the default button loses its color. This behavior is automatically implemented by the system-provided push buttons.  
#### Guidelines  
Use a push button in the window body to perform an instantaneous action, such as Print or Delete. A push button can also open another window to complete its operation.  
**Avoid using a push button to mimic the behavior of other controls.** Users expect an immediate action to occur when they click a push button, including the opening of another window or the dismissal of a dialog. In particular:  
- Do not use a push button to indicate a state, such as on or off. Instead, you can use checkboxes to indicate state, as described in ["Checkbox"](#page-256-0) (page 257).
- Do not use a push button as a label. Instead, use static text to label elements and provide information in the interface (for more information, see ["Static](#page-282-1) Text Field" (page 283)).
- Avoid associating a menu with a push button.  
**Provide enough space between buttons so that users can click a specific one easily.** In particular, if a push button can lead to a potentially dangerous or destructive action (such as Delete), it should be far enough away from safe buttons so that users are unlikely to click it accidentally.  
**Avoid displaying an icon in a button.** A push button should contain text that describes the action it performs.  
**Use a verb or verb phrase for the title of a push button.**The title you create should describe the action the button performs—Save, Close, Print, Delete, Change Password, and so on. If a push button acts on a single setting or entity, name the button as specifically as possible; "Choose Picture…," for example, is more helpful than "Choose…" Because buttons initiate an immediate action, it shouldn't be necessary to use "now" (Scan Now, for example) in the button title.  
**Use title-style capitalization for the button title and add an ellipsis if necessary.** To learn more about title-style capitalization, see ["Capitalizing](#page-305-0) Labels and Text" (page 306).  
If the push button immediately opens another window, dialog, or app to perform its action, use an ellipsis in the title. An ellipsis prepares users to expect another window to open in which they complete the action the button initiates. For example, Print & Scan preferences uses ellipsis characters in the names of buttons that open the print queue window and show information about the printer's options and supplies.  
![](images/_page_245_Picture_2.jpeg)  
**Be sure to resize a button's width to accommodate the title.** If you don't make a button wide enough, the end caps clip the text. Note that the height of a push button is fixed for each size.  
**In general, avoid supplying a static text label to introduce a push button.** You should be able to avoid an introductory label by clearly describing the push button action in the button title.  
#### <span id="page-246-0"></span>Icon Button  
An **icon button**, or freestanding icon, performs an app-specific action, often in a toolbar. For example, System Preferences uses icon buttons to represent its preferences panes.  
![](images/_page_246_Picture_3.jpeg)  
You can use an icon button in a toolbar or in the window body. (Icon buttons are not suitable for use in a bottom bar.)  
To create an icon button in Interface Builder, drag a bevel button or a square button into your window, add your icon, and deselect the Bordered checkbox in the Attributes pane of the inspector. To create one using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSShadowlessSquareBezelStyle as the argument.  
#### Appearance and Behavior  
An icon button does not have a visible rectangular edge around it. In other words, the entire button is clickable, not just the icon.  
An icon button can have a pop-up menu attached to it, which is indicated by the presence of a single downward-pointing arrow. For more information about this usage,see "Icon Button or Bevel Button [Containing](#page-259-0) a [Pop-Up](#page-259-0) Menu" (page 260).  
#### Guidelines  
Use an icon button to perform an app-specific action in either the toolbar or the window body. You can also use an icon button to provide mode-switching functionality in a preferences window toolbar.  
**Avoid mixing icon buttons with toolbar controls in a toolbar.** Toolbars look best, and are easiest for users to understand, when they contain controls of the same type.  
**Make sure the meaning of an icon button is clear and unambiguous.** Because users might view the icon without its label, it's especially important to choose an icon that accurately communicates its meaning. For tips on designing attractive and expressive toolbar icons, see ["Designing](#page-121-0) Toolbar Icons" (page 122).  
**Create a label that names a thing or describes an action; also, use title-style capitalization.** An icon button that functions as a pane-switchershould name a thing,such as Network or Accounts. If an icon button performs an action, its label should describe it succinctly, such as Mask or Show Art. Use title-style capitalization for both types of icon button label (for more information about thisstyle,see ["Capitalizing](#page-305-0) Labels and Text" (page 306)).  
**Avoid making the icon too big for the button.** Even though the outer dimensions of an icon button are not visible, they determine the hit target area. In general, it works well to size the icon button so that you leave a margin of about 10 pixels all the way around an icon.  
If you include a label, place it below the icon, as shown here in the Sound icon button. (Use the small system font for a label.)  
![](images/_page_247_Picture_8.jpeg)  
<span id="page-247-0"></span>**Avoid putting an icon button too close to other UI elements.** Don't forget that the entire button area is clickable (not just the icon). When you use Interface Builder, the layout guides help you see where the edges of an unbordered icon button are.  
#### Scope Button  
A **scope button** specifies the scope of an operation, such as a search, or defines a set of scoping criteria.  
![](images/_page_247_Figure_12.jpeg)  
**Important:** Scope buttons are designed to be used in scope bars and related filter rows only. They are not intended to be used in the toolbar or bottom-bar areas or outside of a scope bar in the window body.  
To learn more about scope bars, see "Using a Scope Bar to Enable [Searching](#page-186-0) and Filtering" (page 187).  
Scope buttons are available in Interface Builder. To create a recessed scope button using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSRecessedBezelStyle as the argument. To create a round rectangle scope button, pass NSRoundRectBezelStyle as the argument to the setBezelStyle: method.  
#### Appearance and Behavior  
Scope buttons are available in two different styles:  
The **recessed scope button**:  
The **round rectangle scope button**:  
Typically, round rectangle and recessed scope buttons contain text, but they can instead contain images.  
#### Guidelines  
Use a recessed scope button to display types or groups of objects or locations that users select to narrow the focus of a search or other operation.  
Use a round rectangle scope button to allow users to save a set of search criteria and to change or set scoping criteria.  
For example, the Finder uses round rectangle scope buttons to display search criteria, such as creation and last opened dates, and to provide a save search button. The Finder location buttons, such as This Mac and Shared, are recessed scope buttons.  
![](images/_page_248_Picture_13.jpeg)  
If you want to display an image in a scope button, be sure to consider the system-provided images before you spend time designing your own. If you decide to design a custom icon for use in a scope button,see ["Designing](#page-121-0) [Toolbar](#page-121-0) Icons" (page 122).  
#### <span id="page-249-0"></span>Gradient Button  
A **gradient button** performs an instantaneous action related to a view, such as a source list.  
![](images/_page_249_Picture_3.jpeg)  
Gradient buttons are available in Interface Builder. To create one using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSSmallSquareBezelStyle as the argument.  
#### <span id="page-249-1"></span>Appearance and Behavior  
Gradient buttons can have push-button, toggle, and pop-up menu behavior. For example, Mail uses gradient buttons below the sidebar to offer New Mailbox, Show/Hide Mail Activity, and Action menu functionality:  
![](images/_page_249_Picture_7.jpeg)  
Gradient buttons contain images; they do not contain text.  
#### Guidelines  
Use a gradient button to offer functionality that is directly related to a source list or other view, such as a column view.  
Because the function of a gradient button is closely tied to the view with which it's associated, there's little need to describe its action using a label.  
When possible, use system-provided images, such as the Action and the Add images, because their meaning is familiar to users. For more information on the system-provided images, see ["System-Provided](#page-319-0) Icons" (page 320). If you need to create your own iconsto use in a gradient button,see ["Designing](#page-121-0) Toolbar Icons" (page 122) for some guidance.  
#### <span id="page-250-0"></span>The Help Button  
The **Help button** opens a window that displays app-specific help.  
![](images/_page_250_Picture_4.jpeg)  
The standard Help button is available in Interface Builder. To create a Help button using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSHelpButtonBezelStyle as the argument.  
#### Appearance and Behavior  
The Help button is always a clear, circular button. The Help button is available in a single size and it always contains the standard OS X question mark graphic.  
When users click a Help button, the system-provided Help Viewer app opens to a page in the current app's help book. An app can determine whether the help book should open to a top-level page or to a page that is appropriate for the context of the button.  
#### Guidelines  
Don't create a custom button to perform the function of the standard Help button.  
In dialogs(including preferences windows) and drawers, the Help button can be located in either the lower-left or lower-right corner. In a dialog that includes OK and Cancel buttons (or other buttons used to dismiss the dialog), the Help button should be in the lower-left corner, vertically aligned with the buttons. In a dialog that does not include OK and Cancel buttons, such as a preferences window, the Help button should be in the lower-right corner. For example, the Mail Fonts & Colors preference displays a Help button in the lower-right corner.  
![](images/_page_251_Picture_2.jpeg)  
<span id="page-251-0"></span>For information on providing help in your app, see "User [Assistance"](#page-106-0) (page 107).  
#### Bevel Button  
A **bevel button** is a multipurpose button designed for use in the window-body area.  
**Note:** Bevel buttons are not recommended for use in apps that run in OS X v10.7 and later. You should consider alternatives,such as gradient buttons and segmented controls(described in ["Gradient](#page-249-0) [Button"](#page-249-0) (page 250) and ["Segmented](#page-258-0) Control" (page 259), respectively).  
You can use bevel buttons singly (as a push button) or in groups (as a set of radio buttons or checkboxes). The Preview inspector window uses bevel buttons as push buttons that rotate and crop the current content.  
![](images/_page_251_Picture_8.jpeg)  
Bevel buttons are available in Interface Builder. To create one using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSRegularSquareBezelStyle as the argument. (To create a square-cornered bevel button, use NSShadowlessSquareBezelStyle as the argument for the setBezelStyle: method.)  
#### Appearance and Behavior  
Bevel buttons can have square or rounded corners. They can display text, icons, or other images. Bevel buttons can also display a single downward-pointing arrow in addition to text or an image, which indicatesthe presence of a pop-up menu (for more information about this usage, see "Icon Button or Bevel Button [Containing](#page-259-0) a [Pop-Up](#page-259-0) Menu" (page 260)).  
Bevel buttons can behave like push buttons or can be grouped and used like radio buttons or checkboxes.  
#### Guidelines  
You can use a square-cornered bevel button when space is limited or when adjoining a set of bevel buttons.  
If you use a bevel button as a push button, its label should be a verb or verb phrase that describes the action it performs. If you provide a set of bevel buttons to be used as radio buttons or checkboxes, you might label each with a noun that describes a setting or a value.  
If you choose to display an icon or image instead of a text label, be sure the meaning of the image is clear and unambiguous. It's recommended that you create an icon no larger than 32 x 32 pixels. Maintain a margin of between 5 and 15 pixels between the icon and the outer edges of the button. A button that contains both an icon and a label may need a margin around the edge that's closer to 15 pixels than to 5 pixels. Use label font (10-point Lucida Grande Regular) for text labels.  
#### **Rounded corners**  
![](images/_page_252_Picture_10.jpeg)  
![](images/_page_252_Picture_11.jpeg)  
![](images/_page_252_Picture_12.jpeg)  
Leave at least 5 pixels between edge of icon and edge of button.  
#### **Rounded corners with label below icon**  
![](images/_page_252_Picture_15.jpeg)  
![](images/_page_252_Picture_16.jpeg)  
![](images/_page_252_Picture_17.jpeg)  
Bevel button as a push button  
You can also use Interface Builder to add a pop-up menu to a bevel button. First, drag a pop-up button into your window then, in the Attributes pane of the inspector, change the type to Pull Down. Finally, in the same pane, change the style to Bevel (for a standard bevel button look) or Square (for a square-cornered bevel button look).  
#### <span id="page-253-0"></span>Round Button  
A **round button** initiates an immediate action.  
**Note:** Round buttons are not recommended for use in apps that run in OS X v10.7 and later. You should consider an alternative,such as a gradient button (described in ["Gradient](#page-249-0) Button" (page 250)).  
![](images/_page_253_Picture_5.jpeg)  
![](images/_page_253_Picture_6.jpeg)  
Round buttons are available in Interface Builder. To create one using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSCircularBezelStyle as the argument.  
#### Appearance and Behavior  
Round buttons contain images only, not text.  
#### Guidelines  
Round buttons, like bevel buttons, are seldom used in modern Mac apps. You might want to use a gradient button that contains a system-provided (or custom) image as an alternative. For more information about gradient buttons, see ["Gradient](#page-249-0) Button" (page 250); for more information about system-provided images, see ["System-Provided](#page-319-0) Icons" (page 320).  
**Don't use a round button to create a Help button.** If you provide onscreen help, use the standard Help button instead (to learn more about this control, see "The Help [Button"](#page-250-0) (page 251)).  
**Don't use round buttons as radio buttons or as checkboxes.** If you need to provide functionality of these types, use radio buttons (see "Radio [Buttons"](#page-254-1) (page 255)) or checkboxes (see ["Checkbox"](#page-256-0) (page 257)).  
If you need to display a single letter in a round button you should treat the letter as an icon.