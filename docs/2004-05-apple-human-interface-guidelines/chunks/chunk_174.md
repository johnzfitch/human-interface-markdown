<!-- Chunk 174 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 200 -->
<span id="page-179-2"></span>Use an **image well** as a drag-and-drop target for an icon or picture. You could use a set of image wells to manage thumbnails in a clip-art catalog, for example. Don't use image wells in place of push buttons or bevel buttons.  
**Figure 10-29** Image wells  
![](images/_page_179_Picture_9.jpeg)  
Some image wells (the user picture in the Picture pane of Accounts preferences, for example) must always contain an image. If the user can clear an image well (leaving it empty) in your application, provide standard Edit menu commands and Clipboard support.  
**Carbon:** Image wells are available in Interface Builder. To create one programmatically, use CreateImageWellControl.  
**Cocoa:** Image wells are available in Interface Builder. An image well is an NSImageView.