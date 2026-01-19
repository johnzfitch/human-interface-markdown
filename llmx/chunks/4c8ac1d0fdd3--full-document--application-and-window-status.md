---
chunk_index: 4037
ref: "4c8ac1d0fdd3"
id: "4c8ac1d0fdd3867a61f82944b1b4bad91e1d1d486b246d1f81a50d58a3e9cece"
slug: "full-document--application-and-window-status"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1278, 1288]
token_estimate: 330
content_sha256: "215985b49dec0bfeb2348a34242b70506378e29b161a957ba698d3cfa228020c"
compacted: false
heading_path: ["The Window Interface to Applications","**Application and Window Status**"]
symbol: null
address: null
asset_path: null
---

## **Application and Window Status**

Since more than one application can run at a time, the screen is likely to display windows for a variety of different applications. The Workspace Manager is one application that will often have a window on-screen. Some users will also run Mail and a spreadsheet, or perhaps a word processor and Digital Webster'" (a dictionary and thesaurus application), at the same time as other applications.

The user must be able to pick a particular application, and a particular window in that application, to work in. The application that the user is currently working in is known as the *active application;* the windows that are the current focus of user attention in the active application are the *key window* and the *main window.* The key window and main window are usually one and the same. The two terms identify different functional roles that can be assumed by the same window:

- The key window is the window that receives characters from the keyboard.
- The main window is the window containing the selected target for controls.

These three concepts-the active application, key window, and main window-refer not to inherent properties of applications and windows, but to their status at a particular point in time. They're discussed more fully in the three sections that follow.