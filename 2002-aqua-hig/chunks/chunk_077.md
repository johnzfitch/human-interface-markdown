<!-- Chunk 77 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 478 -->
<span id="page-69-5"></span><span id="page-69-2"></span>Every document and utility window should have, at a minimum, a title bar and a close button. Even if the window does not have an actual title (a tools palette, for example), it should have a title bar so that users can move the window.  
<span id="page-69-8"></span>A standard document window has  
- <span id="page-69-4"></span>■ a title bar
- a resize control
- <span id="page-69-3"></span>■ scroll bars (if not all the window's contents are visible)
- <span id="page-69-6"></span>■ close, minimize, and zoom buttons, although only the close button must be present at all times  
<span id="page-70-0"></span>**Figure 5-1** Standard window parts  
![](images/_page_70_Picture_3.jpeg)  
<span id="page-70-2"></span>When a document has unsaved changes, the close button should display a dot. Carbon developers should set this control with the SetWindowModified function. In Cocoa, this behavior happens automatically if the application is NSDocument-based; otherwise, use the setDocumentEdited: method of the NSWindow class.  
<span id="page-70-1"></span>**Figure 5-2** The close button in its unsaved changes state  
![](images/_page_70_Picture_6.jpeg)  
<span id="page-71-2"></span>After a document is saved for the first time, a **proxy icon** appears in the title bar. Users can manipulate this icon as if they were manipulating the corresponding file-system object. For example, you can drag a document's proxy icon to a folder in the Finder. A proxy icon appears in its normal state as long as the state of the document and the file system object are the same. When a document has unsaved changes, its proxy icon appears dimmed. Command-clicking the title or the proxy icon displays a pop-up menu illustrating the document path.  
**Figure 5-3** Document path pop-up menu, opened by Command-clicking the proxy icon  
![](images/_page_71_Picture_4.jpeg)