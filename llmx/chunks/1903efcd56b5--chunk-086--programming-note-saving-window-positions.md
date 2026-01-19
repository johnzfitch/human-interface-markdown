---
chunk_index: 3683
ref: "1903efcd56b5"
id: "1903efcd56b588e47d1ac0f5a7c14a92a9c36ae769fab74782ff4e80c9906e4c"
slug: "chunk-086--programming-note-saving-window-positions"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_086.md"
kind: "markdown"
lines: [10, 12]
token_estimate: 255
content_sha256: "f076b4f37d7ebb07047e64cfb730bd15c0e18898a8f57252657d20d816840d3d"
compacted: false
heading_path: ["**Programming Note: Saving Window Positions**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Saving Window Positions**  
Three methods exist to help panels and non-document standard windows remember their window position. Calling the **setFrameAutosaveName:** method once per window makes the window save its position in the defaults system whenever necessary. The next time the window comes up, it automatically appears at the last-saved position. A less automated way of remembering the window position is to call **saveFrameUsingName:**  every time you wish to save the position, and call **setFrameUsingName:** to set the window's position when it's being brought up.  
The methods discussed above aren't appropriate for document windows, since there's no easy way to guarantee unique names for documents. If your application saves the positions of its document windows, you should use the **saveFrameToString:** method to save a representation of the window's position into the document itself. When opening the document, you should position its window using **setFrameFromString:.**