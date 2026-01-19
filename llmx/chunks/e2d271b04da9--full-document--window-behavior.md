---
chunk_index: 4029
ref: "e2d271b04da9"
id: "e2d271b04da9ca874d63b67d942d6047e1127e461f900ba7da507f9090dce581"
slug: "full-document--window-behavior"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1191, 1215]
token_estimate: 428
content_sha256: "2b3466e7efade93e92c2fa9b0b1896f93d56b58ef02c3259d61ad2bc001e0d5c"
compacted: false
heading_path: ["The Window Interface to Applications","**Window Behavior**"]
symbol: null
address: null
asset_path: null
---

## **Window Behavior**

Windows respond to user actions in the following ways:

- Any window can be brought to the front of the screen, relative to other windows in its tier.
- Any window with a title bar can be moved to a new location on the screen, as can any miniwindow or application icon.
- Any window with a resize bar can be resized.
- A window with the appropriate buttons in its title bar can be closed or miniaturized.

A window's title bar can display two buttons:

Miniaturize button Clicking this replaces the window with its mini window

> counterpart. The miniwindow represents the window on-screen and gives the user access to it. Double-clicking the miniwindow causes it to disappear and the window that was

miniaturized to reappear.

Close button Clicking this removes the window from the screen.

When the user clicks a button in the title bar, the action of the button is performed. The click doesn't count as "clicking in a window" for the purpose of bringing the window to the front, making it the key window, or activating an application (the key window and active application are discussed in "Application and Window Status" in this chapter).

Title bar buttons are illustrated below. The window in front has both buttons as they normally appear. The miniaturize button is on the left and the close button is on the right. The window in back shows a *broken* close button. The close button should be broken when the user would lose work by closing the window-for example, when the window displays a document that the user has edited but not saved. More information on the miniaturize and close buttons is in "Implementing Windows" in this chapter.

![](images/_page_67_Picture_7.jpeg)