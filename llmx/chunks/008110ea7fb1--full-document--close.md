---
chunk_index: 916
ref: "008110ea7fb1"
id: "008110ea7fb1ab0c8cf4bea505e645a0935d30e268fa0c52587b92154a4c79fa"
slug: "full-document--close"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1474, 1489]
token_estimate: 343
content_sha256: "fa9bba5ce1e6c9080a74e0ecbe0695377c64131862e57a3837825c83845776fc"
compacted: false
heading_path: ["Standard Menus","The Apple **Menu**","*Open*","Close"]
symbol: null
address: null
asset_path: null
---

#### Close

This is used to close the active window, which may be a document window, a desk accessory, or any other type of window. Clicking in a window's close box is the same as choosing Close.

When the user chooses Close or Quit, and the active document has been changed since the last save, the Close dialog box appears, asking Save changes before closing? A great deal of work can be lost if a user mistakenly clicks No instead of Yes. To avoid confusion, all applications should use the same standard close dialog box. This is especially important to Switcher users, who often move from one application to another and become less aware of

subtle differences between applications.

![](images/_page_66_Picture_2.jpeg)

Figure 26. Standard Close Dialog Box

Yes and No, the two direct responses to the question, are placed together on the left side of the box. Yes is the default button. Cancel, which cancels Close, is to the right, separate from Yes and No.

The text of the question is generally Save changes before closing? but if the user sees this message after choosing Quit, the text would instead be Save changes before quitting? If the application supports multiple windows, the text is Save changes to [document name] before closing? Regardless of the text of the question, the box should always look the same and appear in the same place on the screen.