---
chunk_index: 4050
ref: "3e5d6c82c1bf"
id: "3e5d6c82c1bf4171b8b65c554a998181890603d52fbbfcd185ba5e2cfdb0b4d8"
slug: "full-document--programming-note-saving-window-positions"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1430, 1435]
token_estimate: 255
content_sha256: "6115c96c669cba30aa46833c3228d8c474a4285ac229b9c24be5bdfba24f7a59"
compacted: false
heading_path: ["The Window Interface to Applications","**Placing Windows**","**Programming Note: Saving Window Positions**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Saving Window Positions**

Three methods exist to help panels and non-document standard windows remember their window position. Calling the **setFrameAutosaveName:** method once per window makes the window save its position in the defaults system whenever necessary. The next time the window comes up, it automatically appears at the last-saved position. A less automated way of remembering the window position is to call **saveFrameUsingName:**  every time you wish to save the position, and call **setFrameUsingName:** to set the window's position when it's being brought up.

The methods discussed above aren't appropriate for document windows, since there's no easy way to guarantee unique names for documents. If your application saves the positions of its document windows, you should use the **saveFrameToString:** method to save a representation of the window's position into the document itself. When opening the document, you should position its window using **setFrameFromString:.**