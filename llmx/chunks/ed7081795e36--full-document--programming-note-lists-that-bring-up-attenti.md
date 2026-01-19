---
chunk_index: 4161
ref: "ed7081795e36"
id: "ed7081795e36460b9aa0dcee23d8859ed9e4fc8d27ff3630d52f4f57bd3a7d11"
slug: "full-document--programming-note-lists-that-bring-up-attenti"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2716, 2719]
token_estimate: 149
content_sha256: "f1f6e3b5bbdf0508cd059b890e9e0d053ce88191527fee1926ee8820c3d895e8"
compacted: false
heading_path: ["7! *Controls*","**Changing the Button's Appearance during a Click**","Implementing Pop-Up and Pull-Down Lists","Programming Note: Lists that Bring Up Attention Panels"]
symbol: null
address: null
asset_path: null
---

#### Programming Note: Lists that Bring Up Attention Panels

When an item in a pop-up or pull-down list opens an attention panel, the list by default stays up until the panel is dismissed. Because lists are in a higher window tier than attention panels, they can obscure attention panels. To avoid this, you should dismiss the list before bringing up the attention panel. One way of doing this is to have the list item call the perform:with:afterDelay:canceIPrevious: method to schedule the execution of a method 1 millisecond in the future. This method should then bring up the attention panel.