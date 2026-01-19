---
chunk_index: 713
ref: "89e3cc74d776"
id: "89e3cc74d77657ba31fc9795fafab6ad51f1fdc3d9d27f85f4dcf687c8357f26"
slug: "chunk-044--range-selection"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_044.md"
kind: "markdown"
lines: [31, 35]
token_estimate: 244
content_sha256: "8348ff8096cf741a0593a6183ea62966bc183a923c469b8e5453e5875c41b34d"
compacted: false
heading_path: ["Selection in General","Selection by Clicking","Range Selection"]
symbol: null
address: null
asset_path: null
---

#### Range Selection  
The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:  
- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continually highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. (If possible, the view should scroll to allow extending the selection beyond one windowful.)
- 3. When the feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the active end of the range.