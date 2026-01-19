<!-- Chunk 229 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 106 -->
When a document has unsaved changes, the close button should display a dot.  
**Figure 13-4** The close button in its unsaved changes state  
![](images/_page_180_Picture_8.jpeg)  
<span id="page-180-2"></span>**Carbon:** Display the dot with the SetWindowModified function.  
**Cocoa:** The dot appears automatically if the application is NSDocument-based; otherwise, use the setDocumentEdited: method of the NSWindow class.