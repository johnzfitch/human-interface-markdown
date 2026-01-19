---
chunk_index: 1418
ref: "08a93abed62b"
id: "08a93abed62bf173b91bb72edbfa54cdbb9d132ba27fa0eadc0cd602eccb2dc5"
slug: "full-document--making-a-discontinuous-selection"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1743, 1757]
token_estimate: 549
content_sha256: "fde8d66f843bb96097078b834b60ee856a7d95d5f15cf3ce90e8abf957369ac7"
compacted: false
heading_path: ["Selection in general","Range selection","Extending a selection","Making a discontinuous selection"]
symbol: null
address: null
asset_path: null
---

#### Making a discontinuous selection

In graphics applications, objects aren't usually considered to be in any particular sequence. A selection is extended by adding objects to it, and the added objects do not have to be adjacent to the objects already selected. The user can add either an individual object or a range of objects to the selection by holding down the Shift key before making the additional selection (Shift-click). When the user does this, the objects between the current selection and the new object are not automatically included in the selection. This kind of selection is called a **discontinuous selection**. If the user holds down the Shift key and selects one or more objects that are already highlighted, the objects are deselected.

In the case of graphics, *all* selections are discontinuous selections because graphic objects are discrete. This is not the case with arrays and text, in which an extended selection made by a Shift-click always includes everything between the old selection and the new endpoint. In arrays and text, the Apple-click is function provides for discontinuous selection.

To make a discontinuous selection in a text or array application, the user selects the first piece in the usual way and holds down the Apple key while selecting the remaining pieces. Each piece is selected in the same way as if it were the whole selection, but because the Apple key is held down, the new pieces are *added to* the existing selection instead of replacing it. If one of the pieces selected with Apple-click is already within an existing part of the selection, then instead of being added to the selection it's removed from the selection. Figure 55 shows a sequence in which several pieces are selected and deselected.

![](images/_page_121_Figure_0.jpeg)

Figure 55
Discontinuous selection within an array

Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after making a discontinuous selection, but wouldn't allow the user to type replacement characters (which part of the selection would they replace?).