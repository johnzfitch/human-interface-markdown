<!-- Chunk 107 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 652 -->
If you implement an Open command, you should also include an Open Recent command so users can access recently opened documents without going through the dialog.  
<span id="page-102-1"></span>**Note:** Navigation Services, introduced in Mac OS 8.5, has been enhanced to add support for Mac OS X. Its predecessor, the Standard File Package, is not supported in Mac OS X.  
<span id="page-102-0"></span>**Figure 6-4** An Open dialog  
![](images/_page_102_Picture_5.jpeg)  
The Open dialog contains these elements:  
- A default title ("Open"); you should add your application's name to the Open dialog title—"TextEdit: Open," for example.
- A From pop-up menu that contains Favorite Places (all containers in the user's Favorites folder) and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically one of the predefined folders in the user's home folder. (For recommended default locations, see ["Files" \(page 245\)](#page-244-0).) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- A column browser for navigating the file system.
- A "Go to" text field, in which expert users can type file-system paths to navigate in the dialog. Pathnames must begin with "/" or "~". (For guidelines about pathnames, see ["Displaying Pathnames" \(page 251\)](#page-250-0).)
- <span id="page-103-0"></span>■ An Add to Favorites button, which adds an alias of the chosen folder to the user's Favorites folder and immediately updates the Favorite Places list in the From pop-up menu. The Add to Favorites button is always active.
- A Cancel button and an Open (default) button.
- A resize control in the lower-right corner.  
You can extend the Open dialog as appropriate for your application. For example, you could include a pop-up menu allowing users to filter the type of files that appear in the list (see Figure 6-5). Items that do not meet the filtering criteria would appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an All Applicable Files item, but it does not have to be the default.  
<span id="page-104-2"></span>**Figure 6-5** A customized Open dialog (column browser not shown)  
![](images/_page_104_Picture_3.jpeg)  
Open dialogs should support document preview and can support multiple selection if your application allows more than one document to be open at a time.