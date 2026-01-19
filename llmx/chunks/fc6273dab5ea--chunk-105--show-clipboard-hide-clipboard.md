---
chunk_index: 2299
ref: "fc6273dab5ea"
id: "fc6273dab5eae82977c460de8207764b042a8b47835b66b3ceb61797be486f51"
slug: "chunk-105--show-clipboard-hide-clipboard"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_105.md"
kind: "markdown"
lines: [57, 59]
token_estimate: 194
content_sha256: "7e55bb4044ee5b3e2fc8da8753f85ae1e1f9ff8a4b90d5ff488571ecb82569fa"
compacted: false
heading_path: ["The Clipboard","Undo/Redo","Cut","Show Clipboard/Hide Clipboard"]
symbol: null
address: null
asset_path: null
---

#### Show Clipboard/Hide Clipboard  
Implement the Show Clipboard command in the Edit menu so that the user can display and close the Clipboard window, as described earlier in this chapter in the section "The Clipboard." (If the Clipboard is already showing, the user can also use the close box or the Close command to close the window.) Show Clipboard and Hide Clipboard are a single toggled item.  
Show Clipboard changes to Hide Clipboard when the Clipboard window is displayed. The user can also use the close box in the Clipboard window (or the Close command) to hide the Clipboard. Remember to hide your Clipboard window when your application isn't active. Display it again when the user makes your application active by clicking a window or using the Application menu.