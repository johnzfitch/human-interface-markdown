---
chunk_index: 885
ref: "ff5168bb9560"
id: "ff5168bb95609c3c50a88598a243bed8401daf37460c435530c58ae1fb2ccebb"
slug: "full-document--making-a-discontinuous-selection"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [932, 949]
token_estimate: 563
content_sha256: "da787af1edac30b6c09eaba83a057a71026f5cb354a19f22655fb76cbee4c59f"
compacted: false
heading_path: ["**Types of Objects**","Selection in General","Selection by Clicking","Making a Discontinuous Selection"]
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