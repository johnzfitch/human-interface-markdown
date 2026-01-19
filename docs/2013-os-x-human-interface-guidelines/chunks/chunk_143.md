<!-- Chunk 143 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 6324 -->
An icon button or a bevel button that contains a pop-up menu provides a menu of choices. For example, the Keynote Chart inspector uses a bevel button that contains a pop-up menu to give users a menu of chart styles:  
![](images/_page_257_Picture_8.jpeg)  
Keynote also includes several icon buttons that contain pop-up menus in its toolbar (the Masters toolbar icon is shown here).  
![](images/_page_257_Picture_10.jpeg)  
**Important:** An icon button with a pop-up menu can be used in a window-frame area, as well as in the window body. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-237-0) Controls" (page 238).  
An icon or bevel button with a pop-up menu is easy to create in Interface Builder. First, drag a pop-up button (an NSPopUpButton object) into your window. Select the button and in the Attributes pane of the inspector, change its type to Pull Down. Finally, for a Rounded or Square Bevel Button, change the style to Square or Shadowless Square, respectively. For an icon button, it doesn't matter which style you choose, but you must deselect the Bordered checkbox. Resize the button as needed.  
Both types of buttons can behave like a standard pop-up menu, in which the image on the button isthe current selection, or like a menu title, in which the image on the button is always the same.  
To learn more about bevel buttons, see "Bevel [Button"](#page-249-0) (page 250); to learn more about icon buttons, see ["Icon](#page-244-0) [Button"](#page-244-0) (page 245).  
#### <span id="page-258-0"></span>Pop-Up Menu  
A **pop-up menu** presents a list of mutually exclusive choices in a dialog or window.  
![](images/_page_258_Picture_5.jpeg)  
**Important:** The pop-up menu described in this section is suitable for use in the window-body only. If you need to provide pop-up menu functionality in a window-frame area, see ["Window-Frame](#page-237-0) Controls" (page 238).  
Pop-up menus are available in Interface Builder. To create one using AppKit programming interfaces, use the NSPopUpButton class.  
#### Appearance and Behavior  
A pop-up menu:  
- Has a double-arrow indicator.
- Contains nouns (things) or adjectives (states or attributes), but not verbs (commands).
- Displays a checkmark to the left of the currently selected value when open.  
You can see most of these components in the Highlight color pop-up menu in General preferences (the double-arrow indicator isn't completely visible because the menu is open).  
![](images/_page_259_Picture_2.jpeg)  
A pop-up menu behaves like other menus: Users press to open the menu and then drag to choose an item. The chosen item flashes briefly and is displayed in the closed pop-up menu. If users move the pointer outside the open menu without releasing the mouse button, the current value remains active. An exploratory press in the menu to see what's available doesn't select a new value.  
Pop-up menus are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light [Content](#page-240-0) [Controls"](#page-240-0) (page 241).  
#### Pop-Up Menu Usage  
Use a pop-up menu to present up to 12 mutually exclusive choices that users don't need to see all the time.  
**Consider using a pop-up menu as an alternative to other types of selection controls.** For example, if you have a dialog that contains a set ofsix or more radio buttons, you might consider replacing them with a pop-up menu to save space.  
**Use a pop-up menu to provide a menu of things or states.** If you need to provide a menu of commands (that is, verbs), use a pull-down menu instead (to learn more about menus,see "UI Element [Guidelines:](#page-129-0) Menus" (page 130)). Use title-style capitalization for the label of each item in a pop-up menu.  
**In general, provide an introductory label to the left of the pop-up menu (in left-to-right scripts).** The label should have sentence-style capitalization (for more information on this capitalization style, see ["Capitalizing](#page-303-0) [Labels](#page-303-0) and Text" (page 304)).  
**Avoid adding a submenu to an item in a pop-up menu.** A submenu tends to hide choices too deeply and can be physically difficult for users to use.  
**Avoid using a pop-up menu to display a variable number of items.** Because users must open a pop-up menu to see its contents, they should be able to rely on the contents remaining the same.  
**Consider using a scrolling list, instead of a pop-up menu, for a large number of items.** If space is not restricted, use a scrolling list to display more than 12 items.  
**Don't use a pop-up menu when more than one simultaneous selection is appropriate.** For example, a list of text styles, from which users might choose both bold and italic, should not be displayed in a pop-up menu. In this situation, you should instead use checkboxes or a pull-down menu in which checkmarks appear.  
**In rare cases, include a command that affects the contents of the pop-up menu itself.** For example, in the Print dialog, the Printer pop-up menu contains the Add Printer item, which allows users to add a printer to the menu. If users add a new printer, it becomes the menu's default selection. If you need to add such commands to a pop-up menu, put them at the bottom of the menu, below a separator. (A separator—called a Separator Menu Item in Interface Builder—is a horizontal line.)  
<span id="page-260-0"></span>**Ensure that all pop-up menus in a stack have the same width.** Even if the visible contents of each pop-up menu varies, the width of the controls themselves should be equal.  
#### Action Menu  
An **Action menu** is a specific type of pop-up menu that functions as an app-wide contextual menu.  
![](images/_page_260_Picture_8.jpeg)  
**Important:** An Action menu can be used in a window-frame area or the window body. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-237-0) Controls" (page 238).  
To create an Action menu in Interface Builder use the control that's appropriate for the window area. Then, in the Attributes pane of the inspector, specify NSActionTemplate for the image.  
#### Appearance and Behavior  
An Action menu displays the system-provided Action icon and the standard downward-pointing arrow. (This is the same arrow used in an icon button with an attached pop-up menu; for more information about this controls, see "Icon Button or Bevel Button [Containing](#page-257-0) a Pop-Up Menu" (page 258).)  
An Action menu does not display a label, because users are familiar with the meaning of the Action icon. The only exception is the label that accompanies an Action menu button in a toolbar, because users can customize the toolbar to view toolbar items asicons with text or astext instead of icons(for more information on toolbars, see ["Designing](#page-177-0) a Toolbar" (page 178)).  
#### Guidelines  
Use an Action pop-up menu to provide a visible shortcut to a handful of useful commands. An Action menu hasthe advantage of a contextual menu, without the disadvantage of being hidden. (You can learn more about contextual menus in ["Designing](#page-158-0) Contextual Menus" (page 159).)  
In particular, you can use an Action menu in a toolbar to replace an app-wide contextual menu. For example, in its default set of toolbar controls, the Finder includes an Action menu that performs tasks related to the currently selected item.  
![](images/_page_261_Picture_5.jpeg)  
**Don't create a custom version of the Action icon.** It's essential that you use the system-provided Action icon so that users understand what the control does (for more information on the system-provided icons, see ["System-Provided](#page-318-0) Icons" (page 319)).  
**Follow the guidelines for contextual menu items as you design the contents of an Action menu.** For example, you should ensure that each Action menu item is also available as a menu command and avoid displaying keyboard shortcuts. For more information on the guidelines that govern contextual menus, see ["Designing](#page-158-0) [Contextual](#page-158-0) Menus" (page 159).  
**Use an Action menu at the bottom of a list to provide commands that apply to items in the list.** An Action menu works well beneath a list view or a source list. For example, the Action menu at the bottom of the Mail source list contains commands that act on the account or mailbox selected in the source list.  
![](images/_page_262_Figure_3.jpeg)  
Use a gradient button to provide an Action menu at the bottom of a source list or table view (for information on gradient buttons, see ["Gradient](#page-247-0) Button" (page 248)).  
**Avoid placing an Action menu control anywhere else in the body of a window.** An Action menu needs to be visually connected to a context, such as a list or a toolbar. An Action menu can't replace a contextual menu that users reveal by Control-clicking anywhere in a window, because placing the Action menu in a specific area implies that it applies to that area.  
#### <span id="page-263-0"></span>Share Menu  
A **Share menu** is a specific type of pop-up menu that displays a list of services that users can use to share content. Users reveal a Share menu by clicking a Share menu button.  
![](images/_page_263_Picture_5.jpeg)  
To create a Share menu button in Interface Builder, first select the appropriate button. Then, in the Attributes pane of the inspector, specify NSImageNameShareTemplate for the image. To create a Share menu button using AppKit programming interfaces, use NSImageNameShareTemplate to add an image to a button (NSButton). If you create the button programmatically, in order for the Share menu to behave as users expect, you need to set sendActionOn:NSLeftMouseDownMask.  
**Important:** A Share menu should be used in a window-frame area. To learn more about controls that are designed specifically for use in window-frame areas, see ["Window-Frame](#page-237-0) Controls" (page 238).  
#### Appearance and Behavior  
A Share menu button displays the system-provided Share icon. The button does not display a label because users are familiar with the meaning of the Share icon.  
Users reveal the menu by clicking on the Share menu button. A list descends from the button, and its width is dictated by the longest menu item.  
#### Guidelines  
Sharing Service is an integral part of the OS X experience. A Share menu enables users to share content they care about with others. For general guidelines about Sharing, see ["Sharing](#page-77-0) Service" (page 78).  
Use a Share pop-up menu to provide a visible shortcut to a handful of useful sharing options. A Share menu hasthe advantage of a contextual menu, without the disadvantage of being hidden. (You can learn more about contextual menus in ["Designing](#page-158-0) Contextual Menus" (page 159).)  
**Don't create a custom version of the Share icon.** It's essential that you use the system-provided Share icon so that users understand what the control does (for more information on the system-provided icons, see ["System-Provided](#page-318-0) Icons" (page 319).)  
**Follow the guidelines for contextual menu items as you design the contents of a Share menu.** For example, you should ensure that each Share menu item is also available as a menu command and avoid displaying keyboard shortcuts. For more information on the guidelines that govern contextual menus, see ["Designing](#page-158-0) [Contextual](#page-158-0) Menus" (page 159).  
#### <span id="page-264-0"></span>Combination Box  
A **combination box** (or combo box) provides a list of choices and allows users to specify custom choices.  
![](images/_page_264_Picture_5.jpeg)  
Combo boxes are available in Interface Builder. To create one using the AppKit programming interfaces, use the NSComboBox class.  
#### Appearance and Behavior  
A combo box is a text entry field combined with a drop-down list. The default state of the combo box is closed, with the text field empty or displaying a default selection.  
Users open the list by clicking the arrow to the right of the text field. The list descends from the text field and is the same width as the text field plus the arrow box.  
Users can type any appropriate characters into the text field. If a user types in an item already in the list, or types in a few characters that match the first characters of an item in the list, that item is highlighted when the user opens the list. A user-typed item is *not* added to the permanent list.  
Combo boxes are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light [Content](#page-240-0) [Controls"](#page-240-0) (page 241).  
#### Guidelines  
Use a combo box to give users the convenience of selecting an item from a list combined with the freedom of specifying their own custom item.  
**List only items that users can choose singly.** A combo box does not allow multiple selections, so be sure to offer users a list of items from which they can choose only one at a time.  
**Display a meaningful default selection.** It's best when the default selection (which may not be the first item in the list) provides a clue to the hidden choices. It's also a good idea to introduce a combo box with a label that helps users know what types of items to expect.  
**Don't extend the right edge of the list beyond the right edge of the arrow box.** If an item is too long, it is truncated.  
**Display the most likely choices, even though users can enter their own.** Users appreciate being able to specify custom choices, but they also appreciate the convenience of choosing from a list. For example, Safari allows users to set a preference for the minimum font size to display. In its Advanced preferences pane (shown here), Safari lists several font sizes in a combo box, and users can supply a custom font size if none of the listed choices is suitable.  
![](images/_page_265_Figure_4.jpeg)  
#### <span id="page-265-0"></span>Path Control  
A **path control** displays the file-system path of the currently selected item.  
![](images/_page_265_Picture_7.jpeg)  
The path control is available in Interface Builder (you can change itsstyle in the Attributes pane of the inspector panel). To create this control using AppKit programming interfaces, use the NSPathControl class.  
For example, when you choose Show Path Bar, Finder uses one style of path control to display the path of the currently selected item at the bottom of the window.  
#### Appearance and Behavior  
There are three styles of path control, all of which are suitable for use in the window body:  
● Standard  
- Navigation bar
- Pop up  
All three path-controlstyles display text in addition to iconsfor apps, folders, and document types. When users click the pop-up style path control, a pop-up menu appears, which lists all locations in the path and a Choose menu item. Users can use the Open dialog opened by the Choose item to view the contents of the selected folder (for more information on the Open dialog, see "The Open [Dialog"](#page-218-0) (page 219)).  
If the displayed path is too long to fit in the control, the folder names between the first location and the last are hidden, as shown here in the path control in a Finder window.  
![](images/_page_266_Picture_5.jpeg)  
#### Guidelines  
Use a path control to display the file-system location of the currently selected item in a way that is not overly technical. You can also use a path control to allow users to retrace their steps along a path and open folders they visited earlier.  
<span id="page-266-0"></span>**Use a path control only when necessary.** For most apps, a path control is unlikely to be useful, because few apps need to provide a file-system browsing experience the way the Finder does.  
#### Color Well  
A **color well** indicates the current color of the selected object and, when clicked, displays the Colors window, in which users can specify a color. (To learn more about the Colors window, see "The Colors [Window"](#page-85-0) (page 86).)  
Multiple color wells can appear in a window. For example, the Graphic pane of the Pages inspector contains three color wells that allow users to change the color of an object's fill, stroke, and shadow.  
![](images/_page_267_Figure_2.jpeg)  
<span id="page-267-0"></span>Color wells are available in Interface Builder. To create one using AppKit programming interfaces, use the NSColorWell class.  
#### Image Well  
An **image well** is a drag-and-drop target for an icon or picture.  
For example, the Password pane in Accounts preferences uses an image well to allow users to choose a picture to represent them.  
![](images/_page_267_Picture_7.jpeg)  
Some image wells,such asthe user picture in the Password pane of Accounts preferences, must always contain an image. If you allow users to clear an image well (that is, leave it empty), be sure to provide standard Edit menu commands and Clipboard support for the contents of the image well.  
Image wells are available in Interface Builder. To create one using AppKit programming interfaces, use the NSImageView class.  
#### <span id="page-268-0"></span>Date Picker  
A **date picker** displays components of date and time, such as hours, minutes, days, and years.  
![](images/_page_268_Picture_5.jpeg)  
The date-picker control is available in Interface Builder (you can change its style in the Attributes pane of the inspector). To create one using AppKit programming interfaces, use the NSDatePicker class.  
#### Appearance and Behavior  
The date-picker control provides two main styles:  
- **Textual**. This style consists of a text field or text field combined with a stepper control.
- **Graphical**. This style consists of a graphical representation of a calendar or a clock.  
Using the textual style, users can enter date and time information in the text field or use the stepper. Using the graphical style, users can move the clock hands or choose specific days, months, or years in the calendar.  
#### Guidelines  
Use a date picker to provide time and date setting functionality in a window.  
**Choose the date-picker style that suits your app.** The text field and stepper date picker is useful when space is constrained and you expect users to be making specific date and time selections. A graphical date picker can be useful when you want to give users the option of browsing through days in a calendar or when the look of a clock face is appropriate for the UI of your app.  
#### <span id="page-269-0"></span>Command Pop-Down Menu  
A **command pop-down menu** provides pull-down menu functionality within a window.  
![](images/_page_269_Picture_4.jpeg)  
You can use Interface Builder to create a command pop-down menu: Select an NSPopUpButton object and change its type to Pull Down in the Attributes pane of the inspector. To create a command pop-down menu using AppKit programming interfaces, use the NSPopUpButton class.  
#### Appearance and Behavior  
A closed command pop-down menu always displays the same text, which acts as the menu title. This is in contrast to a closed pop-up menu, which displays the currently selected item (to learn more about pop-up menus, see ["Pop-Up](#page-258-0) Menu" (page 259)).  
A command pop-down menu contains a single, downward-pointing arrow and can display checkmarks to the left of all currently active selections.  
Users open a command pop-down menu by clicking anywhere in the control.  
#### Guidelines  
Use a command pop-down menu to present a list of commands that affect the containing window's contents. For example, the Colors window contains a menu with commands that can be used to change the contents of the Colors window itself.  
![](images/_page_270_Picture_3.jpeg)  
**In general, use a command pop-down menu in a window that is shared among other windows or apps.** For example, the Colors window can be used in any app. The items in its command pop-down menu allow users to make new palettes of colors available in the Colors window.  
**Avoid listing too many items in a command pop-down menu.** Command pop-down menus should contain between 3 and 12 commands. The items in a command pop-down menu don't have to be mutually exclusive.  
<span id="page-270-0"></span>**In general, don't supply an introductory label for a command pop-down menu.** The text in the control should be sufficient to tell users what they can expect to find in the menu.  
#### Slider  
A **slider** lets users choose from a continuousrange of allowable values(shown here with tick marks and labels).  
![](images/_page_270_Picture_9.jpeg)  
Sliders are available in Interface Builder. To create one using AppKit programming interfaces, use the NSSlider class.  
#### Appearance and Behavior  
A slider can be linear or circular.  
The movable part of a linear slider is called the **thumb**, and it can be either directional or round. The slider shown here has a directional thumb.  
![](images/_page_271_Picture_4.jpeg)  
A circular slider displays a small circular dimple that provides the same functionality as the thumb of a linear slider: Users drag the dimple clockwise or counter-clockwise to change the values.  
![](images/_page_271_Picture_6.jpeg)  
If a circular slider includes tick marks, they appear as dots that are evenly spaced around the circumference of the slider.  
Sliders are available in both standard Aqua and light content appearances. To learn more about controls that are appropriate for a window that has a light-colored or white background, see "Light Content [Controls"](#page-240-0) (page 241).  
#### Guidelines  
Use a slider to allow users to make fine-grained adjustments or choices throughout a range of values. Sliders support live feedback (live dragging), so they're especially useful when you want users to be able to see the effects of moving a slider in real time. For example, users can watch the size of Dock icons change as they move the Dock Size slider in Dock preferences.  
**Ensure that the slider moves as users expect.** By default, users scroll content in the "natural" manner (that is, the content moves in the same direction as the user's fingers on a trackpad). But users can change this setting so that the content moves in the opposite direction of the gesture. You need to make sure that a slider always moves in the direction that makes the most sense, regardless of the user's setting. For example, the user should be able to move a vertical volume slider upwards for greater volume and downwards for lower volume.  
**In general, use a directional thumb in a linear slider with tick marks.** The point of the thumb helps show users the current value. (Note that you can also display a directional-thumb slider without tick marks.)  
**In general, use a round thumb in a linear slider without tick marks.** The rounded lower edge of the thumb works well in a slider without tick marks because it does not appear to point to a specific value.  
**In general, label at least the starting and ending values in a linear slider with tick marks.** You can create labels that use numbers or words, depending on what the values represent. If each tick mark represents an equal fraction of the entire range, it might not be necessary to label each one. However, if users can't deduce the value of each tick mark from its position in the range, you probably should label each one to prevent confusion. For example, it's important to label some of the interior tick marks in Energy Saver preferences.  
![](images/_page_272_Picture_2.jpeg)  
In addition, it's a good idea to set the context for a slider with an introductory label so users know what they're changing.  
**As much as possible, match the slider style to the values it represents.** For example, a linear slider is appropriate in Energy Saver preferences (shown above) because the values range from very small (the screen saver should start after 3 minutes) to very large (the screen saver should never start) and don't increase at consistent intervals. In this case, a linear slider brings to mind a number line that stretches from the origin to infinity.  
On the other hand, the circular slider in the Keynote Graphic inspector (shown below) allows users to choose the angle of the drop shadow displayed for an object. The circular slider not only displays the full range of values (0 to 360 degrees) in a compact way, it also mirrors the placement of the drop shadow itself as it is displayed on different sides of the object.  
![](images/_page_272_Picture_6.jpeg)  
**Display tick marks when it helps users understand their choices.** In general, you should display tick marks when it's important for users to understand the scale of the measurements or when users need to be able to select specific values. If, on the other hand, users don't need to be aware of the specific values the slider passes through (as in the Dock size and magnification preferences, for example), you might choose to display a slider without tick marks.