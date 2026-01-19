---
chunk_index: 744
ref: "81c0badf346e"
id: "81c0badf346e688419225817a86f7fa9cbe5bf9b62b85d2fd8f4f83bf4c22fe7"
slug: "chunk-061--close"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_061.md"
kind: "markdown"
lines: [8, 15]
token_estimate: 345
content_sha256: "f0d5a39b5fef2dbe2b438132a13647c5d9d24b1c8cf97a2d19e631de02afe1cb"
compacted: false
heading_path: ["Close"]
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