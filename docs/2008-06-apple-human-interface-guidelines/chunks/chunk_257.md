<!-- Chunk 257 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 535 -->
Your application should open a window when a user does any of the following:  
- Double-clicks the icon for a document supported by your application in the Finder
- Double-clicks your application icon
- Selects a document in the Finder and chooses open from the File menu (or selects the document and presses Command-O in the Finder)
- <span id="page-210-4"></span><span id="page-210-3"></span>■ Chooses a file from within an Open dialog
- Chooses the New command from the File menu
- Clicks the application icon in the Dock when no windows are open  
When the user opens an existing document, make sure its title is the **display name**, which reflects the user's preference for showing or hiding its filename extension. Don't display pathnames in document titles.  
New windows should be named as described in "Naming New [Windows"](#page-211-0) (page 212).  
<span id="page-211-5"></span>The content of some windows changes depending on the user's selection. For example, when the user clicks one of the icons at the top of the Mail Preferences window, the display at the bottom of the window changes. Some windows,such as Displaysin System Preferences,switch panes using a tab control (see "Tab [Views"](#page-328-0) (page 329)).  
Windows with changeable panes should reopen in their previous state as long as the application is open and return to their default views when the user quits. In a window with toolbars, if the toolbar represents only a subset of multiple possible views (favorites), the default state should be to show all of the options below the toolbar, not a particular pane. If the toolbar displays all of the possible selections, then the default state of the window should be to display whichever pane the user last selected. For example, when System Preferences opens, all of the possible selections are visible, but when Mail preferences opens, it displays the last pane selected by the user. The System Preferences window is shown in Figure 14-29.  
<span id="page-211-6"></span><span id="page-211-1"></span>**Figure 14-29** The System Preferences window in its default state  
![](images/_page_211_Picture_5.jpeg)