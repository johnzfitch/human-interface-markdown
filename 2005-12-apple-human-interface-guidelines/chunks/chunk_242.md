<!-- Chunk 242 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 519 -->
Your application should open a window when a user does any of the following:  
- Double-clicks the icon for a document supported by your application in the Finder
- Double-clicks your application icon
- Selects a document in the Finder and chooses open from the File menu (or selects the document and presses Command-O in the Finder)
- Chooses a file from within an Open dialog
- Chooses the New command from the File menu
- <span id="page-183-6"></span><span id="page-183-3"></span>■ Clicks the application icon in the Dock when no windows are open  
When the user opens an existing document, make sure its title is the **display name,** which reflects the user's preference for showing or hiding its filename extension. Don't display pathnames in document titles.  
<span id="page-183-4"></span>New windows should be named as described in ["Naming New Windows"](#page-184-0) (page 185).  
The content of some windows changes depending on the user's selection. For example, when the user clicks one of the icons at the top of the Mail Preferences window, the display at the bottom of the window changes. Some windows, such as Displays in System Preferences, switch panes using a tab control (see ["Tab Views"](#page-271-0) (page 272)).  
<span id="page-183-5"></span>Windows with changeable panes should reopen in their previous state as long as the application is open and return to their default views when the user quits. In a window with toolbars, if the toolbar represents only a subset of multiple possible views (favorites), the default state should be to show all of the options below the toolbar, not a particular pane. If the toolbar displays all of the possible selections, then the default state of the window should be to display whichever pane the user last selected. For example, when System Preferences opens, all of the possible selections are visible, but when Mail preferences opens, it displays the last pane selected by the user.  
<span id="page-184-1"></span>**Figure 13-14** System Preferences in the default state  
![](images/_page_184_Picture_3.jpeg)