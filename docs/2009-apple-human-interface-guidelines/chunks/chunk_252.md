<!-- Chunk 252 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1338 -->
A **checkbox** describes a state, action, or value that can be either on or off. In a group of checkboxes, each checkbox should be independent of all the others, unless interdependency is clearly indicated (for example, by displaying a subordinate checkbox indented below a superior checkbox). A checkbox can also enable or disable another control, such as a text field or pop-up menu.  
<span id="page-282-1"></span>For example, in Sound preferences (shown in Figure 15-23), checkboxes allow users to make choices about sound effects and choose whether to display the volume setting in the menu bar. Notice that users can select or deselect any of the three sound effects checkboxes, because these controls are independent of each other.  
**Figure 15-23** Checkboxes provide on-off choices to the user  
![](images/_page_282_Picture_8.jpeg)  
#### <span id="page-282-2"></span>Checkbox Usage  
Use a checkbox when you want to allow users to choose between two opposite states, actions, or values. If you want to provide a set of choicesfrom which users can choose only one, use a set of radio buttonsinstead (see "Radio [Buttons"](#page-279-1) (page 280) for more on this control).  
If there are several independent values or states you want users to control, you can provide a group of checkboxes (see Figure 15-23 for an example of a group of independent checkboxes). If, on the other hand, you need to allow users to make an on-off type of choice that can lead to additional, related on-off choices, you can display checkboxes in a hierarchy that indicates the relationship.  
For example, the Trackpad pane of the Keyboard & Mouse preferences allows users to decide which trackpad gestures to use (this window is shown in Figure 15-24). Notice that the "Allow horizontal scrolling" checkbox is dependent on the "Use two fingers to scroll" checkbox, because if users choose *not* to use two fingers to scroll, they don't care about horizontal scrolling. Similarly, the Dragging and Drag Lock checkboxes are unavailable unless the Clicking checkbox is selected, because the dragging gestures are dependent on the clicking gesture. The Trackpad pane uses indentation to tell users that some of these settings are dependent on others.  
<span id="page-283-0"></span>**Figure 15-24** Checkboxes can be indented to show a dependent relationship  
![](images/_page_283_Picture_5.jpeg)  
#### Checkbox Contents and Labeling  
Each checkbox label should clearly imply two opposite states so it's clear what happens when the option is selected or deselected. If you can't find an unambiguous label, consider using a pair of radio buttons so you can clarify the states with two different labels.  
Checkbox labels should have sentence-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and [Text"](#page-135-0) (page 136) for more on this style), unless the state or value is the title of some other element in the interface that is capitalized.  
When a userselection comprises more than one state, use a dash in the appropriate checkboxes. Thissymbol is consistent with the mixed-state indicator in menus, as described in "Using [Symbols](#page-169-0) in Menus" (page 170).  
#### Checkbox Specifications  
**Control sizes**: The dimensions of the checkbox itself are fixed for each size, but you determine the length of the introductory label and checkbox label.  
**Label spacing and fonts**: Checkbox text (both the introductory label and control label) should be in a font that is proportional to the size of the control. The following fonts are supplied automatically by Interface Builder:  
- Regular size: System font.
- Small: Small system font.
- Mini: Mini system font.  
If you display an introductory label on the same line asthe first checkbox, use the following metricsto position it correctly:  
- Regular size: 8 pixels from the end of the label (the colon) to the control.
- Small: 6 pixels from the end of the label (the colon) to the control.
- <span id="page-284-1"></span>● Mini: 5 pixels from the end of the label (the colon) to the control.  
<span id="page-284-0"></span>Be sure to align the baseline of the introductory label with the baseline of the closest checkbox's label, as shown in Figure 15-25.  
**Figure 15-25** Checkbox label alignment  
![](images/_page_284_Figure_14.jpeg)  
If you display an introductory label above a group of checkboxes, leave 8 pixels between the label and the first checkbox.  
**Control spacing**: Typically, checkboxes are arranged vertically, because this arrangement makes it easier for users to distinguish one state from another. As described in ["Checkbox](#page-282-2) Usage" (page 283), you should align a set of independent checkboxes so that all appear to be at the same level. If one checkbox describes a state or action that depends on the state of another checkbox, you can indent the dependent checkbox below the controlling one.  
Use the following metrics when you lay out checkboxes in your window:  
- Regular size: 8 pixels between controls when stacked.
- Small: 8 pixels between controls when stacked.
- Mini: 7 pixels between controls when stacked.  
#### Checkbox Implementation  
Checkboxes are available in Interface Builder. To create one using Application Kit programming interfaces, create an NSButton object of type NSSwitchButton.