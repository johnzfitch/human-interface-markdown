<!-- Chunk 72 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 966 -->
Using Open from an application, the user can open only a document that can be processed by that application. To open a document that can be processed only by some other application, the user must ordinarily leave the application and return to the Finder. Using Open from the Finder, the user can open any document—the appropriate application is automatically opened as well.  
When an application starts up by putting an empty untitled document on the screen, the Open option can remain enabled (not dimmed) even if the application allows only one open document at a time. In this case, choosing Open from the File menu simultaneously closes the empty document (why save an empty document?) and opens another.  
#### Close  
Closes the active window, which may be a document window, a desk accessory, or any other type of window. Clicking in a window's close box is the same as choosing Close.  
When the user chooses Close or Quit, and the active document has been changed since the last save, the Close dialog box appears, asking Save changes before closing? A great deal of work can be lost if a user mistakenly clicks No instead of Yes. To avoid confusion, all applications should use the same standard Close dialog box. This is especially important to users who often move from one application to another and become less aware of subtle differences between applications.  
![](images/_page_84_Picture_6.jpeg)  
Figure 34 35 Standard Close dialog box  
Yes and No, the two direct responses to the question, are placed together on the left side of the box. Yes is the default button. Cancel, which cancels Close, is to the right, separate from Yes and No.  
The text of the question is generally Save changes before closing? but if the user sees this message after choosing Quit, the text would instead be Save changes before quitting? If the application supports multiple windows, the text is Save changes to [document name] before closing? Regardless of the text of the question, the box should always look the same and appear in the same place on the screen.  
#### Save  
Lets the user save the active document to disk, including any changes made to that document since the last time it was saved. The document remains open. Users appreciate seeing, at this point, a message telling them the document is indeed being saved.  
If the user chooses Save for a new untitled document (one the user hasn't named yet), the application presents the Save As dialog box (see below). This dialog box allows the user to name the document and choose where it will be saved before the application continues with the save. The active document remains active.  
If there's not enough room on the disk to save the document, the application says so. The application then suggests that the user can choose Save As instead, to save the document on another disk.  
#### Save As  
Saves a copy of the active document under a new name provided by the user. When the user opens a document, makes changes to it, and then chooses Save As, the changes are not made to the original document. The changed version of the document is saved under the new name. The active document is no longer the one the user opened, but rather the new one with the new name.  
If no changes had been made to the original document when Save As was chosen, then there are two identical documents having different names.  
#### Revert to Saved  
Discards all changes made to the active document since the last time it was saved or opened. The document on disk is reopened. Before all this happens, a dialog box lets the user confirm that this is what he or she really wants. (This follows the principles that users be allowed to make informed decisions and to change their minds.) Figure 35 shows a Revert to Saved dialog box.  
![](images/_page_86_Figure_2.jpeg)  
Figure 35 36 A Revert to Saved dialog box