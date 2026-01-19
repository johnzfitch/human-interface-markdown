<!-- Chunk 234 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 2604 -->
This section describes the standard dialogs that you use when a user is saving a document for the first time, closing a document, or quitting an application.  
#### <span id="page-246-1"></span>Save Dialogs  
An application that saves the contents of individual windows—which would be most text and graphics applications—should use document-specific sheets for its Save dialogs. In a Save dialog, users can save a document for the first time or change the name or location (or both) of a previously saved document.  
<span id="page-246-3"></span>The Save dialog hastwo states: minimal and expanded. Clicking the disclosure button toggles between these states. If the user changes the state, the next Save dialog should open in the selected state.  
Your application should pass in a filename extension as part of every filename. Users can control its visibility using the Hide Extension checkbox in the expanded Save dialog; see [Figure](#page-217-1) 14-30 (page 218). Existing documents do not get extensions added to or removed from their filenames unless the user chooses Save As and changes the setting in the Save dialog.  
#### <span id="page-246-4"></span>**The Minimal Save Dialog**  
<span id="page-246-0"></span>In the minimal Save dialog (shown in Figure 14-57), users can specify a name and choose a frequently accessed location to store a document.  
**Figure 14-57** The minimal (collapsed) Save dialog  
![](images/_page_246_Picture_9.jpeg)  
The minimal Save dialog contains these elements:  
<span id="page-246-6"></span><span id="page-246-5"></span>● Save As text field for the document name. Expert users can enter pathnames by pressing Command-Shift-G. (Note that the pathname separator is the "/" character.)  
If the document has not been saved previously, your application should put the default name (such as "untitled") in this field, and the filename should be selected. If the user has chosen to make the filename extension visible, the extension is not selected.  
<span id="page-246-2"></span>If the document has been saved previously and the user chooses Save As, the Save dialog should open with the document name highlighted in the Save As field. The filename extension (if it is visible) is not selected.  
- Where pop-up menu, containing mounted volumes, the folders in the Finder sidebar, and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically the predefined Documents folder in the user's home folder. If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- A Save button (default).
- A Cancel button. Dismisses the dialog and returns the application to its previous state.  
<span id="page-247-1"></span>● A disclosure button. Clicking it displays the expanded Save dialog. (For more information about how to use disclosure buttons, see ["Disclosure](#page-330-0) Buttons" (page 331).)  
Any custom elements you add go between the Where pop-up menu and the buttons at the bottom of the dialog.  
#### <span id="page-247-3"></span><span id="page-247-2"></span>**The Expanded Save Dialog**  
<span id="page-247-0"></span>In contrast with the minimal Save dialog, the expanded Save dialog lets users save documents in locations other than those available in the minimal Save dialog's Where pop-up menu. An example of the expanded Save dialog is shown in Figure 14-58.  
**Figure 14-58** The expanded Save dialog  
![](images/_page_247_Picture_7.jpeg)  
In addition to the items in the minimal Save dialog, the expanded Save dialog displays the following:  
- Back and forward buttons to navigate back and forth between selections made in the list or column view.
- A source list that mirrors the Finder sidebar.
- A column or list view for navigating the file system.
- A File Format (or Format) pop-up menu, which displays a list of file formats from which the user can choose.
- A New Folder button, which displays an application-modal dialog that asks the user to name the new folder, and then creates it.  
<span id="page-248-0"></span>● A "Hide extension" checkbox, which allows the user to control whether or not the filename's extension (.jpg, for example) is visible. The "Hide extension" checkbox should be selected as the default (that is, filename extensions should not appear in user-visible filenames unless the user requests them).  
<span id="page-248-3"></span>If the user changes the state of the checkbox for a particular document, the next new document should match the last user-selected state, even after the user quits and reopens the application. The filename in the Save As field updates in real time as the checkbox is selected or deselected.  
If you add other elements to customize the Save dialog, they should appear above the Cancel and Save buttons. When the dialog is expanded, custom elements should appear between the file-system browser and the push buttons.  
<span id="page-248-1"></span>In default keyboard navigation mode, pressing Tab in the expanded Save dialog shifts the keyboard focus from the Save As text field to the source list, to the visible columns, and then back to the text field.  
#### <span id="page-248-7"></span>Closing a Document With Unsaved Changes  
<span id="page-248-5"></span>When the user attempts to close a document that has unsaved changes, present a Save Changes alert. An application that saves the contents of individual windows—such as most text and graphics applications—should use document-specific sheets, like the one shown in [Figure](#page-235-0) 14-46 (page 236) for its Save Changes alert.  
In an application that can display multiple views of the same file, if the user chooses the Close File command instead of Close Window, you should use an application-modal dialog instead of a sheet. This emphasizes the fact that the user's actions affect the file as a whole, not just the portion displayed in the current view. In this situation, change the word "document" in the Save Changes alert message to the word "file". After the user clicks Save or Don't Save, close all open views of the file.  
<span id="page-248-4"></span>When a Save Changes sheet is open, the document's close button and the Close command in the File menu are unavailable; the user can't close the document until the Save Changes sheet is addressed.  
#### Attempting to Save a Locked or Read-Only Document  
<span id="page-248-6"></span><span id="page-248-2"></span>If the user edits a locked or read-only document and then quits the application or chooses Save, do not display the standard Save Changes alert. Instead, display a sheet explaining that because the document is read-only, it cannot be saved. The sheet should then offer the user the options of saving a copy, rejecting the changes, or continuing to view or edit the document.  
#### Saving Documents During a Quit Operation  
Users can interrupt a quit operation with documents still unsaved. For example, if a user chooses Quit and a save alert (a sheet) opens for a document, the user can work on other documents or switch to another application without addressing the save alert.  
When a user quits an application in which all open documents have been saved, all documents close immediately and the application quits.  
#### **Quitting an Application That Is Not Document-Based**  
When a user attempts to quit an application that is not document-based but that has many windows whose contents are saved simultaneously, present an application-modal Save Changes alert, such as the one shown in Figure 14-59.  
<span id="page-249-0"></span>**Figure 14-59** A Save Changes alert for an application that is not document-based  
![](images/_page_249_Picture_5.jpeg)  
#### **Quitting an Application With Multiple Unsaved Documents Open**  
<span id="page-249-1"></span>When a user attempts to quit a document-based application and there is more than one document with unsaved changes open, present an application-modal Review Changes alert,such asthe one shown in Figure 14-60.  
<span id="page-249-2"></span>**Figure 14-60** The Review Changes (application-modal) alert that appears when the user quits with more than one unsaved document open  
![](images/_page_249_Picture_9.jpeg)  
<span id="page-249-3"></span>The appropriate action for each button is as follows:  
- **Discard Changes**. Closes all documents without saving changes and quits the application.
- **Cancel**. Cancels the Quit command.
- **Review Changes**. All open documents (including those minimized in the Dock) come forward, with the unsaved documents on top. The active document presents a Save Before Quitting alert. If the user clicks Save, the Save dialog appears (if the document has not previously been saved). If the user clicks Don't Save, the next unsaved document comesforward with its Save Before Quitting alert. If the user dismisses the last Save Before Quitting alert with Save or Don't Save, all documents close and the application quits.  
During the review, if the user activates another unsaved document, it should come forward with its Save Before Quitting sheet open. Save Before Quitting sheets on other documents remain open. During the review, if the user activates a saved document, the review process continues when the next unsaved document becomes active.  
<span id="page-250-2"></span>If, in the midst of a quit operation, the user clicks the application icon in the Dock or chooses Bring All to Front from the Window menu, documents should appear in this order: documents with open sheets on top, unsaved documents next, and then saved documents.  
<span id="page-250-4"></span>At any time during the review process, the user can click Cancel to stop the quit operation. If the user initiates a Quit command during the review process, the process begins again with the application-modal alert shown in Figure 14-60.  
#### **Saving a Document With the Same Name as an Existing Document**  
<span id="page-250-5"></span><span id="page-250-1"></span>If the user types the name of a document that already exists in the same location into the Save As field of a Save dialog, and then clicks Save, present an application-modal alert in which the user can confirm whether or not to replace the previous document.  
**Figure 14-61** Alert for confirming replacing a file  
![](images/_page_250_Picture_8.jpeg)