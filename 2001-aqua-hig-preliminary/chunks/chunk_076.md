<!-- Chunk 76 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 1831 -->
Initiated by a Close or Quit command, the Save Changes dialog enables users to save changes (or not) to a particular document or application.  
The Save Changes dialog contains these elements:  
- application icon
- Save button (default). Dismisses the dialog and does one of the following:  
- If the document has been previously saved, changes are saved and the document closes.
- If the document has never been saved, the Save Location dialog appears. (See [Figure 6-5.](#page-81-1))
- Cancel button. Dismisses the dialog and returns to the application's previous state.
- Don't Save button. Dismisses the dialog and closes the document without saving changes. Since this button can cause data loss, position it away from the "safe" buttons.  
#### <span id="page-80-1"></span><span id="page-80-0"></span>The Save Location Dialog  
The Save Location dialog is a sheet that enables the user to specify a name and location for a document. If the document has not been saved previously, and the user clicks Save on the Save Changes dialog ([Figure 6-1 \(page 73\)](#page-72-2)), the Save Changes sheet is replaced with the Save Location sheet.  
The Save Location dialog has two states, collapsed and expanded. The collapsed state allows the user to enter a name and choose a frequently accessed location. The collapsed Save dialog has these elements:  
- "Save as" text field for the document name. (Users can enter pathnames by typing "/" or "~" as the first character.)
- Where pop-up menu, containing Favorite Places (all folders in the user's Favorites folder) and Recent Places (the five most recent folders into which the user saved documents). Your application specifies the default location, typically the Documents folder or the last user-selected location.
- <span id="page-80-2"></span>■ Cancel button and Save (default) button
- a disclosure triangle  
Dialog Behavior **81**  
<span id="page-81-1"></span><span id="page-81-0"></span>**Figure 6-5** The minimal ("collapsed") Save Location sheet  
![](images/_page_81_Picture_3.jpeg)  
Clicking the disclosure triangle displays the following:  
- a column browser for navigating the file system
- an Add to Favorites button, which adds an alias of the chosen folder to the user's Favorites folder and immediately updates the Favorite Places list in the Where pop-up menu. The Add to Favorites button is always available.
- a New Folder button, which displays a dialog that asks the user to name the new folder.  
<span id="page-82-0"></span>**Figure 6-6** The expanded Save Location dialog  
![](images/_page_82_Picture_3.jpeg)  
To enable the user to specify the document's format, you can add a Format pop-up menu between the "Save as" text field and the Where pop-up menu. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types, and specify the default format to show when the dialog opens.  
<span id="page-82-1"></span>If you add other elements to customize the Save Location dialog, they appear above the Cancel and Save buttons. All custom elements should be visible in the dialog's collapsed state, below the Where pop-up menu.  
Pressing Tab in the Save dialog shifts the keyboard focus from the "Save as" text field to the visible columns, and then back to the text field.  
Dialog Behavior **83**  
#### <span id="page-83-0"></span>Closing a Document With Unsaved Changes  
When the user attempts to close a document that has unsaved changes, present a Save Changes dialog, which should be a document-modal sheet.  
When a document-modal Save Changes sheet is open, the document's close button and the Close command in the File menu are unavailable, so that the user can't close the document until the Save dialog is addressed.  
#### <span id="page-83-1"></span>Saving a Document With the Same Name as an Existing Document  
<span id="page-83-5"></span>If the user types an existing document name into the "Save as" field and clicks Save, present an application-modal dialog that enables the user to confirm whether or not to replace the previous document.  
<span id="page-83-3"></span>**Figure 6-7** Replace confirmation dialog  
![](images/_page_83_Picture_8.jpeg)  
#### <span id="page-83-4"></span><span id="page-83-2"></span>Saving Documents During a Quit Operation  
In Mac OS X, users can interrupt a quit operation. For example, if a user chooses Quit and a Save sheet opens for a document, the user can work on other documents or switch to another application without addressing the Save dialog. To minimize the impact of such interruptions, all Save Changes dialogs initiated by a Quit command should include a message that alerts users that they are in the midst of a quit operation. (See [Figure 6-8 \(page 85\)](#page-84-3) for an example.)  
When a user quits an application in which all open documents have been saved, all documents close immediately and the application quits.  
#### **Quitting an Application With One Unsaved Document Open**  
When a user attempts to quit your application and there is only one document with unsaved changes open, present the "save before quitting?" dialog as a sheet attached to the unsaved document, perform the actions described in the section ["The Save Changes Dialog" \(page 80\),](#page-79-2) and then quit the application as appropriate.  
<span id="page-84-3"></span><span id="page-84-0"></span>**Figure 6-8** Dialog (sheet) when user quits with only one unsaved document  
![](images/_page_84_Picture_5.jpeg)  
#### **Quitting an Application With Multiple Unsaved Documents Open**  
When a user attempts to quit your application and there is more than one document with unsaved changes open, present the application-modal "save before quitting?" dialog.  
<span id="page-84-2"></span><span id="page-84-1"></span>**Figure 6-9** Dialog when user quits with unsaved documents (application modal)  
![](images/_page_84_Picture_9.jpeg)  
Dialog Behavior **85**  
The appropriate action for each button is as follows:  
- **Don't Save Any.** Closes all documents without saving changes and quits the application.
- **Cancel.** Cancels the Quit command.
- **Review Unsaved.** All open documents (including those minimized in the Dock) come forward, with the unsaved documents on top. The active document presents the Save sheet; if the user clicks Save or Don't Save, the next unsaved document comes forward with its Save sheet. If the user dismisses the last Save sheet with Save or Don't Save, all documents close and the application quits.  
During the review, if the user activates another unsaved document, it should come forward with its Save Changes sheet open. Already-opened Save sheets on other documents remain open.  
If, in the midst of a quit operation, the user clicks the application icon in the Dock or chooses "Bring All to Front," documents should appear in this order: documents with open sheets on top, unsaved documents next, and then saved documents.  
<span id="page-85-2"></span><span id="page-85-1"></span>At any time during the review process, the user can click Cancel to stop the quit operation. If the user initiates a Quit command while in the review state, the process begins again with the application-modal alert shown in [Figure 6-9](#page-84-2) [\(page 85\).](#page-84-2)