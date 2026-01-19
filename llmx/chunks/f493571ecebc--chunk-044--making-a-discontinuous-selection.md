---
chunk_index: 715
ref: "f493571ecebc"
id: "f493571ecebc656c319221771ef38284ec693517e8ce20cbe1eacdddc77e0088"
slug: "chunk-044--making-a-discontinuous-selection"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_044.md"
kind: "markdown"
lines: [40, 48]
token_estimate: 565
content_sha256: "2c4dd53c8e70b436a644e595dbaa238347dc74fa26ab471f2f6f627ee4e0c277"
compacted: false
heading_path: ["Selection in General","Selection by Clicking","Range Selection","Making a Discontinuous Selection"]
symbol: null
address: null
asset_path: null
---

#### Making a Discontinuous Selection  
In graphics applications, objects aren't usually considered to be in any particular sequence. A selection is extended by adding objects to it, and the added objects do not have to be adjacent to the objects already selected. The user can add either an individual object or a range of objects to the selection by holding down the Shift key before making the additional  
selection (Shift-click). When this happens, the objects between the current selection and the new object are not automatically included in the selection. This kind of selection is called a **discontinuous selection**. If the user holds down the Shift key and selects one or more objects that are already highlighted, the objects are deselected.  
In the case of graphics, *all* selections are discontinuous selections because graphic objects are discrete. This is not the case with arrays and text, however. In these two kinds of applications, an extended selection made by a Shift-click always includes everything between the old selection and the new endpoint. To provide for discontinuous selection in these applications, Apple-click is included in the human interface.  
To make a discontinuous selection in a text or array application, the user selects the first piece in the usual way and holds down the Apple key before selecting the remaining pieces. Each piece is selected in the same way as if it were the whole selection, but because the Apple key is held down, the new pieces are added to the existing selection instead of replacing it. If one of the pieces selected with Apple-click is already within an existing part of the selection, then instead of being added to the selection it's removed from the selection. Figure 9 shows a sequence in which several pieces are selected and deselected.  
![](images/_page_42_Figure_4.jpeg)  
Figure 9. Discontinuous Selection Within an Array  
Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the  
user to choose a font after making a discontinuous selection, but wouldn't allow the user to type replacement characters (which part of the selection would they replace?).