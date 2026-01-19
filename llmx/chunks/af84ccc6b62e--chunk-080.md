---
chunk_index: 3671
ref: "af84ccc6b62e"
id: "af84ccc6b62e93d4dd8cba35d27e98baf3e06d5956f07d5dc5da249c1a075748"
slug: "chunk-080"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_080.md"
kind: "markdown"
lines: [1, 7]
token_estimate: 367
content_sha256: "a0d0ed04fbf0813ad7302808bf23d2210ca572544357c3525ff16fe9b12a5980"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 80 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 1065 -->
Out of all running applications, at most one is selected to be the active application (the principal application the user is working in). An application must be activated-made to be the active application-before the user can type in its windows or use its menus.  
The active application differs from other running applications in four ways:  
- It's the only application with visible menus. When an application is deactivated, its menus are hidden from view. When it's reactivated, they're restored to the screen.
- It's the application that owns most, if not all, of the panels that are visible on-screen. In general, panels behave like menus: They hide when the application isn't active and return to the screen when the application is reactivated. In exceptional cases, however, you may choose to leave a panel on-screen even when the application isn't active. (See Chapter 5 for guidelines on when it's appropriate to allow a panel to persist.)
- It's the application that receives the user's keyboard actions. Typing and keyboard alternatives can affect only the active application. When there's no active application, the user's keystrokes have no effect.
- It's the application that contains the key window and main window (if there is a current key window or main window), and its windows are likely to be in front of the windows of other applications.