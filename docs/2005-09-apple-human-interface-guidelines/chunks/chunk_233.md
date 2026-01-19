<!-- Chunk 233 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 206 -->
Users can close windows by:  
- Choosing Close from the File menu
- Pressing Command-W
- Clicking the close button  
When a user closes a document window, your application should:  
- Decide what to do with unsaved data (see "Dialogs for Saving, Closing, and [Quitting"](#page-210-0) (page 211))
- Store thewindow's onscreen position and size (so theycan be usedwhen thewindowis reopened)  
<span id="page-187-1"></span>In most cases, applications that are not document-based should quitwhen the mainwindowis closed. For Example, System Preferences quits if the user closes the window. If an application continues to perform some function when the main window is closed, however, it may be appropriate to leave it runningwhen the mainwindowis closed.For example, iTunes continues to playwhen the user closes the main window.