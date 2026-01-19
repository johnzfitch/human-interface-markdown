<!-- Chunk 110 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 432 -->
The minimal Save dialog enables users to save changes to a particular document, to name or rename the document, and to choose a frequently accessed location to store it.  
<span id="page-101-1"></span>**Figure 6-5** The minimal (collapsed) Save dialog  
![](images/_page_101_Picture_7.jpeg)  
The minimal Save dialog contains these elements:  
■ "Save as" text field for the document name. (Expert users can enter pathnames by typing "/" or "~" as the first character.)  
If the document has not been saved previously, your application should put the default name (such as "untitled") in this field, and the filename should be selected. If the user has chosen to make the filename extension visible, the extension is not selected.  
<span id="page-102-1"></span>If the document has been saved previously and the user chooses Save As, the Save dialog should open with the document name, highlighted, in the "Save as" field. The filename extension (if it is visible) is not selected.  
- Where pop-up menu, containing Favorite Places (all folders in the user's Favorites folder) and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically the predefined Documents folder in the user's home folder. (For recommended default locations, see ["File Location" \(page 235\).](#page-234-0)) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- Save button (default).
- Cancel button. Dismisses the dialog and returns to the application's previous state.
- <span id="page-102-4"></span><span id="page-102-3"></span>■ A disclosure button. Clicking it displays the expanded Save dialog.