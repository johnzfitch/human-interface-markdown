<!-- Chunk 116 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 361 -->
The **View menu** provides commands that affect what users see in a window. In the Finder, for example, the View menu contains commands for displaying windows as columns, icons, or lists. Commands for showing, hiding, and customizing a toolbar belong in the View menu. Create a View menu for these commands even if your application doesn't need to have other commands in the View menu. Show/Hide Toolbar should appear right above Customize Toolbar.  
Avoid using the View menu to display utility windows (such as tool palettes); use the Window menu instead.  
<span id="page-93-0"></span>**Figure 7-19** A View menu  
![](images/_page_93_Picture_3.jpeg)  
<span id="page-93-2"></span><span id="page-93-1"></span>**Show/Hide Toolbar (Command-Option-T).** Shows or hides a toolbar. The Show/Hide Toolbar command is provided so that people using full keyboard access can implement these functions with the keyboard. It should be a dynamic menu item that toggles based on the current visibility of the toolbar. If the toolbar is currently visible, the menu item says Hide Toolbar. If the toolbar is not visible, it says Show Toolbar.  
**Customize Toolbar**. Opens a window that allows the user to customize which items are present. Figure 7-20 shows the result of choosing this command in the Finder.  
<span id="page-94-3"></span><span id="page-94-1"></span>**Figure 7-20** Finder toolbar customization window  
![](images/_page_94_Picture_3.jpeg)