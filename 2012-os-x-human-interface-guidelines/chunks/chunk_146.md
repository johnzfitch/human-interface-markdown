<!-- Chunk 146 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 8830 -->
Selection controls provide waysfor usersto make selectionsfrom multiple items. Some selection controls allow only a single selection, others can be configured to allow a single selection or multiple selections.  
**Important:** The controls described in this section are suitable for use in the window body; they should not be used in the window-frame areas. The single exception is the icon button with a pop-up menu, which can also be used in a toolbar. To learn more about the controls that are designed specifically for use in the toolbar (and bottom-bar), see ["Window-Frame](#page-240-0) Controls" (page 241).  
#### <span id="page-254-1"></span>Radio Buttons  
A group of **radio buttons** displays a set of mutually exclusive, but related, choices.  
| Open all files in one window                                |
|-------------------------------------------------------------|
| <ul> <li>Open groups of files in the same window</li> </ul> |
| Open each file in its own window                            |  
Radio buttons are available in Interface Builder. To create one using AppKit programming interfaces, create an NSButton object with type NSRadioButton.  
#### Appearance and Behavior  
The selected and unselected appearances of a radio button are provided automatically; you do not display any text or images in a radio button.  
A set of radio buttonsis never dynamic; that is, the contents and labels don't change depending on the context.  
#### Guidelines  
Use a group of radio buttons when you need to display a set of choices from which the user can choose only one.  
**Use checkboxes, instead of radio buttons, to display a set of choices from which the user can choose more than one at the same time.** Also, if you need to display a single setting, state, or choice that the user can either accept or reject, don't use a single radio button; instead you can use a checkbox. To learn more about checkboxes, see ["Checkbox"](#page-256-0) (page 257).  
**Consider using a pop-up menu if you need to display more than five items.** It's best when a group of radio buttons contains at least two items and a maximum of about five. (To learn more about pop-up menus, see ["Pop-Up](#page-260-0) Menu" (page 261).)  
**Don't use a radio button to initiate an action.** Instead, use a push button to initiated an action. Note that the choice of a radio button can change the state of the app. In Speech preferences, for example, the user must choose the second listening method ("Listen continuously with keyword"), to enable the keyword setup preferences.  
![](images/_page_255_Picture_2.jpeg)  
**Give each radio button a text label that describes the choice it represents.** Users need to know precisely what they're choosing when they select a radio button. Radio button labels should have sentence-style capitalization, as described in ["Capitalizing](#page-305-0) Labels and Text" (page 306). In addition, you should introduce a group of radio buttons with a label that describes the choices represented by the group.  
**In a horizontal group of radio buttons, make the space between each pair of radio buttons consistent.** It works well to measure the space needed to accommodate the longest radio button label and use that measurement consistently. Also, use the Interface Builder guidesto ensure that the baseline of the introductory label is aligned with the baseline of the label of the first button in a group.  
#### <span id="page-256-0"></span>Checkbox  
A **checkbox** describes a state, action, or value that can be either on or off.  
Checkboxes are available in Interface Builder. To create one using AppKit programming interfaces, create an NSButton object of type NSSwitchButton.  
#### Appearance and Behavior  
The selected and unselected appearances of a checkbox are provided automatically; you do not display any text or images in a checkbox.  
#### Guidelines  
Use a checkbox when you want to allow users to choose between two opposite states, actions, or values.  
**Use radio buttons, instead of checkboxes, to provide a set of choices from which users can choose only one.** To learn more about using radio buttons in your app, see "Radio [Buttons"](#page-254-1) (page 255).  
**Use the alignment of a group of checkboxes to show how they're related.** If there are several independent values or states you want users to control, you can provide a group of checkboxes that are all left-aligned. If, on the other hand, you need to allow usersto make an on-off type of choice that can lead to additional, related on-off choices, you can display checkboxes in a hierarchy that indicates the relationship.  
For example, in the Clock pane of Date & Time preferences, the options for customizing the display of date and time in the menu bar are inactive unless the user selects "Show date and time in menu bar." In addition to using unambiguous labels, the Clock pane uses this indentation to show users that some settings are dependent on others.  
![](images/_page_257_Picture_2.jpeg)  
**Provide a label for each checkbox that clearly implies two opposite states.** The label should make it clear what happens when the option is selected or deselected. If you can't find an unambiguous label, consider using a pair of radio buttons instead, so you can clarify the two states with two different labels. Checkbox labelsshould have sentence-style capitalization (for more on thisstyle,see ["Capitalizing](#page-305-0) Labels and Text" (page 306)), unless the state or value is the title of some other element in the interface that is capitalized.  
In addition, it's a good idea to provide a label that introduces a group of checkboxes and clearly describes the set of choices they represent. Use the Interface Builder guides to ensure that the baseline of the introductory label is aligned with the baseline of the label of the first button in a group.  
**If appropriate, display a dash inside a checkbox.** A dash means that the selection comprises more than one state, in a way that issimilar to the use of a dash in a menu (for more information about this,see "Using [Symbols](#page-142-0) in [Menus"](#page-142-0) (page 143)).  
**In general, arrange checkboxes in a column.** When checkboxes are arranged vertically, it's easier for users to distinguish one state from another.  
#### <span id="page-258-0"></span>Segmented Control  
A **segmented control** is a linear set of two or more segments, each of which functions as a button.  
![](images/_page_258_Picture_3.jpeg)  
**Important:** The segmented control described in this section is suitable for use in the window body only; it should not be used in the window-frame areas. For information about the segmented control that can be used in the toolbar (or bottom bar), see ["Window-Frame](#page-240-0) Controls" (page 241).  
The segmented control is available in Interface Builder. To create one using AppKit programming interfaces, use the NSSegmentedControl class.  
#### Appearance and Behavior  
A segmented control contains either icons or text, but not a mixture of both. The segments in a segmented control can behave as a collection of radio buttons or checkboxes.  
#### Guidelines  
Use a segmented control to offer users a few closely related choices that affect a selected object. You can also use a segmented control to change views or panes in a window. (Note that a view-changer segmented control looks similar to a tab view control, it does not behave the same; for more information about tab views, see "Tab [View"](#page-296-0) (page 297).)  
**Don't use a segmented control to enable addition or deletion of objects in a source list or split view.** If you need to provide a way for users to add and delete objects in a source list or other split view, use a gradient button (described in ["Gradient](#page-249-0) Button" (page 250)) in the window body. (If you need to put an add-delete control in a bottom bar, use a toolbar control (described in ["Appearance](#page-243-2) and Behavior" (page 244).)  
**Make the width of each segment the same.** If segments have different widths, users are likely to wonder if different segments have different behaviors or different degrees of importance.  
**Use a noun or short noun phrase for the text inside each segment.** The text you provide should describe a view or an object and use title-style capitalization (for more on thisstyle,see ["Capitalizing](#page-305-0) Labels and Text" (page 306)). A segmented control that contains text inside each segment probably does not need an introductory label.  
**As much as possible, use the system-provided icons, instead of custom icons, inside a segmented control.** If you need to design your own images, try to imitate the clarity and simple lines of the system-provided images. For some tips on how to create custom images of this type, see ["Designing](#page-121-0) Toolbar Icons" (page 122). (To learn more about the system-provided images, see ["System-Provided](#page-319-0) Icons" (page 320).) If you decide to design custom icons for a segmented control, use the following sizes:  
● Regular size: 17 x 15 pixels.  
● Small: 14 x 13 pixels.  
● Mini: 12 x 11 pixels.  
<span id="page-259-0"></span>Note that if you choose to put icons inside the segments of a segmented control, you can provide a text label below the control.  
#### Icon Button or Bevel Button Containing a Pop-Up Menu  
An icon button or a bevel button that contains a pop-up menu provides a menu of choices. For example, the Keynote Chart inspector uses a bevel button that contains a pop-up menu to give users a menu of chart styles:  
![](images/_page_259_Picture_8.jpeg)  
Keynote also includes several icon buttons that contain pop-up menus in its toolbar (the Masters toolbar icon is shown here).  
![](images/_page_259_Picture_10.jpeg)  
**Important:** An icon button with a pop-up menu can be used in a window-frame area, as well as in the window body. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-240-0) Controls" (page 241).  
An icon or bevel button with a pop-up menu is easy to create in Interface Builder. First, drag a pop-up button (an NSPopUpButton object) into your window. Select the button and in the Attributes pane of the inspector, change its type to Pull Down. Finally, for a Rounded or Square Bevel Button, change the style to Square or Shadowless Square, respectively. For an icon button, it doesn't matter which style you choose, but you must deselect the Bordered checkbox. Resize the button as needed.  
Both types of buttons can behave like a standard pop-up menu, in which the image on the button isthe current selection, or like a menu title, in which the image on the button is always the same.  
To learn more about bevel buttons, see "Bevel [Button"](#page-251-0) (page 252); to learn more about icon buttons, see ["Icon](#page-246-0) [Button"](#page-246-0) (page 247).  
#### <span id="page-260-0"></span>Pop-Up Menu  
A **pop-up menu** presents a list of mutually exclusive choices in a dialog or window.  
![](images/_page_260_Picture_5.jpeg)  
**Important:** The pop-up menu described in this section is suitable for use in the window-body only. If you need to provide pop-up menu functionality in a window-frame area, see ["Window-Frame](#page-240-0) Controls" (page 241).  
Pop-up menus are available in Interface Builder. To create one using AppKit programming interfaces, use the NSPopUpButton class.  
#### Appearance and Behavior  
A pop-up menu:  
- Has a double-arrow indicator.
- Contains nouns (things) or adjectives (states or attributes), but not verbs (commands).
- Displays a checkmark to the left of the currently selected value when open.  
You can see most of these components in the Highlight color pop-up menu in General preferences (the double-arrow indicator isn't completely visible because the menu is open).  
![](images/_page_260_Picture_14.jpeg)  
A pop-up menu behaves like other menus: Users press to open the menu and then drag to choose an item. The chosen item flashes briefly and is displayed in the closed pop-up menu. If users move the pointer outside the open menu without releasing the mouse button, the current value remains active. An exploratory press in the menu to see what's available doesn't select a new value.  
#### Pop-Up Menu Usage  
Use a pop-up menu to present up to 12 mutually exclusive choices that users don't need to see all the time.  
**Consider using a pop-up menu as an alternative to other types of selection controls.** For example, if you have a dialog that contains a set ofsix or more radio buttons, you might consider replacing them with a pop-up menu to save space.  
**Use a pop-up menu to provide a menu of things or states.** If you need to provide a menu of commands (that is, verbs), use a pull-down menu instead (to learn more about menus,see "UI Element [Guidelines:](#page-131-0) Menus" (page 132)). Use title-style capitalization for the label of each item in a pop-up menu.  
**In general, provide an introductory label to the left of the pop-up menu (in left-to-right scripts).** The label should have sentence-style capitalization (for more information on this capitalization style, see ["Capitalizing](#page-305-0) [Labels](#page-305-0) and Text" (page 306)).  
**Avoid adding a submenu to an item in a pop-up menu.** A submenu tends to hide choices too deeply and can be physically difficult for users to use.  
**Avoid using a pop-up menu to display a variable number of items.** Because users must open a pop-up menu to see its contents, they should be able to rely on the contents remaining the same.  
**Consider using a scrolling list, instead of a pop-up menu, for a large number of items.** If space is not restricted, use a scrolling list to display more than 12 items.  
**Don't use a pop-up menu when more than one simultaneous selection is appropriate.** For example, a list of text styles, from which users might choose both bold and italic, should not be displayed in a pop-up menu. In this situation, you should instead use checkboxes or a pull-down menu in which checkmarks appear.  
**In rare cases, include a command that affects the contents of the pop-up menu itself.** For example, in the Print dialog, the Printer pop-up menu contains the Add Printer item, which allows users to add a printer to the menu. If users add a new printer, it becomes the menu's default selection. If you need to add such commands to a pop-up menu, put them at the bottom of the menu, below a separator. (A separator—called a Separator Menu Item in Interface Builder—is a horizontal line.)  
**Ensure that all pop-up menus in a stack have the same width.** Even if the visible contents of each pop-up menu varies, the width of the controls themselves should be equal.  
#### <span id="page-262-0"></span>Action Menu  
An **Action menu** is a specific type of pop-up menu that functions as an app-wide contextual menu.  
![](images/_page_262_Picture_3.jpeg)  
**Important:** An Action menu can be used in a window-frame area or the window body. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-240-0) Controls" (page 241).  
To create an Action menu in Interface Builder use the control that's appropriate for the window area. Then, in the Attributes pane of the inspector, specify NSActionTemplate for the image.  
#### Appearance and Behavior  
An Action menu displays the system-provided Action icon and the standard downward-pointing arrow. (This is the same arrow used in an icon button with an attached pop-up menu; for more information about this controls, see "Icon Button or Bevel Button [Containing](#page-259-0) a Pop-Up Menu" (page 260).)  
An Action menu does not display a label, because users are familiar with the meaning of the Action icon. The only exception is the label that accompanies an Action menu button in a toolbar, because users can customize the toolbar to view toolbar items asicons with text or astext instead of icons(for more information on toolbars, see ["Designing](#page-179-0) a Toolbar" (page 180)).  
#### Guidelines  
Use an Action pop-up menu to provide a visible shortcut to a handful of useful commands. An Action menu hasthe advantage of a contextual menu, without the disadvantage of being hidden. (You can learn more about contextual menus in ["Designing](#page-161-1) Contextual Menus" (page 162).)  
In particular, you can use an Action menu in a toolbar to replace an app-wide contextual menu. For example, in its default set of toolbar controls, the Finder includes an Action menu that performs tasks related to the currently selected item.  
![](images/_page_263_Picture_2.jpeg)  
**Don't create a custom version of the Action icon.** It's essential that you use the system-provided Action icon so that users understand what the control does (for more information on the system-provided icons, see ["System-Provided](#page-319-0) Icons" (page 320)).  
**Follow the guidelines for contextual menu items as you design the contents of an Action menu.** For example, you should ensure that each Action menu item is also available as a menu command and avoid displaying keyboard shortcuts. For more information on the guidelines that govern contextual menus, see ["Designing](#page-161-1) [Contextual](#page-161-1) Menus" (page 162).  
**Use an Action menu at the bottom of a list to provide commands that apply to items in the list.** An Action menu works well beneath a list view or a source list. For example, the Action menu at the bottom of the Mail source list contains commands that act on the account or mailbox selected in the source list.  
![](images/_page_264_Picture_2.jpeg)  
Use a gradient button to provide an Action menu at the bottom of a source list or list view (for information on gradient buttons, see ["Gradient](#page-249-0) Button" (page 250)).  
**Avoid placing an Action menu control anywhere else in the body of a window.** An Action menu needs to be visually connected to a context, such as a list or a toolbar. An Action menu can't replace a contextual menu that users reveal by Control-clicking anywhere in a window, because placing the Action menu in a specific area implies that it applies to that area.  
#### <span id="page-265-0"></span>Share Menu  
A **Share menu** is a specific type of pop-up menu that displays a list of services that users can choose to share content.  
![](images/_page_265_Picture_3.jpeg)  
To create a Share menu in Interface Builder, select the appropriate button. Then, in the Attributes pane of the inspector, specify NSImageNameShareTemplate for the image. To create one using AppKit programming interfaces, use NSImageNameShareTemplate to add an image to a button (NSButton). If you create a Share button programmatically, in order for the Share menu to behave as users expect, you need to set sendActionOn:NSLeftMouseDownMask.  
**Important:** A Share menu should be used in a window-frame area. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-240-0) Controls" (page 241).  
#### Appearance and Behavior  
A Share menu displays the system-provided Share icon. A Share menu does not display a label because users are familiar with the meaning of the Share icon.  
Users reveal the menu by clicking on the Share menu button. A list descends from the button, and its width is dictated by the longest menu item.  
#### Guidelines  
Sharing Service is an integral part of the OS X experience. A Share menu enables users to share content they care about with others. For general guidelines about Sharing, see ["Sharing](#page-78-0) Service" (page 79).  
Use a Share pop-up menu to provide a visible shortcut to a handful of useful sharing options. A Share menu hasthe advantage of a contextual menu, without the disadvantage of being hidden. (You can learn more about contextual menus in ["Designing](#page-161-1) Contextual Menus" (page 162).  
**Don't create a custom version of the Share icon.** It's essential that you use the system-provided Share icon so that users understand what the control does (for more information on the system-provided icons, see ["System-Provided](#page-319-0) Icons" (page 320).  
**Follow the guidelines for contextual menu items as you design the contents of a Share menu.** For example, you should ensure that each Share menu item is also available as a menu command and avoid displaying keyboard shortcuts. For more information on the guidelines that govern contextual menus, see ["Designing](#page-161-1) [Contextual](#page-161-1) Menus" (page 162).  
#### <span id="page-266-0"></span>Combination Box  
A **combination box** (or combo box) provides a list of choices and allows users to specify custom choices.  
![](images/_page_266_Picture_3.jpeg)  
Combo boxes are available in Interface Builder. To create one using the AppKit programming interfaces, use the NSComboBox class.  
#### Appearance and Behavior  
A combo box is a text entry field combined with a drop-down list. The default state of the combo box is closed, with the text field empty or displaying a default selection.  
Users open the list by clicking the arrow to the right of the text field. The list descends from the text field and is the same width as the text field plus the arrow box.  
Users can type any appropriate characters into the text field. If a user types in an item already in the list, or types in a few characters that match the first characters of an item in the list, that item is highlighted when the user opens the list. A user-typed item is *not* added to the permanent list.  
#### Guidelines  
Use a combo box to give users the convenience of selecting an item from a list combined with the freedom of specifying their own custom item.  
**List only items that users can choose singly.** A combo box does not allow multiple selections, so be sure to offer users a list of items from which they can choose only one at a time.  
**Display a meaningful default selection.** It's best when the default selection (which may not be the first item in the list) provides a clue to the hidden choices. It's also a good idea to introduce a combo box with a label that helps users know what types of items to expect.  
**Don't extend the right edge of the list beyond the right edge of the arrow box.** If an item is too long, it is truncated.  
**Display the most likely choices, even though users can enter their own.** Users appreciate being able to specify custom choices, but they also appreciate the convenience of choosing from a list. For example, Safari allows users to set a preference for the minimum font size to display. In its Advanced preferences pane (shown here), Safari lists several font sizes in a combo box, and users can supply a custom font size if none of the listed choices is suitable.  
![](images/_page_267_Figure_2.jpeg)  
#### <span id="page-267-0"></span>Path Control  
A **path control** displays the file-system path of the currently selected item.  
![](images/_page_267_Picture_5.jpeg)  
The path control is available in Interface Builder (you can change itsstyle in the Attributes pane of the inspector panel). To create this control using AppKit programming interfaces, use the NSPathControl class.  
For example, the Finder uses one style of path control to display the path of the currently selected item at the bottom of the window, as shown in "A path control displays the path of the current item."  
#### Appearance and Behavior  
There are three styles of path control, all of which are suitable for use in the window body:  
- Standard
- Navigation bar
- Pop up  
All three path-controlstyles display text in addition to iconsfor apps, folders, and document types. When users click the pop-up style path control, a pop-up menu appears, which lists all locations in the path and a Choose menu item. Users can use the Open dialog opened by the Choose item to view the contents of the selected folder (for more information on the Open dialog, see "The Open [Dialog"](#page-221-0) (page 222)).  
If the displayed path is too long to fit in the control, the folder names between the first location and the last are hidden, as shown here in the path control in a Finder window.  
![](images/_page_268_Picture_3.jpeg)  
#### Guidelines  
Use a path control to display the file-system location of the currently selected item in a way that is not overly technical. You can also use a path control to allow users to retrace their steps along a path and open folders they visited earlier.  
<span id="page-268-0"></span>**Use a path control only when necessary.** For most apps, a path control is unlikely to be useful, because few apps need to provide a file-system browsing experience the way the Finder does.  
#### Color Well  
A **color well** indicates the current color of the selected object and, when clicked, displays the Colors window, in which users can specify a color. (To learn more about the Colors window, see "The Colors [Window"](#page-86-0) (page 87).)  
Multiple color wells can appear in a window. For example, the Graphic pane of the Pages inspector contains three color wells that allow users to change the color of an object's fill, stroke, and shadow.  
![](images/_page_269_Figure_2.jpeg)  
<span id="page-269-0"></span>Color wells are available in Interface Builder. To create one using AppKit programming interfaces, use the NSColorWell class.  
#### Image Well  
An **image well** is a drag-and-drop target for an icon or picture.  
For example, the Password pane in Accounts preferences uses an image well to allow users to choose a picture to represent them.  
![](images/_page_269_Picture_7.jpeg)  
Some image wells,such asthe user picture in the Password pane of Accounts preferences, must always contain an image. If you allow users to clear an image well (that is, leave it empty), be sure to provide standard Edit menu commands and Clipboard support for the contents of the image well.  
Image wells are available in Interface Builder. To create one using AppKit programming interfaces, use the NSImageView class.  
#### <span id="page-270-0"></span>Date Picker  
A **date picker** displays components of date and time, such as hours, minutes, days, and years.  
![](images/_page_270_Picture_5.jpeg)  
The date-picker control is available in Interface Builder (you can change its style in the Attributes pane of the inspector). To create one using AppKit programming interfaces, use the NSDatePicker class.  
#### Appearance and Behavior  
The date-picker control provides two main styles:  
- **Textual**. This style consists of a text field or text field combined with a stepper control.
- **Graphical**. This style consists of a graphical representation of a calendar or a clock.  
Using the textual style, users can enter date and time information in the text field or use the stepper. Using the graphical style, users can move the clock hands or choose specific days, months, or years in the calendar.  
#### Guidelines  
Use a date picker to provide time and date setting functionality in a window.  
**Choose the date-picker style that suits your app.** The text field and stepper date picker is useful when space is constrained and you expect users to be making specific date and time selections. A graphical date picker can be useful when you want to give users the option of browsing through days in a calendar or when the look of a clock face is appropriate for the UI of your app.  
#### <span id="page-271-0"></span>Command Pop-Down Menu  
A **command pop-down menu** provides pull-down menu functionality within a window.  
![](images/_page_271_Picture_4.jpeg)  
You can use Interface Builder to create a command pop-down menu: Select an NSPopUpButton object and change its type to Pull Down in the Attributes pane of the inspector. To create a command pop-down menu using AppKit programming interfaces, use the NSPopUpButton class.  
#### Appearance and Behavior  
A closed command pop-down menu always displays the same text, which acts as the menu title. This is in contrast to a closed pop-up menu, which displays the currently selected item (to learn more about pop-up menus, see ["Pop-Up](#page-260-0) Menu" (page 261)).  
A command pop-down menu contains a single, downward-pointing arrow and can display checkmarks to the left of all currently active selections.  
Users open a command pop-down menu by clicking anywhere in the control.  
#### Guidelines  
Use a command pop-down menu to present a list of commands that affect the containing window's contents. For example, the Colors window contains a menu with commands that can be used to change the contents of the Colors window itself.  
![](images/_page_272_Picture_3.jpeg)  
**In general, use a command pop-down menu in a window that is shared among other windows or apps.** For example, the Colors window can be used in any app. The items in its command pop-down menu allow users to make new palettes of colors available in the Colors window.  
**Avoid listing too many items in a command pop-down menu.** Command pop-down menus should contain between 3 and 12 commands. The items in a command pop-down menu do not have to be mutually exclusive.  
<span id="page-272-0"></span>**In general, don't supply an introductory label for a command pop-down menu.** The text in the control should be sufficient to tell users what they can expect to find in the menu.  
#### Slider  
A **slider** lets users choose from a continuousrange of allowable values(shown here with tick marks and labels).  
![](images/_page_272_Picture_9.jpeg)  
Sliders are available in Interface Builder. To create one using AppKit programming interfaces, use the NSSlider class.  
#### Appearance and Behavior  
A slider can be linear or circular.  
The movable part of a linear slider is called the **thumb**, and it can be either directional or round. The slider shown here has a directional thumb  
![](images/_page_273_Picture_4.jpeg)  
A circular slider displays a small circular dimple that provides the same functionality as the thumb of a linear slider: Users drag the dimple clockwise or counter-clockwise to change the values.  
![](images/_page_273_Picture_6.jpeg)  
If a circular slider includes tick marks, they appear as dots that are evenly spaced around the circumference of the slider.  
#### Guidelines  
Use a slider to allow users to make fine-grained adjustments or choices throughout a range of values. Sliders support live feedback (live dragging), so they're especially useful when you want users to be able to see the effects of moving a slider in real time. For example, users can watch the size of Dock icons change as they move the Dock Size slider in Dock preferences.  
**Ensure that the slider moves as users expect.** By default, users scroll content in the "natural" manner (that is, the content moves in the same direction as the user's fingers on a trackpad). But users can change this setting so that the content moves in the opposite direction of the gesture. You need to make sure that a slider always moves in the direction that makes the most sense, regardless of the user's setting. For example, the user should be able to move a vertical volume slider upwards for greater volume and downwards for lower volume.  
**In general, use a directional thumb in a linear slider with tick marks.** The point of the thumb helps show users the current value. (Note that you can also display a directional-thumb slider without tick marks.)  
**In general, use a round thumb in a linear slider without tick marks.** The rounded lower edge of the thumb works well in a slider without tick marks because it does not appear to point to a specific value.  
**In general, label at least the starting and ending values in a linear slider with tick marks.** You can create labels that use numbers or words, depending on what the values represent. If each tick mark represents an equal fraction of the entire range, it might not be necessary to label each one. However, if users can't deduce the value of each tick mark from its position in the range, you probably should label each one to prevent confusion. For example, it's important to label some of the interior tick marks in Energy Saver preferences.  
![](images/_page_274_Picture_2.jpeg)  
In addition, it's a good idea to set the context for a slider with an introductory label so users know what they're changing.  
**As much as possible, match the slider style to the values it represents.** For example, a linear slider is appropriate in Energy Saver preferences (shown above) because the values range from very small (the screen saver should start after 3 minutes) to very large (the screen saver should never start) and do not increase at consistent intervals. In this case, a linear slider brings to mind a number line that stretches from the origin to infinity.  
On the other hand, the circular slider in the Keynote Graphic inspector (shown below) allows users to choose the angle of the drop shadow displayed for an object. The circular slider not only displays the full range of values (0 to 360 degrees) in a compact way, it also mirrors the placement of the drop shadow itself as it is displayed on different sides of the object.  
![](images/_page_274_Picture_6.jpeg)  
**Display tick marks when it helps users understand their choices.** In general, you should display tick marks when it's important for users to understand the scale of the measurements or when users need to be able to select specific values. If, on the other hand, users don't need to be aware of the specific values the slider passes through (as in the Dock size and magnification preferences, for example), you might choose to display a slider without tick marks.  
#### <span id="page-275-0"></span>The Stepper Control (Little Arrows)  
The **stepper control** (also known as little arrows) allows users to increment or decrement values, usually in conjunction with a text field that indicates the current value.  
![](images/_page_275_Picture_3.jpeg)  
The text field may or may not be editable.  
<span id="page-275-1"></span>The stepper control is available in Interface Builder. To create one using AppKit programming interfaces, use the NSStepper class.  
#### Placard  
A **placard** displays information at the bottom edge of a window.  
![](images/_page_275_Picture_8.jpeg)  
**Note:** Placards are not recommended for use in apps that run in OS X v10.7 and later.  
Placards are not available in Interface Builder. To create one using AppKit programming interfaces, subclass NSScrollView.  
Typically, placards are used in document windows as a way to enable quick modifications to the view of the contents—for example, to change the current page or the magnification. The most familiar use of the placard is as a pop-up menu placed at the bottom of a window, to the left of the horizontal scroll bar.  
![](images/_page_275_Picture_12.jpeg)  
**Don't add to the placard menu commands that affect the contents of the window in other ways.** Instead, you should use an Action menu (for more information on Action menus, see ["Action](#page-262-0) Menu" (page 263)).