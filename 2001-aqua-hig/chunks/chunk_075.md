<!-- Chunk 75 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 411 -->
<span id="page-64-4"></span><span id="page-64-3"></span>In a Style or Font menu, you can display menu items in the actual style or font so users can see what effect the text attribute will have.  
Don't use text styles in menus other than a Style or Font menu.  
<span id="page-64-1"></span>**Figure 4-15** A Font menu displayed with different fonts  
![](images/_page_64_Picture_11.jpeg)  
<span id="page-66-5"></span><span id="page-66-0"></span>Windows provide a way for people to view and interact with their data. There are various kinds of windows, each with its own function and appearance.  
<span id="page-66-1"></span>**Document windows** contain file-based user data. They present a view into the content that people create and store. If the document is larger than the window, the window shows a portion of the document's contents.  
<span id="page-66-2"></span>Other windows, commonly called **utility windows**, float above other windows and provide tools or controls that users can work with while documents are open. Some utility windows are system-wide (such as those of type kUtilityWindowClass in Carbon). To create windows such as tools palettes in Carbon, use kFloatingWindowClass. In Cocoa, create a window specifying NSUtilityWindowMask as the style mask or call setFloatingPanel:YES.  
<span id="page-66-4"></span><span id="page-66-3"></span>Some applications are not document-based. Such applications typically still have at least one main window, which can use the standard Aqua document window features.  
**Note:** Dialogs and alerts are also types of windows; they are discussed in ["Dialogs" \(page 91\).](#page-90-0)