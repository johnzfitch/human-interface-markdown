---
chunk_index: 533
ref: "c2205cede6a4"
id: "c2205cede6a4e17bee215e4d8c31a60bfcf31d1342d44d6188db38083ff711e6"
slug: "full-document--extending-a-selection"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1271, 1280]
token_estimate: 323
content_sha256: "3d6d215ac7c9099bdf65bdeebf9cb07fc2eba870d0c852ced692b813f22647cc"
compacted: false
heading_path: ["Range Selection","Extending a Selection"]
symbol: null
address: null
asset_path: null
---

### Extending a Selection

A user can change the extent of an existing selection by holding down the Open-Apple key and clicking the mouse button. (This is an unfortunate but unavoidable difference with MacIntosh, where Shift-click is used instead. Should Apple II hardware ever permit reading the shift key by itself, windowing software should accept either a Shift-click or an Open-Apple-click.) Exactly what happens next depends on the context.

In text or an array, the result of an Open-Apple-click is always a range. The position where the button is clicked becomes the new endpoint or anchor point of the range; the selection can be extended in any direction. If the user clicks within the current range, the new range will be smaller than the old range.

In graphics, a selection is extended by adding objects to it; the added objects do not have to be adjacent to the objects already selected. The user can add either an individual object or a range of objects to the selection by holding down the Open-Apple key before making the additional selection. If the user holds down the Open-Apple key and selects one or more objects that are already highlighted, the objects are deselected.

Extended selections can be made across the panes of a split window. (See "Splitting Windows".)