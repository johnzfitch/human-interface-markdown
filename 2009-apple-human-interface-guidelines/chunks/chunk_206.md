<!-- Chunk 206 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1302 -->
All windows should have a title bar even if the window doesn't have a title (which should be a very rare exception). In Mac OS X v10.5 and later, all windows display the title bar unified with the toolbar, if a toolbar is present. The following sections describe the components of the title bar.  
#### The Window Title  
A document window should display the name of the document being viewed. Application windows display the application name. Panels display a descriptive title appropriate for that window. If the contents of the window can change, it might be appropriate to change the title to reflect the current context. For example, in the Keynote inspector panel, the title of the window changes to reflect which pane has been selected.  
If you need to display more than one item in the title, separate the items with an em dash (—) with space on eitherside. For example, the main viewer window of Mail displaysthe currently selected message mailbox and the selected folder, if any. When a message is viewed in its own window, the message title is displayed.  
Don't display pathnames in window titles. When displaying document titles, use the display name and show the extension if the user has elected to show extensions. If you need to display a path in the body of a window you can use the path control, described in "Path [Controls"](#page-297-0) (page 298).  
The only controlsthat belong in a title bar are the close, minimize, and zoom buttons. If a title bar is combined with a toolbar, the unified area can contain the toolbar control and the toolbar customization contextual menu (these controls are described in "Title Bar [Buttons"](#page-197-1) (page 198)). Do not place other controls in a title bar.  
Window Elements **197**  
#### <span id="page-197-1"></span>Title Bar Buttons  
Document and application windows always display active close and minimize buttons. (See ["Closing](#page-220-1) [Windows"](#page-220-1) (page 221) and ["Minimizing](#page-220-0) and Expanding Windows" (page 221) for details on what the close and minimize buttons do.) Include the zoom button if the window can be adjusted in size. Information on how the zoom button works is in "Resizing and Zooming [Windows"](#page-219-1) (page 220).  
<span id="page-197-2"></span>Panels always display an active close button but never an active minimize button.  
If buttons are not active, they should at least all be present in an inactive state. The exception is in panels, where it is acceptable to display only one button, the close button. For more information on panels, including information on their title bar buttons, see ["Panels"](#page-226-0) (page 227).  
Alerts and modal dialogs do not display any of these buttons.  
<span id="page-197-0"></span>The title barshould include a toolbar control if a toolbar is present in the window (see ["Toolbars"](#page-199-0) (page 200)). Figure 14-7 shows the appropriate configurations of title bar buttons for standard windows (and alerts and modal dialogs); [Figure](#page-228-1) 14-39 (page 229) shows appropriate title bar button configurations for panels.  
**Figure 14-7** Title bar buttons for standard windows  
![](images/_page_197_Picture_9.jpeg)  
#### Indicating Changes with the Close Button  
<span id="page-198-0"></span>When a document has unsaved changes, the close button should display a dot, as shown in Figure 14-8.  
**Figure 14-8** The close button in its unsaved changes state  
![](images/_page_198_Picture_5.jpeg)  
#### <span id="page-198-3"></span>The Proxy Icon  
<span id="page-198-1"></span>Document windows can include a **proxy icon** in the title bar after the content is saved for the first time. After pressing a proxy icon for a brief period, users can manipulate it asif they were manipulating the corresponding file-system object. For example, you can attach a document to an email message by dragging its proxy icon into the email message, as shown in Figure 14-9.  
**Figure 14-9** A proxy icon being dragged to another application  
![](images/_page_198_Picture_9.jpeg)  
<span id="page-198-2"></span>A proxy icon appears in its normal state as long as the state of the document and the file-system object are the same. When a document has unsaved changes, its proxy icon appears dimmed. Note the difference between the proxy icon in the document with unsaved changes versus the document with saved changes in Figure 14-10.  
<span id="page-199-1"></span>**Figure 14-10** Proxy icons in windows with saved and unsaved changes  
![](images/_page_199_Picture_3.jpeg)  
<span id="page-199-2"></span>Command-clicking the title or the proxy icon displays a pop-up menu illustrating the document path (note that you do not place a standard pop-up menu control in the title bar to provide this behavior). As shown in Figure 14-11, the document path displays the document itself and all containing folders up to the volume that contains the user's home directory. Because Mac OS X is a multiple-user environment, it's especially important to show the complete path of a document to avoid confusion.  
**Figure 14-11** A document path pop-up menu, opened by Command-clicking the proxy icon  
![](images/_page_199_Picture_6.jpeg)