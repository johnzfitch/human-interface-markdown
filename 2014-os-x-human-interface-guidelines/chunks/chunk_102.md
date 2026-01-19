<!-- Chunk 102 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 1430 -->
Users expect to be able to specify a title and save location when they choose to save a document for the first time. To perform the initial save, users expect to see the standard Save dialog.  
**Note:** As much as possible, help users stop worrying about the save state of their content. In particular, you want them to stop thinking that they must continually choose File > Save in order to avoid losing their work.  
Although users see a Save dialog the first time they want to name and place their document, they should seldom—if ever—see a Save dialog while they continue to work on the document.  
The Save dialog hastwo states: minimal (also known as collapsed) and expanded. Clicking the disclosure button toggles between these states. For example, in the minimal Save dialog (shown here displayed by TextEdit), you can see the closed disclosure button to the right of the document title.  
![](images/_page_167_Picture_4.jpeg)  
The minimal Save dialog contains these elements:  
- The Save As text field, in which users enter the document name. Expert users can enter pathnames by pressing Command-Shift-G. (Note that the pathname separator is the "/" character.)
- The Where pop-up menu, which contains mounted volumes, folders in the Finder sidebar, and Recent Places (which are the five most recent folders the user opened or saved documents to).
- A Save button (this is the default button).
- A Cancel button, which dismisses the dialog and returns the app to its previous state.  
- A disclosure button. Clicking it displays the expanded Save dialog. (For more information about how to use disclosure buttons, see [Disclosure](#page-185-0) Button (page 186).)
- An optional accessory view, which can contain information such as text encoding settings. (In general, the accessory view should not be necessary.)  
The expanded Save dialog gives users a broader view of the file system than they get in the minimal Save dialog's Where pop-up menu. For example, the expanded TextEdit Save dialog displaysthe browsable file-system view.  
![](images/_page_168_Picture_4.jpeg)  
In addition to the items in the minimal Save dialog, the expanded Save dialog includes the following:  
- Back and Forward buttons to navigate back and forth between selections made in the list or column view.
- A source list that mirrors the Finder sidebar.  
- Options for navigating the file system.
- A File Format (or Format) pop-up menu, which displays a list of file formatsfrom which the user can choose.
- A New Folder button, which displays an app-modal dialog that asks the user to name the new folder, and then creates it.
- A "Hide extension" checkbox, which allows the user to control whether or not the filename's extension (.jpg, for example) is visible.  
In addition to the Save dialog, a document-based app can display the close confirmation save dialog. The close confirmation save dialog (shown when users close a document window that contains data that has never been saved) has the same minimal and expanded states as the standard Save dialog. For example, TextEdit displays the close confirmation save dialog when the user closes a new document window with unsaved changes.  
![](images/_page_169_Picture_6.jpeg)  
As with the standard Save dialog, the close confirmation save dialog includes a disclosure button to the right of the Save As text field. Clicking this button expands the dialog to show a similar browsable file system view. The differences between the close confirmation save dialog and the standard Save dialog are due to the fact that it's unclear whether the user intends to discard their work. For this reason, the text at the top of the dialog explains why it has appeared, and the Don't Save button at the bottom of the dialog allows the user to decline to save their work.  
There are a few ways in which you can customize a Save dialog so that it provides a better user experience.  
**Specify a reasonable defaultlocation.** The default location appearsin the Where pop-up menu (in the minimal Save dialog) and in the Finder view (in the expanded Save dialog). Typically, the default location is one of the predefined folders in the user's home folder. If the user selects a different folder, make sure you remember the user's selection so that it appears the next time the dialog is displayed.  
**Allow users to choose whetherto view the file extension.** Select the "Hide extension" checkbox asthe default (that is, filename extensions should not appear in user-visible filenames unless the user requests them). If the user changes the state of the checkbox for a particular document, the next new document should match the last user-selected state, even after the user quits and reopensthe app. The filename in the Save Asfield updates in real time as the checkbox is selected or deselected.  
**Display the default new document name before users save the document for the first time.** In general, this name should be "untitled." In the Save As field, display the default name as selected so that users can easily replace it with a custom name. If the user chooses to make the filename extension visible, the extension is not selected.  
**Display custom UI elements below the location-selection elements.** In the minimal Save dialog, custom UI elements go between the Where pop-up menu and the buttons at the bottom of the dialog. In the expanded Save dialog, custom elements go between the file-system browser and the buttons at the bottom of the dialog.  
**Note:** In default keyboard navigation mode, pressing Tab in the expanded Save dialog shifts the keyboard focus from the Save As text field to the source list, to the visible columns, and then back to the text field.