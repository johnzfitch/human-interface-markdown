<!-- Chunk 110 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 814 -->
A **checkbox** describes a state, action, or value that can be either on or off.  
| Double-click a window's title bar to minimize |
|-----------------------------------------------|
| Minimize windows into application icon        |
| Animate opening applications                  |
| Automatically hide and show the Dock          |
| Show indicators for open applications         |
|                                               |  
**API Note:** To define a checkbox in your code, create an NSButton object of type NSSwitchButton.  
#### A checkbox:  
- Is designed for use in the window body only, not in the window-frame areas. To learn about controls that you can use in window-frame areas, see Some [Controls](#page-176-1) Can Be Used in the Window Frame (page 177).
- Doesn't display custom text or images  
Use a checkbox to allow users to choose between two opposite states, actions, or values.  
**Use radio buttons, not checkboxes, to provide a set of choices from which users can choose only one.** To learn more about using radio buttons in your app, see Radio [Buttons](#page-179-0) (page 180).  
**Use the alignment of a group of checkboxes to show how they're related.** If there are several independent values or states that you want users to control, you can provide a group of checkboxes that are all left-aligned. If, on the other hand, you need to allow users to make an on-off type of choice that can lead to additional, related on-off choices, you can display checkboxes in a hierarchy that indicates the relationship.  
For example, in the Clock pane of Date & Time preferences, the options for customizing the display of date and time in the menu bar are inactive unless the user selects "Show date and time in menu bar." In addition to using unambiguous labels, the Clock pane uses this indentation to show users that some settings are dependent on others.  
![](images/_page_182_Picture_2.jpeg)  
**Provide a label for each checkbox that clearly implies two opposite states.** The label should make it clear what happens when the option is selected or deselected. If you can't find an unambiguous label, consider using a pair of radio buttons instead, so you can clarify the two states with two different labels. Give checkbox labels sentence-style capitalization, unless the state or value is the title of another element in the interface that is capitalized. For more on this style, see Use the Right [Capitalization](#page-46-0) Style in Labels and Text (page 47).  
In addition, it's a good idea to provide a label that introduces a group of checkboxes and clearly describes the set of choices they represent. Use the Interface Builder guides to ensure that the baseline of the introductory label is aligned with the baseline of the label of the first button in a group.  
**If appropriate, display a dash inside a checkbox.** A dash indicates that the selection represents more than one state, in a way that is similar to the use of a dash in a menu. For more information about this, see [Symbols](#page-84-0) Can Give Users [Information](#page-84-0) About State (page 85).  
**In general, arrange checkboxes in a column.** When checkboxes are arranged vertically, it's easier for users to distinguish one state from another.