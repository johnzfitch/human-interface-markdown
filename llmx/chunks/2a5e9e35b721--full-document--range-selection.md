---
chunk_index: 2034
ref: "2a5e9e35b721"
id: "2a5e9e35b721e9ccd6a66202090a0b33568fe932701045f0fcc9442712c54c2b"
slug: "full-document--range-selection"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2289, 2296]
token_estimate: 242
content_sha256: "eca304ba08992400533355d2397a2bcadade6b34f6038739e72e4ca9f6b967ba"
compacted: false
heading_path: ["Selection in general","Selection by clicking","Range selection"]
symbol: null
address: null
asset_path: null
---

#### Range selection

The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:

- 1 The user positions the pointer at one corner of the range and presses the mouse button. This position is called the anchor point of the range.
- 2 Without releasing the button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continuously highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. (If possible, the view should scroll to allow extending the selection beyond one windowful.)
- 3 When the feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the active end of the range.