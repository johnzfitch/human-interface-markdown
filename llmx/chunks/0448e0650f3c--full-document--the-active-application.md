---
chunk_index: 4038
ref: "0448e0650f3c"
id: "0448e0650f3cc4a9e50773b9378667217c5664d7247ab6bd8e6f4ddcddb74cf3"
slug: "full-document--the-active-application"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1289, 1299]
token_estimate: 348
content_sha256: "ecffd0f404bc627a05a78f301eb5fb525d16698328d7db93f78beecc865e93c6"
compacted: false
heading_path: ["The Window Interface to Applications","**The Active Application**"]
symbol: null
address: null
asset_path: null
---

## **The Active Application**

Out of all running applications, at most one is selected to be the active application (the principal application the user is working in). An application must be activated-made to be the active application-before the user can type in its windows or use its menus.

The active application differs from other running applications in four ways:

- It's the only application with visible menus. When an application is deactivated, its menus are hidden from view. When it's reactivated, they're restored to the screen.
- It's the application that owns most, if not all, of the panels that are visible on-screen. In general, panels behave like menus: They hide when the application isn't active and return to the screen when the application is reactivated. In exceptional cases, however, you may choose to leave a panel on-screen even when the application isn't active. (See Chapter 5 for guidelines on when it's appropriate to allow a panel to persist.)
- It's the application that receives the user's keyboard actions. Typing and keyboard alternatives can affect only the active application. When there's no active application, the user's keystrokes have no effect.
- It's the application that contains the key window and main window (if there is a current key window or main window), and its windows are likely to be in front of the windows of other applications.