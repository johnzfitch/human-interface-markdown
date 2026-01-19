---
chunk_index: 4143
ref: "f633d5fc9c46"
id: "f633d5fc9c4644f412b2756b3e901cea90f3e3b7c8229e17102c56eb347c5745"
slug: "full-document--the-windows-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2508, 2523]
token_estimate: 566
content_sha256: "947fcb1a5d61e617233c412eec1219156110cf7b0068b1b33696f77200929414"
compacted: false
heading_path: ["5 *Panels*","**The Windows Menu**"]
symbol: null
address: null
asset_path: null
---

## **The Windows Menu**

![](images/_page_141_Picture_1.jpeg)

The Windows menu contains commands affecting the windows that belong to the application. You can replace this menu with one more suitable for your application. For example, an application that has multiple windows per document might have its own tools to organize the windows.

| Command            | Action                                                                                                                                                                                                                                                                          |
|--------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Arrange in Front   | Stacks and offsets all the application's document windows<br>(those that can become the main window and are created using<br>Open and New commands) at the front of the screen. While this<br>command is recommended, it isn't mandatory.                                       |
| Miniaturize Window | Miniaturizes the key window (if it has a miniaturize button).<br>The affected window need not be a document window.                                                                                                                                                             |
| Close Window       | Closes the key window (if it has a close button). If the window<br>is the last one (or only one) open displaying a document, it also<br>closes the document, just as the Close command would.<br>(See "The Document Menu," earlier, for a description of the<br>Close command.) |

The commands in this menu bring windows to the front of the screen and, in the case of the last two commands, remove them. Other kinds of commands, even if they affect windows in some way, should be located elsewhere in the menu hierarchy.

You can replace Arrange in Front with an Arrange command that brings up a panel or menu giving the user more choices concerning which windows to arrange and how they should be tiled or stacked.