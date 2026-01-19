---
chunk_index: 3637
ref: "6c628d9baae3"
id: "6c628d9baae3ad72f66476f5db8481cce14f1123cc9bc9c06a1487fa0e80125e"
slug: "chunk-051"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_051.md"
kind: "markdown"
lines: [1, 5]
token_estimate: 307
content_sha256: "54dd1e8264b01bbdf637cb559a6b1650795f77536bd86611f32d19aa3034c401"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 51 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 281 -->
Clicking can be used not only to operate an object, but also simply to bring a window forward. When the user clicks in a window that isn't already in front, a question arises concerning intent: Did the user intend the click just to bring the window forward, or was it also intended to do some work within the window? This question is addressed by the following guidelines:  
- If the user chooses a particular control-for example, by clicking a button or clicking in a scroller-the click should not only bring the window forward, but should also operate the control. Since controls are small, it's reasonable to assume that the user chose to click the control, not just the window.
- If the click is just generally within the content area of the window, the click will bring the window forward but shouldn't have any result within the window. Specifically, it shouldn't alter the current selection.  
However, if the user chooses to double-click within the content area of the window, the normal double-click action should be performed. Double-clicking on a word should select the word whether the window is in front or not.