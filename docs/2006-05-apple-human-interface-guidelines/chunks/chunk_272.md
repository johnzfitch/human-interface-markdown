<!-- Chunk 272 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 477 -->
In the minimal Save dialog, users can save changes to an unnamed document, name or rename a document, and choose a frequently accessed location to store it.  
<span id="page-219-0"></span>**Figure 13-39** The minimal (collapsed) Save dialog  
![](images/_page_219_Picture_5.jpeg)  
The minimal Save dialog contains these elements:  
- <span id="page-219-5"></span><span id="page-219-4"></span>■ Save As text field for the document name. Expert users can enter pathnames by pressing Command-Shift-G. (Note that the pathname separator is the "/" character.)
- If the document has not been saved previously, your application should put the default name (such as "untitled") in this field, and the filename should be selected. If the user has chosen to make the filename extension visible, the extension is not selected.
- If the document has been saved previously and the user chooses Save As, the Save dialog should open with the document name highlighted in the Save As field. The filename extension (if it is visible) is not selected.
- <span id="page-219-2"></span>■ Where pop-up menu, containing mounted volumes, the folders in theFinder Sidebar, and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typicallythe predefined Documents folderin the user's home folder. If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- <span id="page-219-1"></span>■ A Save button (default).
- A Cancel button. Dismisses the dialog and returns the application to its previous state.
- A disclosure button. Clicking it displays the expanded Save dialog. (For more information about how to use disclosure buttons, see ["Disclosure](#page-273-0) Buttons" (page 274).)  
Any custom elements you add go between the Where pop-up menu and the buttons at the bottom of the dialog.