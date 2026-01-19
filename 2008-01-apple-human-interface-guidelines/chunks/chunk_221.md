<!-- Chunk 221 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 205 -->
Users can close windows by:  
- Choosing Close from the File menu
- Pressing Command-W
- Clicking the close button  
When a user closes a document window, your application should:  
- Decidewhat to dowith unsaved data (see "Dialogs for Saving, Closing, and [Quitting"](#page-249-0) (page 250))
- Store thewindow's onscreen position and size (so theycan be usedwhen thewindowis reopened)  
<span id="page-223-2"></span>In most cases, applications that are not document-based should quitwhen the mainwindowis closed. For Example, System Preferences quits if the user closes the window. If an application continues to perform some function when the main window is closed, however, it may be appropriate to leave it runningwhen the mainwindowis closed.For example, iTunes continues to playwhen the user closes the main window.