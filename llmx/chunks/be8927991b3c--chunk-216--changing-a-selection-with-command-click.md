---
chunk_index: 2460
ref: "be8927991b3c"
id: "be8927991b3ce4298589031721e105d983b78765470b9d798da1dd3166ffce6f"
slug: "chunk-216--changing-a-selection-with-command-click"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_216.md"
kind: "markdown"
lines: [28, 35]
token_estimate: 436
content_sha256: "7ecd0e94d04d48c307165780aa336afdf8a43ae16ffb89b239c66cfb2d122d09"
compacted: false
heading_path: ["Selection by Clicking","Selection by Dragging","Changing a Selection With Shift-Click","Changing a Selection With Command-Click"]
symbol: null
address: null
asset_path: null
---

#### Changing a Selection With Command-Click  
In the case of graphics, all selections are discontinuous selections because graphic objects are discrete. This is not the case with arrays and text, in which an extended selection made by a Shift-click always includes everything between the old anchor point and the new active end. In arrays and text, discontinuous selections are made by clicking while holding down the Command key.  
To make a discontinuous selection in a text or array application, the user selects the first piece in the usual way and holds down the Command key while selecting the remaining pieces. Each piece is selected in the same way as if it were the whole selection, but because the Command key is held down, the new pieces are *added* to the existing selection instead of replacing it. If one of the pieces selected with Command-click is already within an existing part of the selection, then instead of being added to the selection, it's removed from the selection.  
Selecting **291**  
Figure 10-18 shows the process of adding cells to and removing cells from a discontinuous selection.  
**Figure 10-18** Discontinuous selection within an array  
Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after making a discontinuous selection, but not allow the user to type replacement characters. In this situation, it wouldn't be apparent to users which part of the selection the characters would replace. Decide what makes sense in the context of your application and test it with users to make sure that their needs are met.  
![](images/_page_315_Picture_6.jpeg)