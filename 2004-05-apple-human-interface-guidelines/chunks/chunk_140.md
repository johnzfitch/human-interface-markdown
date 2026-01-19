<!-- Chunk 140 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 1028 -->
In the minimal Save dialog, users can save changes to an unnamed document, name or rename a document, and choose a frequently accessed location to store it.  
<span id="page-143-0"></span>**Figure 9-10** The minimal (collapsed) Save dialog  
![](images/_page_143_Picture_3.jpeg)  
The minimal Save dialog contains these elements:  
- <span id="page-143-7"></span><span id="page-143-5"></span>■ Save As text field for the document name. (Expert users can enter pathnames by pressing Command-Shift-G.)
- If the document has not been saved previously, your application should put the default name (such as "untitled") in this field, and the filename should be selected. If the user has chosen to make the filename extension visible, the extension is not selected.  
If the document has been saved previously and the user chooses Save As, the Save dialog should open with the document name highlighted in the Save As field. The filename extension (if it is visible) is not selected.  
- <span id="page-143-3"></span>■ Where pop-up menu, containing mounted volumes, the folders in the Finder sidebar, and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically the predefined Documents folder in the user's home folder. (For recommended default locations, see *Apple Software Design Guidelines*.) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- <span id="page-143-2"></span>■ A Save button (default).
- A Cancel button. Dismisses the dialog and returns the application to its previous state.
- <span id="page-143-1"></span>■ A disclosure button. Clicking it displays the expanded Save dialog.  
<span id="page-143-6"></span><span id="page-143-4"></span>Any custom elements you add go between the Where pop-up menu and the buttons at the bottom of the dialog.  
#### The Expanded Save Dialog  
In contrast with the minimal Save dialog, the expanded Save dialog lets users save documents in locations other than those available in the minimal Save dialog's Where pop-up menu.  
<span id="page-144-0"></span>**Figure 9-11** The expanded Save dialog  
![](images/_page_144_Picture_3.jpeg)  
In addition to the items in the minimal Save dialog, the expanded Save dialog displays the following:  
- Back and forward buttons to navigate back and forth between selections made in the list or column view.
- A sidebar that mirrors the one presented in the Finder.
- <span id="page-144-3"></span><span id="page-144-1"></span>■ A column or list view for navigating the file system.
- A New Folder button, which displays an application-modal dialog that asks the user to name the new folder, and then creates it.
- A Hide Extension checkbox, which allows the user to control whether or not the filename's extension (.jpg, for example) is visible. The Hide Extension checkbox should be selected as the default (that is, filename extensions should not appear in user-visible filenames unless the user requests them).  
<span id="page-144-2"></span>If the user changes the state of the checkbox for a particular document, the next new document should match the last user-selected state, even after the user quits and reopens the application. The filename in the Save As field updates in real time as the checkbox is selected or deselected.  
Don't provide your own options for handling filename extensions; use the standard Open and Save dialogs.  
**Carbon:** Set the PreserveSaveFileExtension flag when calling the Save dialog, and use NavCompleteSave to set the flag to hide the filename extension.  
If you add other elements to customize the expanded Save dialog, they should appear above the Cancel and Save buttons. When the dialog is expanded, custom elements should appear between the file-system browser and the push buttons.  
<span id="page-145-4"></span>In default keyboard navigation mode, pressing Tab in the expanded Save dialog shifts the keyboard focus from the Save As text field to the sidebar, to the visible columns, and then back to the text field.