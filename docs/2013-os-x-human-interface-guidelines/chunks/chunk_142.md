<!-- Chunk 142 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 2606 -->
Selection controls provide waysfor usersto make selectionsfrom multiple items. Some selection controls allow only a single selection, others can be configured to allow a single selection or multiple selections.  
**Important:** The controls described in this section are suitable for use in the window body; they should not be used in the window-frame areas. The single exception is the icon button with a pop-up menu, which can also be used in a toolbar. To learn more about the controls that are designed specifically for use in the toolbar (and bottom-bar), see ["Window-Frame](#page-237-0) Controls" (page 238).  
#### <span id="page-252-1"></span>Radio Buttons  
A group of **radio buttons** displays a set of mutually exclusive, but related, choices.  
| Open all files in one window              |
|-------------------------------------------|
| • Open groups of files in the same window |
| Open each file in its own window          |  
Radio buttons are available in Interface Builder. To create one using AppKit programming interfaces, create an NSButton object with type NSRadioButton.  
#### Appearance and Behavior  
The selected and unselected appearances of a radio button are provided automatically; you don't display any text or images in a radio button.  
A set of radio buttonsis never dynamic; that is, the contents and labels don't change depending on the context.  
Radio buttons are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light [Content](#page-240-0) [Controls"](#page-240-0) (page 241).  
#### Guidelines  
Use a group of radio buttons when you need to display a set of choices from which the user can choose only one.  
**Use checkboxes, instead of radio buttons, to display a set of choices from which the user can choose more than one at the same time.** Also, if you need to display a single setting, state, or choice that the user can either accept or reject, don't use a single radio button; instead you can use a checkbox. To learn more about checkboxes, see ["Checkbox"](#page-254-0) (page 255).  
**Consider using a pop-up menu if you need to display more than five items.** It's best when a group of radio buttons contains at least two items and a maximum of about five. (To learn more about pop-up menus, see ["Pop-Up](#page-258-0) Menu" (page 259).)  
**Don't use a radio button to initiate an action.** Instead, use a push button to initiated an action. Note that the choice of a radio button can change the state of the app. In Speech preferences, for example, the user must choose the second listening method ("Listen continuously with keyword"), to enable the keyword setup preferences.  
![](images/_page_253_Picture_3.jpeg)  
**Give each radio button a text label that describes the choice it represents.** Users need to know precisely what they're choosing when they select a radio button. Radio button labels should have sentence-style capitalization, as described in ["Capitalizing](#page-303-0) Labels and Text" (page 304). In addition, you should introduce a group of radio buttons with a label that describes the choices represented by the group.  
**In a horizontal group of radio buttons, make the space between each pair of radio buttons consistent.** It works well to measure the space needed to accommodate the longest radio button label and use that measurement consistently. Also, use the Interface Builder guidesto ensure that the baseline of the introductory label is aligned with the baseline of the label of the first button in a group.  
#### <span id="page-254-0"></span>Checkbox  
A **checkbox** describes a state, action, or value that can be either on or off.  
| Double-click a window's title bar to minimize |
|-----------------------------------------------|
| ■ Minimize windows into application icon      |
| ✓ Animate opening applications                |
| ✓ Automatically hide and show the Dock        |
| Show indicator lights for open applications   |
| Automatically hide and show the Dock          |  
Checkboxes are available in Interface Builder. To create one using AppKit programming interfaces, create an NSButton object of type NSSwitchButton.  
#### Appearance and Behavior  
The selected and unselected appearances of a checkbox are provided automatically; you don't display any text or images in a checkbox.  
Checkboxes are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light [Content](#page-240-0) [Controls"](#page-240-0) (page 241).  
#### Guidelines  
Use a checkbox when you want to allow users to choose between two opposite states, actions, or values.  
**Use radio buttons, instead of checkboxes, to provide a set of choices from which users can choose only one.** To learn more about using radio buttons in your app, see "Radio [Buttons"](#page-252-1) (page 253).  
**Use the alignment of a group of checkboxes to show how they're related.** If there are several independent values or states you want users to control, you can provide a group of checkboxes that are all left-aligned. If, on the other hand, you need to allow usersto make an on-off type of choice that can lead to additional, related on-off choices, you can display checkboxes in a hierarchy that indicates the relationship.  
For example, in the Clock pane of Date & Time preferences, the options for customizing the display of date and time in the menu bar are inactive unless the user selects "Show date and time in menu bar." In addition to using unambiguous labels, the Clock pane uses this indentation to show users that some settings are dependent on others.  
![](images/_page_255_Picture_2.jpeg)  
**Provide a label for each checkbox that clearly implies two opposite states.** The label should make it clear what happens when the option is selected or deselected. If you can't find an unambiguous label, consider using a pair of radio buttons instead, so you can clarify the two states with two different labels. Checkbox labelsshould have sentence-style capitalization (for more on thisstyle,see ["Capitalizing](#page-303-0) Labels and Text" (page 304)), unless the state or value is the title of some other element in the interface that is capitalized.  
In addition, it's a good idea to provide a label that introduces a group of checkboxes and clearly describes the set of choices they represent. Use the Interface Builder guides to ensure that the baseline of the introductory label is aligned with the baseline of the label of the first button in a group.  
**If appropriate, display a dash inside a checkbox.** A dash means that the selection comprises more than one state, in a way that issimilar to the use of a dash in a menu (for more information about this,see "Using [Symbols](#page-140-0) in [Menus"](#page-140-0) (page 141)).  
**In general, arrange checkboxes in a column.** When checkboxes are arranged vertically, it's easier for users to distinguish one state from another.  
#### <span id="page-256-0"></span>Segmented Control  
A **segmented control** is a linear set of two or more segments, each of which functions as a button.  
![](images/_page_256_Picture_3.jpeg)  
**Important:** The segmented control described in this section is suitable for use in the window body only; it should not be used in the window-frame areas. For information about the segmented control that can be used in the toolbar (or bottom bar), see ["Window-Frame](#page-237-0) Controls" (page 238).  
The segmented control is available in Interface Builder. To create one using AppKit programming interfaces, use the NSSegmentedControl class.  
#### Appearance and Behavior  
A segmented control contains either icons or text, but not a mixture of both. The segments in a segmented control can behave as a collection of radio buttons or checkboxes.  
Segmented controls are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light [Content](#page-240-0) [Controls"](#page-240-0) (page 241).  
#### Guidelines  
Use a segmented control to offer users a few closely related choices that affect a selected object. You can also use a segmented control to change views or panes in a window. (Note that a view-changer segmented control looks similar to a tab view control, it does not behave the same; for more information about tab views, see "Tab [View"](#page-293-0) (page 294).)  
**Don't use a segmented control to enable addition or deletion of objects in a source list or split view.** If you need to provide a way for users to add and delete objects in a source list or other split view, use a gradient button (described in ["Gradient](#page-247-0) Button" (page 248)) in the window body. (If you need to put an add-delete control in a bottom bar, use a toolbar control (described in ["Window-Frame](#page-237-0) Controls" (page 238).)  
**Make the width of each segment the same.** If segments have different widths, users are likely to wonder if different segments have different behaviors or different degrees of importance.  
**Use a noun or short noun phrase for the text inside each segment.** The text you provide should describe a view or an object and use title-style capitalization (for more on thisstyle,see ["Capitalizing](#page-303-0) Labels and Text" (page 304)). A segmented control that containstext inside each segment probably doesn't need an introductory label. **As much as possible, use the system-provided icons, instead of custom icons, inside a segmented control.** If you need to design your own images, try to imitate the clarity and simple lines of the system-provided images. For some tips on how to create custom images of this type, see ["Designing](#page-120-0) Toolbar Icons" (page 121). (To learn more about the system-provided images, see ["System-Provided](#page-318-0) Icons" (page 319).) If you decide to design custom icons for a segmented control, use the following sizes:  
● Regular size: 17 x 15 pixels.  
● Small: 14 x 13 pixels.  
● Mini: 12 x 11 pixels.  
<span id="page-257-0"></span>Note that if you choose to put icons inside the segments of a segmented control, you can provide a text label below the control.