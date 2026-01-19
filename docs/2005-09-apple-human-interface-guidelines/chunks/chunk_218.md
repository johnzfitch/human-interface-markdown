<!-- Chunk 218 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 106 -->
When a document has unsaved changes, the close button should display a dot.  
**Figure 13-4** The close button in its unsaved changes state  
![](images/_page_172_Picture_7.jpeg)  
<span id="page-172-2"></span>**Carbon:** Display the dot with the SetWindowModified function.  
**Cocoa:** The dot appears automatically if the application is NSDocument-based; otherwise, use the setDocumentEdited: method of the NSWindow class.