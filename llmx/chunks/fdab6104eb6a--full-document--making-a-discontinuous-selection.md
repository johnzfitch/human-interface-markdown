---
chunk_index: 534
ref: "fdab6104eb6a"
id: "fdab6104eb6aa260fc87757871a3f1da1fb146948cc633ffaf55e626559708e8"
slug: "full-document--making-a-discontinuous-selection"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1281, 1290]
token_estimate: 216
content_sha256: "cd04617e0bbb243b8e6c878124598004582a1c7bf6637224143a7d575e0581d5"
compacted: false
heading_path: ["Making a Discontinuous Selection"]
symbol: null
address: null
asset_path: null
---

# Making a Discontinuous Selection

In graphics applications, objects aren't usually considered to be in any particular sequence. Therefore, the user can use Open-Apple-click to extend a selection by a single object, even if that object is nowhere near the current selection. When this happens, the objects between the current selection and the new object are not automatically included in the selection. This kind of selection is called a discontinuous selection. In the case of graphics, all selections are discontinuous selections.

This is not the case with arrays and text, however. In these two kinds of applications, an extended selection made by an Open-Apple-click always includes everything between the old selection and the new endpoint. To provide the possibility of a discontinuous selection in

1/15/84 Tognazzini

![](images/_page_89_Figure_5.jpeg)