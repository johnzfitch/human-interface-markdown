<!-- Chunk 311 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 207 -->
<span id="page-255-2"></span>Use an **image well** as a drag-and-drop target for an icon or picture. You could use a set of imagewells to manage thumbnails in a clip-art catalog, for example. Don't use imagewells in place of push buttons or bevel buttons.  
**Figure 14-29** Image wells  
![](images/_page_255_Picture_8.jpeg)  
<span id="page-255-4"></span>Some image wells (the user picture in the Picture pane of Accounts preferences, for example) must always contain an image. If the user can clear an image well (leaving it empty) in your application, provide standard Edit menu commands and Clipboard support.  
**Carbon:** Image wells are available in Interface Builder. To create one programmatically, use CreateImageWellControl.  
**Cocoa:** Image wells are available in Interface Builder. An image well is an NSImageView.