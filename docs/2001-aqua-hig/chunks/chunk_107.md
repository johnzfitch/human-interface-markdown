<!-- Chunk 107 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 660 -->
<span id="page-98-4"></span><span id="page-98-3"></span><span id="page-98-2"></span><span id="page-98-1"></span>The Open dialog appears when the user chooses the Open command or presses Command-O. The Open dialog is application modal (the user can switch to other applications).  
Dialog Behavior **99**  
If you implement an Open command, you should also include an Open Recent command so users can access recently opened documents without going through the dialog.  
<span id="page-99-1"></span>**Note:** The Carbon functions in Navigation Services, introduced in Mac OS 8.5, has been enhanced to add support for Mac OS X. Its predecessor, the Standard File Package, is not supported in Mac OS X.  
<span id="page-99-0"></span>**Figure 6-4** An Open dialog  
![](images/_page_99_Picture_5.jpeg)  
The Open dialog contain these elements:  
■ A default title ("Open"); you should add your application's name to the Open dialog title—"TextEdit: Open," for example.  
- A From pop-up menu that contains Favorite Places (all containers in the user's Favorites folder) and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically one of the predefined folders in the user's home folder. (For recommended default locations, see ["File Location" \(page 235\).](#page-234-0)) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- A column browser for navigating the file system.
- A "Go to" text field, into which expert users can type file-system paths to navigate in the dialog. Pathnames must begin with "/" or "~".
- <span id="page-100-2"></span>■ An Add to Favorites button, which adds an alias of the chosen folder to the user's Favorites folder and immediately updates the Favorite Places list in the From pop-up menu. The Add to Favorites button is always active.
- A Cancel button and an Open (default) button.
- A resize control in the lower-right corner.  
An Open dialog can include a Show pop-up menu, which allows the user to filter the type of files that appear in the list. Items that do not meet the filtering criteria appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an "All applicable files" item, but it does not have to be the default.  
Open dialogs should support document preview and can support multiple selection if your application allows more than one document to be open at a time.