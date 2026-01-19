---
chunk_index: 2283
ref: "1beda9a5a0db"
id: "1beda9a5a0db55677c3a73691742c58cc215e5256342b38142242932a43852aa"
slug: "chunk-104--open"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_104.md"
kind: "markdown"
lines: [19, 26]
token_estimate: 572
content_sha256: "ab742e422352fb2c49554c06372ae26043d346c057d1e88c683e94e7f836e2e9"
compacted: false
heading_path: ["New","Open"]
symbol: null
address: null
asset_path: null
---

#### Open  
The Open command opens an existing document. When the user chooses Open from within your application, display the standard file dialog box. The user selects a document from the list in the dialog box. You can create a custom filter procedure to display all the documents of the types that your application can handle. When the user selects a document, the application opens it. Figure 4-63 shows the standard file dialog box that appears when the user chooses the Open command.  
**Figure 4-63** The standard file dialog box for opening files  
![](images/_page_124_Picture_5.jpeg)  
The user can browse through all levels of the file system from the desktop down through nested folders, and back to the desktop. The Eject button allows the user to eject any removable media such as a 3.5-inch disk or a CD-ROM disc. The Eject button is disabled when there are no removable media selected. The Desktop button allows the user to go immediately to the top level of the hierarchy. The Desktop button is disabled when the user is looking at that level, as shown in Figure 4-63.  
When the user chooses Open while running an application, the standard file dialog box displays all documents that the application can open. The standard file dialog box displays all documents, folders, and storage devices that are available. When the user selects a document and clicks the Open button or double-clicks a document name, the application opens the document.  
When an application starts up by putting an empty, untitled document on the screen, the Open command remains enabled even if the application allows only one open document at a time. In this case, choosing Open from the File menu displays an alert box that informs the user that only one window can be open at a time and asks if it's OK to close the current window. If the user clicks OK, close an empty document or display the save changes alert box for a document with contents; then open the document the user selected. If the user clicks Cancel, the current document remains on the screen in the state it was in before the user chose the Open command.  
Note that you shouldn't set a maximum number of documents that your application can open. You should base the limit on the amount of available memory at any given time.