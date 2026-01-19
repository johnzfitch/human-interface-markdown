<!-- Chunk 117 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 736 -->
An **Action menu** is a specific type of pop-up menu that functions as an app-wide contextual menu.  
![](images/_page_191_Picture_3.jpeg)  
**Important:** An Action menu can be used in a window-frame area or the window body. To learn more about controls that are designed specifically for use in window-frame areas, see Some [Controls](#page-176-1) Can Be Used on the [Window](#page-176-1) Frame (page 177).  
**API Note:** To create an Action menu in Interface Builder use the control that's appropriate for the window area. Then, in the Attributes pane of the inspector, specify NSActionTemplate for the image.  
#### An Action menu:  
- Displays the system-provided Action image and the standard downward-pointing arrow
- Does not display a label (because users are familiar with the meaning of the Action image)  
Use an Action pop-up menu to provide a visible shortcut to a handful of useful commands. An Action menu hasthe advantage of a contextual menu, without the disadvantage of being hidden. You can learn more about contextual menus in [Contextual](#page-106-0) Menus (page 107).  
In particular, you can use an Action menu in a toolbar to replace an app-wide contextual menu. For example, in its default set of toolbar controls, the Finder includes an Action menu that performs tasks related to the currently selected item.  
![](images/_page_192_Picture_2.jpeg)  
**Don't create a custom version of the Action image.** It's essential that you use the system-provided Action image so that users understand what the control does. For more information on the system-provided images, see [System-Provided](#page-328-0) Images (page 329).  
**Follow the guidelines for contextual menu items as you design the contents of an Action menu.** For example, you should ensure that each Action menu item is also available as a menu command and avoid displaying keyboard shortcuts. For more information on the guidelines that govern contextual menus, see [Contextual](#page-106-0) [Menus](#page-106-0) (page 107).  
**Use an Action menu at the bottom of a list to provide commands that apply to items in the list.** An Action menu works well beneath a list view or a source list. For example, the Action menu at the bottom of the Mail source list contains commands that act on the account or mailbox selected in the source list.  
![](images/_page_193_Picture_2.jpeg)  
Use a gradient button to provide an Action menu at the bottom of a source list or table view. For information on gradient buttons, see [Gradient](#page-183-0) Button (page 184).  
<span id="page-193-0"></span>**Avoid placing an Action menu control anywhere else in the body of a window.** An Action menu needs to be visually connected to a context, such as a list or a toolbar. An Action menu can't replace a contextual menu that users reveal by Control-clicking anywhere in a window, because placing the Action menu in a specific area implies that it applies to that area.