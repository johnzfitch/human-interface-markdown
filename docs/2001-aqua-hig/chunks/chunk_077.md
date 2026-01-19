<!-- Chunk 77 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 459 -->
<span id="page-68-5"></span><span id="page-68-2"></span>Every document and utility window should have a title bar and a close button. Even if the window does not have an actual title (a tools palette, for example), the user should be able to move the window by dragging the title bar.  
<span id="page-68-7"></span>A standard document window has  
- <span id="page-68-4"></span>■ a title bar
- a resize control
- <span id="page-68-3"></span>■ scroll bars (if not all the window's contents are visible)
- <span id="page-68-6"></span>■ close, minimize, and zoom buttons, although only the close button must be present at all times  
<span id="page-68-1"></span>**Figure 5-1** Standard window parts  
![](images/_page_68_Picture_10.jpeg)  
<span id="page-69-3"></span>When a document has unsaved changes, the close button displays a dot. Carbon developers can set this control with the SetWindowModified function. In Cocoa, use the setDocumentEdited: method in the NSWindow class.  
<span id="page-69-1"></span>**Figure 5-2** The close button in its unsaved changes state  
![](images/_page_69_Picture_4.jpeg)  
<span id="page-69-5"></span>After a document is saved for the first time, a **proxy icon** appears in the title bar. Users can manipulate this icon as if they were manipulating the corresponding file-system object. For example, you can drag a document's proxy icon to a folder in the Finder. A proxy icon appears in its normal state as long as the state of the document and the file system object are the same. When a document has unsaved changes, its proxy icon appears dimmed. Command-clicking the title or the proxy icon displays a pop-up menu illustrating the document path.  
<span id="page-69-2"></span>**Figure 5-3** Document path pop-up menu, opened by Command-clicking the proxy icon  
![](images/_page_69_Picture_7.jpeg)