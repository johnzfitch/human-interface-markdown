---
chunk_index: 3677
ref: "09504e51753b"
id: "09504e51753b1075426361eba2440376356f92397936f347fd3d3690a1c6e2af"
slug: "chunk-082--in-the-active-application"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_082.md"
kind: "markdown"
lines: [3, 5]
token_estimate: 200
content_sha256: "a6bafe60ac2dc2edca0d19c8966158996f88b17166505bd605c3047a1f14023f"
compacted: false
heading_path: ["**In the Active Application**"]
symbol: null
address: null
asset_path: null
---

#### **In the Active Application**  
. In the active application, the user can select a new key window by clicking in it. If the window is a standard window, it's also made the main window. If it's a panel that accepts keystrokes, it's highlighted as the new key window, but the former main window retains its status and is highlighted in dark gray. The user can't select a main window without also making it the key window.  
The Application Kit chooses a new key window (or main window) for the active application whenever the user closes or miniaturizes the window currently having that status. Even if the application has no more windows on-screen, and thus no new key window can be chosen, the application still remains active: It's up to the user to decide whether to continue working in it.