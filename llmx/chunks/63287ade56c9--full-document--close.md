---
chunk_index: 1358
ref: "63287ade56c9"
id: "63287ade56c9f3475e3ca873bdbe3ea2e54f9d6d389792d0fc9a79c4883b02b1"
slug: "full-document--close"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1202, 1215]
token_estimate: 337
content_sha256: "a32341c1e4a4ff76c728e6059aec323e73805b068f1bc3fa95e6b0274f8e596f"
compacted: false
heading_path: ["About MacPaint...","Figure 33 34 HFS open dialog box","Close"]
symbol: null
address: null
asset_path: null
---

#### Close

Closes the active window, which may be a document window, a desk accessory, or any other type of window. Clicking in a window's close box is the same as choosing Close.

When the user chooses Close or Quit, and the active document has been changed since the last save, the Close dialog box appears, asking Save changes before closing? A great deal of work can be lost if a user mistakenly clicks No instead of Yes. To avoid confusion, all applications should use the same standard Close dialog box. This is especially important to users who often move from one application to another and become less aware of subtle differences between applications.

![](images/_page_84_Picture_6.jpeg)

Figure 34 35 Standard Close dialog box

Yes and No, the two direct responses to the question, are placed together on the left side of the box. Yes is the default button. Cancel, which cancels Close, is to the right, separate from Yes and No.

The text of the question is generally Save changes before closing? but if the user sees this message after choosing Quit, the text would instead be Save changes before quitting? If the application supports multiple windows, the text is Save changes to [document name] before closing? Regardless of the text of the question, the box should always look the same and appear in the same place on the screen.