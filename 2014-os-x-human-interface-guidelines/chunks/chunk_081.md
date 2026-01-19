<!-- Chunk 81 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 492 -->
Users expect a window to open when they:  
- Double-click the icon for a document in the Finder
- Double-click an app icon
- Select a document in the Finder and choose Open from the File menu (or select the document and press Command-O in the Finder)
- Choose a file from within an Open dialog
- Choose the New command from the File menu
- Click the app icon in the Dock (when no windows are currently open)  
Most users expect app windows that were open when they logged out to reopen when they log back in. To meet this expectation, be sure to opt in to the Resume feature. To learn the programmatic steps you need to take to adopt Resume, see User Interface Preservation. (Note that users can opt out of this feature in General preferences.)  
**Make sure windows display changeable panes as users expect.** For the most part, users expect windows to reopen the pane that was open previously. Specifically, windows with changeable panes should reopen in their previous state as long as the app is open; if the user quits the app, these windows should return to their default state.  
In a window with multiple toolbars, if the toolbar represents only a subset of multiple possible views (such as favorites), the default state should be to show all of the options below the toolbar, not a particular pane. If the toolbar displays all of the possible selections, then the default state of the window should be to display the pane that the user last selected. For example, when System Preferences opens, all of the possible selections are visible, but when Mail preferences opens, it displays the last pane selected by the user.  
**Title a newly opened window appropriately.** When the user opens an existing document, make sure its title is the **display name**, which reflects the user's preference for showing or hiding its filename extension. Don't display pathnames in document titles. To learn how to name new windows, see Naming [Windows](#page-124-0) (page 125).