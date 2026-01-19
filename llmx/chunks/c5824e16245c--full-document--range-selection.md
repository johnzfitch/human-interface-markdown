---
chunk_index: 1416
ref: "c5824e16245c"
id: "c5824e16245c0aad9235644926bc2d549e339486669cca2837f3dacb67704354"
slug: "full-document--range-selection"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1722, 1729]
token_estimate: 242
content_sha256: "8b7824fbb773d96834a2776485362ac5750adce6a8dc38f15966768f86089be5"
compacted: false
heading_path: ["Selection in general","Range selection"]
symbol: null
address: null
asset_path: null
---

## Range selection

The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:

- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the anchor point of the range.
- 2. Without releasing the button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continuously highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. (If possible, the view should scroll to allow extending the selection beyond one windowful.)
- 3. When the feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the active end of the range.