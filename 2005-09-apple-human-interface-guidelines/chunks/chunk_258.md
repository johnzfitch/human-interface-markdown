<!-- Chunk 258 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 1273 -->
An application that saves the contents of individualwindows—whichwould be most text and graphics applications—should use document-specific sheets for its Save dialogs. The Save dialog has two states: minimal and expanded. Clickingthe disclosure button toggles between these states. If the user changes the state, the next Save dialog should open in the selected state.  
<span id="page-210-3"></span>Your application should pass in a filename extension as part of every filename. Users can control its visibility usingthe Hide Extension checkbox in the expanded Save dialog; see[Figure](#page-182-2) 13-15 (page 183). Existing documents do not get extensions added to or removed from their filenames unless the user chooses Save As and changes the setting in the Save dialog.  
#### <span id="page-210-4"></span>**The Minimal Save Dialog**  
<span id="page-210-1"></span>In the minimal Save dialog, users can save changes to an unnamed document, name or rename a document, and choose a frequently accessed location to store it.  
**Figure 13-39** The minimal (collapsed) Save dialog  
![](images/_page_210_Picture_10.jpeg)  
<span id="page-210-6"></span><span id="page-210-5"></span>The minimal Save dialog contains these elements:  
■ Save As text field for the document name. Expert users can enter pathnames by pressing Command-Shift-G. (Note that the pathname separator is the "/" character.)  
If the document has not been saved previously, your application should put the default name (such as "untitled") in this field, and the filename should be selected. If the user has chosen to make the filename extension visible, the extension is not selected.  
If the document has been saved previously and the user chooses Save As, the Save dialog should open with the document name highlighted in the Save As field. The filename extension (if it is visible) is not selected.  
- <span id="page-211-2"></span>■ Where pop-up menu, containing mounted volumes, the folders in theFinder Sidebar, and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typicallythe predefined Documents folderin the user's home folder. If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- A Save button (default).
- <span id="page-211-1"></span>■ A Cancel button. Dismisses the dialog and returns the application to its previous state.
- A disclosure button. Clicking it displays the expanded Save dialog. (For more information about how to use disclosure buttons, see ["Disclosure](#page-263-0) Buttons" (page 264).)  
Any custom elements you add go between the Where pop-up menu and the buttons at the bottom of the dialog.  
#### <span id="page-211-4"></span><span id="page-211-3"></span>**The Expanded Save Dialog**  
<span id="page-211-0"></span>In contrast with the minimal Save dialog, the expanded Save dialog lets users save documents in locations other than those available in the minimal Save dialog's Where pop-up menu.  
**Figure 13-40** The expanded Save dialog  
![](images/_page_211_Picture_11.jpeg)  
In addition to the items in the minimal Save dialog, the expanded Save dialog displays the following:  
■ Backand forward buttons to navigate backand forth between selections made in the list or column view.  
- A source list that mirrors the Finder Sidebar.
- A column or list view for navigating the file system.
- A File Format (or Format) pop-up menu, which displays a list of file formats from which the user can choose.
- <span id="page-212-2"></span>■ A New Folder button, which displays an application-modal dialog that asks the user to name the new folder, and then creates it.
- <span id="page-212-0"></span>■ A Hide Extension checkbox, which allows the user to control whether or not the filename's extension (.jpg, for example) is visible. The Hide Extension checkbox should be selected as the default (that is, filename extensions should not appear in user-visible filenames unless the user requests them).  
If the user changes the state of the checkbox for a particular document, the next new document should match the last user-selected state, even after the user quits and reopens the application. The filename in the Save As field updates in real time as the checkbox is selected or deselected.  
<span id="page-212-1"></span>Don't provide your own options for handling filename extensions; use the standard Open and Save dialogs.  
**Carbon:** Set the PreserveSaveFileExtension flag when calling the Save dialog, and use NavCompleteSave to set the flag to hide the filename extension.  
If you add other elements to customize the expanded Save dialog, they should appear above the Cancel and Save buttons. When the dialog is expanded, custom elements should appear between the file-system browser and the push buttons.  
In default keyboard navigation mode, pressing Tab in the expanded Save dialog shifts the keyboard focus from the Save As text field to the source list, to the visible columns, and then back to the text field.