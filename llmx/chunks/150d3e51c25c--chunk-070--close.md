---
chunk_index: 1727
ref: "150d3e51c25c"
id: "150d3e51c25cc0be1c5fedfaa5efb74ba4959c9b5640c9c4172c79f88d5860fe"
slug: "chunk-070--close"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_070.md"
kind: "markdown"
lines: [24, 30]
token_estimate: 350
content_sha256: "6397f146723f3d1dca8f6ff87ef02684c3272fc3880e0e46b0248a0d8a285e7d"
compacted: false
heading_path: ["The File menu","New","Open","Close"]
symbol: null
address: null
asset_path: null
---

#### Close  
Closes the active window, which may be <sup>a</sup> document window, <sup>a</sup> desk accessory, or any other type of window. Clicking in a window's close box isthe same as choosing Close.  
When the user chooses Close, and the active document has been changed since the last save, the Close dialog box appears, asking "Save changes before closing?" A great deal of work can be lost if <sup>a</sup> user mistakenly clicks No instead of Yes. To avoid confusion, all applications should use the same standard Close dialog box (Figure 3-31). This is especially important to users who often move from one application to another and become less aware of subtle differences between applications.  
![](images/_page_90_Picture_5.jpeg)  
Figure 3-31 Standard Close dialog box  
Yes and No, the two direct responses to the question, are placed together on the left side of the box. Yes is the default button. Cancel, which cancels Close, is to the right, separate from Yes and No.  
The text of the question is generally "Save changes before closing?" but if the user sees this message after choosing Quit, the text would instead be "Save changes before quitting?" If the application supports multiple windows, the text is "Save changes to [document name] before closing?" Regardless of the text of the question, the box should always look the same and appear in the same place on the screen.