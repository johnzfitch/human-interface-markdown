<!-- Chunk 109 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 642 -->
A group of **radio buttons** displays a set of mutually exclusive, but related, choices.  
![](images/_page_179_Picture_11.jpeg)  
**APINote:** To define a radio button in your code, create an NSButton object of type NSRadioButton.  
#### A radio button:  
- Is designed for use in the window body only, not in the window-frame areas. To learn about controls that you can use in window-frame areas, see Some [Controls](#page-176-1) Can Be Used in the Window Frame (page 177).
- Is not dynamic; that is, the button's content and label don't change depending on the context.
- Doesn't display custom text or images.  
Use a group of radio buttons when you need to display a set of choices from which the user can choose only one.  
**Use checkboxes, instead of radio buttons, to display a set of choices from which the user can choose more than one at the same time.** Also, if you need to display a single setting, state, or choice that the user can either accept or reject, don't use a single radio button; use a checkbox instead. To learn more about checkboxes, see [Checkbox](#page-181-0) (page 182).  
**Consider using a pop-up menu if you need to display more than five items.** It's best when a group of radio buttons contains at least two items and a maximum of about five. To learn more about pop-up menus, see [Pop-Up](#page-189-1) Menu (page 190).  
**Don't use a radio button to initiate an action.** Instead, use a push button to initiate an action. Note that the choice of a radio button can change the state of the app. In Speech preferences, for example, the user must choose the second listening method ("Listen continuously with keyword"), to enable the keyword setup preferences.  
![](images/_page_180_Picture_10.jpeg)  
**Give each radio button a text label that describes the choice it represents.** Users need to know precisely what they're choosing when they select a radio button. Give radio button labels sentence-style capitalization, as described in Use the Right [Capitalization](#page-46-0) Style in Labels and Text (page 47). In addition, introduce a group of radio buttons with a label that describes the choices represented by the group.  
**In a horizontal group of radio buttons, make the space between each pair of radio buttons consistent.** It works well to measure the space needed to accommodate the longest radio button label and use that measurement consistently. Also, use the Interface Builder guidesto ensure that the baseline of the introductory label is aligned with the baseline of the label of the first button in a group.