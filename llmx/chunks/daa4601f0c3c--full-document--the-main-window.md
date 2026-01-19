---
chunk_index: 4042
ref: "daa4601f0c3c"
id: "daa4601f0c3cb3d80f8b08bfaa42d0dacb1917eacb78aec64d6a2c66c5bc73f7"
slug: "full-document--the-main-window"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1348, 1368]
token_estimate: 513
content_sha256: "25aaad4d288782b05c2877fb78f42c1c58cc04c0c3d1e9d1c5bd921f8bb3e324"
compacted: false
heading_path: ["The Window Interface to Applications","**The Key Window**","**The Main Window**"]
symbol: null
address: null
asset_path: null
---

#### **The Main Window**

The *main window* is the standard window where the user is currently working. It's the focus of user actions carried out in panels and menus. The Find panel, for example, requires the user to supply information by typing it. Since the panel is the destination of the user's keystrokes, it's marked as the key window. But the panel is just an instrument through which users can do work in another window-the main window.

Whenever a standard window becomes the key window, it also becomes the main window. When key-window status shifts from a standard window to a panel, main-window status remains with the standard window.

So that users can pick out the main window when it's not the key window, the Application Kit highlights its title bar in dark gray. If the main window is also the key window, it has only the black highlighting of the key window. The following figure illustrates the main window when it's marked as the key window and when it's not.

A menu command might affect either the key window or the main window, depending on the command. For example, the Paste command can be used to enter text in a Find panel. But the Save command saves the document displayed in the main window, and the Bold command turns the current selection in the main window bold. For this reason, user actions in a panel or menu are associated with both the key window and the main window:

- An action is first associated with the key window.
- If the key window is a panel and it can't handle the action, the action is next associated with the main window.

Note that this order of precedence is reflected in the way windows are highlighted: The key window is always marked, but the main window is marked only when it's not the key window.

The main window is always in the same application as the key window, the active application. It follows the key window as the user's actions shift the focus from window to window and from application to application.

![](images/_page_76_Picture_1.jpeg)

![](images/_page_76_Picture_2.jpeg)