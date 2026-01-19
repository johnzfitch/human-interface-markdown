---
chunk_index: 1973
ref: "7db9f1697402"
id: "7db9f16974024771fd6a2b2c9cc456c76fe2fae34d4262164c9c923eb3fab8ff"
slug: "full-document--close"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1667, 1680]
token_estimate: 348
content_sha256: "0ef8e7be1bc918a7875e044db4fa993ac1e7eb4f676560e29bdc6625f2baf5ff"
compacted: false
heading_path: ["The Apple menu","The File menu","New","Close"]
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