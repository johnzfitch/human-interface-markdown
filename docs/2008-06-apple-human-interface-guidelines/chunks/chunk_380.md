<!-- Chunk 380 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 216 -->
Use an **image well** as a drag-and-drop target for an icon or picture. You could use a set of image wells to manage thumbnailsin a clip-art catalog, for example. Don't use image wellsin place of push buttons or bevel buttons. Figure 15-41 shows the image well in Accounts preferences.  
<span id="page-291-1"></span>**Figure 15-41** An image well in a preferences pane  
![](images/_page_291_Picture_3.jpeg)  
<span id="page-291-3"></span>Some image wells (the user picture in the Password pane of Accounts preferences, for example) must always contain an image. If the user can clear an image well (leaving it empty) in your application, provide standard Edit menu commands and Clipboard support.  
<span id="page-291-0"></span>Image wells are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSImageView class.