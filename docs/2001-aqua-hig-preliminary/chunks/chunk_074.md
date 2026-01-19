<!-- Chunk 74 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 510 -->
The Open dialog appears when the user chooses the Open command or presses Command-O. The Open dialog is application modal (the user can switch to other applications).  
**Note:** If you implement an Open command, you should also include an Open Recent command so that users can access recently opened documents without going through the dialog.  
<span id="page-78-0"></span>**Figure 6-4** An Open dialog  
![](images/_page_78_Picture_3.jpeg)  
#### The Open dialog  
- has a column browser for navigating the file system
- has a From pop-up menu that contains Favorite Places (all containers in the user's Favorites folder) and Recent Places (the five most recent folders into which the user saved documents). Your application specifies the default location, typically the last user-selected location or the user's Documents folder.
- displays an Add to Favorites button, which adds an alias of the chosen folder to the user's Favorites folder and immediately updates the Favorite Places list in the From pop-up menu. The Add to Favorites button is always available.
- has a default title ("Open"); you should add your application's name to the Open dialog title—"TextEdit Open," for example.  
Dialog Behavior **79**  
- can include a Show pop-up menu, which allows the user to filter the type of files that appear in the list. Items that do not meet the filtering criteria appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an "All applicable files" item, but it does not have to be the default.
- includes a Go to text field, into which the user can type file system paths (pathnames must begin with "/" or "~") to navigate in the dialog.
- can be resized with the resize control in the lower-right corner
- supports document preview
- supports multiple selection if your application allows it; the user can open multiple documents in the same operation