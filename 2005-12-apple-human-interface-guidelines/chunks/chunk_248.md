<!-- Chunk 248 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 209 -->
Users can close windows by:  
- Choosing Close from the File menu
- Pressing Command-W
- Clicking the close button  
When a user closes a document window, your application should:  
- Decide what to do with unsaved data (see ["Dialogs for Saving, Closing, and Quitting"](#page-212-0) (page 213))
- Store the window's onscreen position and size (so they can be used when the window is reopened)  
<span id="page-189-1"></span>In most cases, applications that are not document-based should quit when the main window is closed. For Example, System Preferences quits if the user closes the window. If an application continues to perform some function when the main window is closed, however, it may be appropriate to leave it running when the main window is closed. For example, iTunes continues to play when the user closes the main window.