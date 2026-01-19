---
chunk_index: 4044
ref: "cd822d6898df"
id: "cd822d6898dfa25a9b0588edaf03ac8f96dec69df5a6729ae2580f6eed21f8e1"
slug: "full-document--in-the-active-application"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1373, 1378]
token_estimate: 199
content_sha256: "c2abe46c33d51fb6e9b212b62595db600fe03767f6589f9d5790f621185313ff"
compacted: false
heading_path: ["The Window Interface to Applications","**How Windows Become the Key Window and Main Window**","**In the Active Application**"]
symbol: null
address: null
asset_path: null
---

#### **In the Active Application**

. In the active application, the user can select a new key window by clicking in it. If the window is a standard window, it's also made the main window. If it's a panel that accepts keystrokes, it's highlighted as the new key window, but the former main window retains its status and is highlighted in dark gray. The user can't select a main window without also making it the key window.

The Application Kit chooses a new key window (or main window) for the active application whenever the user closes or miniaturizes the window currently having that status. Even if the application has no more windows on-screen, and thus no new key window can be chosen, the application still remains active: It's up to the user to decide whether to continue working in it.