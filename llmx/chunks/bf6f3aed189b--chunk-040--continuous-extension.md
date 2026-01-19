---
chunk_index: 3620
ref: "bf6f3aed189b"
id: "bf6f3aed189b00e06dcea39ecaed0c043859a703410a85dbaca5500ee5ed233c"
slug: "chunk-040--continuous-extension"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_040.md"
kind: "markdown"
lines: [6, 10]
token_estimate: 343
content_sha256: "f2d36fa0ce7789779007f813f4f00e348e678115a4ddd611db696102ec621038"
compacted: false
heading_path: ["**Extending the Selection**","**Continuous Extension**"]
symbol: null
address: null
asset_path: null
---

#### **Continuous Extension**  
Clicking and dragging with the Alternate key down results in a new selection that's a continuation of the previous one. The new selection includes the previous selection and everything lying between it and the location of the cursor when the user releases the mouse button. The Alternate key is thus an alternative to dragging as a way of selecting a rangethe user can click to establish an anchor point, hold down the Alternate key, and click again to determine the end point.  
If the previous selection is already a range, Alternate-clicking and Alternate-dragging move the edge of selection that's closest to the cursor when the mouse button goes down to the cursor's location when the mouse button goes up. The Alternate key thus also provides a way of adjusting the boundaries of the previous selection. Alternate-clicking outside a selected range extends the range to the point of the click. Alternate-clicking inside a selected range repositions the closest edge of the selection to the point of the click.  
![](images/_page_41_Picture_3.jpeg)  
If the current selection is the result of a multiple-click, the Alternate key extends it just as dragging would. Double-clicking a word, holding the Alternate key down, and clicking another word elsewhere in the text extends the selection to include both words and all those between.