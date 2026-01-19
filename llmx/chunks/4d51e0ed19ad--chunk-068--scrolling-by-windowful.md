---
chunk_index: 777
ref: "4d51e0ed19ad"
id: "4d51e0ed19ad56bfffb0c67dbb6639e463c7ddb4f946099dd7035b2dc5661921"
slug: "chunk-068--scrolling-by-windowful"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_068.md"
kind: "markdown"
lines: [4, 6]
token_estimate: 314
content_sha256: "c5e5fae4b6fecc0f6a6474392499d1cb9c67176bfb64d6234a051e363966c09f"
compacted: false
heading_path: ["Scrolling by Windowful"]
symbol: null
address: null
asset_path: null
---

#### Scrolling by Windowful  
Clicking the mouse anywhere in the gray area of the scroll bar advances the document by a windowful. The scroll box, and the document view, move toward the place where the user clicked. Clicking *below* the scroll box, for example, brings the user the next windowful toward the bottom of the document. Pressing in the gray area causes the display of consecutive windowfuls until the user releases the mouse button, or until the location of the scroll box catches up to the location of the pointer. Each windowful is the height or width of the window, minus one unit overlap (where a unit is the distance the view scrolls when the scroll arrow is clicked once).  
In both the above schemes, the user moves the document in increments until it's in the desired position under the window. The user can also move the document directly to any position by dragging the scroll box to the corresponding position in the scroll bar. To move the scroll box, the user drags it along the scroll bar; an outline of the scroll box follows the pointer. When the mouse button is released, the scroll box jumps to the position last held by the outline, and the document jumps to the position corresponding to the new position of the scroll box.