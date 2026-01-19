---
chunk_index: 4058
ref: "bbdb93ec049c"
id: "bbdb93ec049cf2afbaf7577b7a9abdaf9481502230891507215d4e3388fd20f2"
slug: "full-document--choosing-the-key-window"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1490, 1495]
token_estimate: 177
content_sha256: "e9069d4907a13b2cec80656b597fe530066ed03edee421673023c4ded001547f"
compacted: false
heading_path: ["The Window Interface to Applications","**Choosing the Key Window**"]
symbol: null
address: null
asset_path: null
---

## **Choosing the Key Window**

In general, all the standard windows in your application should be permitted to become the key window, even if they don't respond to keyboard actions. Giving key-window status to a window focuses attention on it and prevents the user from typing in any other window. If the key window doesn't do anything with the user's typing, it should beep as it receives the keystrokes to indicate to the user that typing isn't appropriate.

When an application is activated on startup, it should designate one of its windows to be the initial key (and main) window. If the application opens a document file for the user, the window that displays the document should be the key window.