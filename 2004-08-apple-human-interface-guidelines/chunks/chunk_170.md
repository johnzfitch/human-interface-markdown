<!-- Chunk 170 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 540 -->
<span id="page-144-0"></span>In contrast with the minimal Save dialog, the expanded Save dialog lets users save documents in locations other than those available in the minimal Save dialog's Where pop-up menu.  
**Figure 9-11** The expanded Save dialog  
![](images/_page_144_Picture_8.jpeg)  
In addition to the items in the minimal Save dialog, the expanded Save dialog displays the following:  
- Back and forward buttons to navigate back and forth between selections made in the list or column view.
- A sidebar that mirrors the one presented in the Finder.
- A column or list view for navigating the file system.
- A New Folder button, which displays an application-modal dialog that asks the user to name the new folder, and then creates it.  
<span id="page-145-1"></span>■ A Hide Extension checkbox, which allows the user to control whether or not the filename's extension (.jpg, for example) is visible. The Hide Extension checkbox should be selected as the default (that is, filename extensions should not appear in user-visible filenames unless the user requests them).  
If the user changes the state of the checkbox for a particular document, the next new document should match the last user-selected state, even after the user quits and reopens the application. The filename in the Save As field updates in real time as the checkbox is selected or deselected.  
<span id="page-145-3"></span>Don't provide your own options for handling filename extensions; use the standard Open and Save dialogs.  
**Carbon:** Set the PreserveSaveFileExtension flag when calling the Save dialog, and use NavCompleteSave to set the flag to hide the filename extension.  
If you add other elements to customize the expanded Save dialog, they should appear above the Cancel and Save buttons. When the dialog is expanded, custom elements should appear between the file-system browser and the push buttons.  
<span id="page-145-2"></span><span id="page-145-0"></span>In default keyboard navigation mode, pressing Tab in the expanded Save dialog shifts the keyboard focus from the Save As text field to the sidebar, to the visible columns, and then back to the text field.