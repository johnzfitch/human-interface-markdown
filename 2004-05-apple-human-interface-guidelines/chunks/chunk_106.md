<!-- Chunk 106 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 957 -->
A document window should display the name of the document being viewed. Application windows display the application name. Utility windows display a descriptive title appropriate for that window. If the contents of the window can change, it might be appropriate to change the title to reflect the current context. For example, in the Keynote inspector, the title of the window changes to reflect which pane has been selected.  
If you need to display more than one item in the title, separate the items with an em dash (—) with space on either side. For example, the main viewer window of Mail displays the currently selected message mailbox and the selected folder, if any. Note that if a message is viewed in its own window, the message title is displayed.  
Don't display pathnames in window titles. When displaying document titles, use the display name and show the extension if the user has selected to show extensions. See *Apple Software Design Guidelines* for more information.  
#### Title Bar Buttons  
Document and application windows always display active close and minimize buttons. (See ["Closing Windows"](#page-119-0) (page 120) and ["Minimizing and Expanding Windows"](#page-118-1) (page 119) for details on what the close and minimize buttons do.) Include the zoom button if the window can be adjusted in size. Information on how the zoom button works is in ["Resizing and Zooming](#page-118-0) [Windows"](#page-118-0) (page 119).  
<span id="page-103-0"></span>Utility windows always display an active close button but never an active minimize button.  
If buttons are not active, they should at least all be present in an inactive state. The exception is utility windows, where it is acceptable to display only one button, the close button.  
Alerts and modal dialogs do not include any of these buttons.  
The title bar should include a toolbar control if a toolbar is available in the window (see ["Toolbars"](#page-107-0) (page 108)).  
<span id="page-104-0"></span>**Figure 8-3** Title bar buttons for standard windows  
![](images/_page_104_Picture_3.jpeg)  
#### <span id="page-104-1"></span>Indicating Changes With the Close Button  
When a document has unsaved changes, the close button should display a dot.  
**Figure 8-4** The close button in its unsaved changes state  
![](images/_page_104_Picture_7.jpeg)  
<span id="page-104-2"></span>**Carbon:** Display the dot with the SetWindowModified function.  
**Cocoa:** The dot appears automatically if the application is NSDocument-based; otherwise, use the setDocumentEdited: method of the NSWindow class.  
#### The Proxy Icon  
Document windows include a **proxy icon** in the title bar after a document is saved for the first time. After pressing a proxy icon for a couple of seconds, users can manipulate it as if they were manipulating the corresponding file-system object. For example, you can attach a document to an email message by dragging its proxy icon into the email message.  
<span id="page-105-0"></span>**Figure 8-5** A proxy icon being dragged to another application  
U U P m D m w  
<span id="page-106-2"></span>A proxy icon appears in its normal state as long as the state of the document and the file-system object are the same. When a document has unsaved changes, its proxy icon appears dimmed. Note the difference between the proxy icon in the document with unsaved changes versus the document with saved changes in Figure 8-6.  
<span id="page-106-0"></span>**Figure 8-6** Proxy icons in documents with saved and unsaved changes  
![](images/_page_106_Figure_4.jpeg)  
<span id="page-106-1"></span>Command-clicking the title or the proxy icon displays a pop-up menu illustrating the document path.  
**Figure 8-7** A document path pop-up menu, opened by Command-clicking the proxy icon  
![](images/_page_106_Picture_7.jpeg)