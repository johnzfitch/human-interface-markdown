<!-- Chunk 169 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 455 -->
<span id="page-143-0"></span>In the minimal Save dialog, users can save changes to an unnamed document, name or rename a document, and choose a frequently accessed location to store it.  
**Figure 9-10** The minimal (collapsed) Save dialog  
![](images/_page_143_Picture_6.jpeg)  
<span id="page-143-4"></span>The minimal Save dialog contains these elements:  
<span id="page-143-5"></span>■ Save As text field for the document name. (Expert users can enter pathnames by pressing Command-Shift-G.)  
If the document has not been saved previously, your application should put the default name (such as "untitled") in this field, and the filename should be selected. If the user has chosen to make the filename extension visible, the extension is not selected.  
<span id="page-143-1"></span>If the document has been saved previously and the user chooses Save As, the Save dialog should open with the document name highlighted in the Save As field. The filename extension (if it is visible) is not selected.  
- Where pop-up menu, containing mounted volumes, the folders in the Finder sidebar, and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically the predefined Documents folder in the user's home folder. (For recommended default locations, see *Apple Software Design Guidelines*.) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- A Save button (default).  
- <span id="page-144-2"></span>■ A Cancel button. Dismisses the dialog and returns the application to its previous state.
- A disclosure button. Clicking it displays the expanded Save dialog.  
Any custom elements you add go between the Where pop-up menu and the buttons at the bottom of the dialog.