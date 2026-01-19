<!-- Chunk 193 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 815 -->
You can use the keyboard to move the focus (highlight) between onscreen items. This feature enables a user to access controls, menus, the Dock, toolbars, and so on when using the mouse is undesirable, difficult, or impossible. In Roman systems, focus always begins at the first field that accepts keyboard input and follows a reading path from upper left to bottom right.  
<span id="page-167-1"></span>Focus is indicated with a ring in the appearance color (Aqua or Graphite).  
**Figure 9-1** Keyboard focus for a text field  
![](images/_page_167_Picture_9.jpeg)  
<span id="page-168-0"></span>**Figure 9-2** Keyboard focus for a scrolling list  
![](images/_page_168_Picture_3.jpeg)  
**Figure 9-3** Keyboard focus for columns  
<span id="page-168-1"></span>![](images/_page_168_Picture_5.jpeg)  
In list and column views, a selected item should be highlighted across the full row. In column view, the selected item has a dark highlight and the folders containing the item have a lighter highlight. When a window becomes inactive, all selections inside it should become the lighter highlight color.  
The Keyboard **169**  
User Input  
<span id="page-169-7"></span><span id="page-169-5"></span><span id="page-169-0"></span>Navigation between most controls in achieved by pressing the Tab key and the arrow keys. Shift-Tab navigates in reverse direction.  
<span id="page-169-4"></span><span id="page-169-2"></span>In **default keyboard access mode,** focus moves only between fields that receive keyboard input, such as text entry fields, list boxes that support type-ahead, and scrolling lists. Mac OS X 10.1 provides the option of **full keyboard access mode,** which enables users to navigate through windows and dialogs. Cocoa applications that use system controls get this functionality automatically.  
<span id="page-169-1"></span>Users can turn on full keyboard access in the Full Keyboard Access pane of Keyboard preferences. Control -F1 is a reserved keyboard shortcut for turning full keyboard access on or off; don't use this combination for any other purpose. Control-F7 temporarily overrides the current mode in windows and dialogs.  
In full keyboard access mode, the arrow keys move between values within a control. For example, if the user selects a slider with the Tab key, the arrow keys move the slider control along the slider track. For vertically oriented choices, such as menu items, the Up Arrow and Down Arrow keys move the slider. For horizontally oriented choices, such as a row of tabs, the Right Arrow and Left Arrow keys move the slider. In some cases, it makes sense to support both orientations. For example, a vertical slider could use both the Up Arrow and the Right Arrow to increase the value.  
<span id="page-169-6"></span>In some cases, such as radio buttons, moving the focus to an item selects it as well. In other cases, such as push buttons, the user chooses a selected item by pressing the Space bar. In full keyboard access mode, pressing the Space bar is equivalent to clicking the mouse button.  
<span id="page-169-3"></span>The Escape key is used to cancel a dialog and to cancel a selection in a pop-up menu or list. In a Dock pop-up menu, Escape dismisses the menu and moves focus to the frontmost window.