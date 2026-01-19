---
chunk_index: 4074
ref: "4a4745f5266e"
id: "4a4745f5266e9be3dcb7a09eef5bb3bfaf47c94647cb1e2d2992d2754b653759"
slug: "full-document--relinquishing-key-window-status"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1611, 1616]
token_estimate: 195
content_sha256: "43d8bc26d9e1e91886c3056ca8622e49d4f341179c1d77ef28a4c0e857885dbe"
compacted: false
heading_path: ["5 *Panels*","**Relinquishing Key-Window Status**"]
symbol: null
address: null
asset_path: null
---

## **Relinquishing Key-Window Status**

A panel should remain the key window only as long as necessary. If user actions within the panel affect the main window, key-window status should be returned to the main window as soon as those actions are completed.

For example, when the user clicks the Set button (or types Return) in a Font panel to change the font of the current selection in the main window, the panel gives up key-window status (if it had it). In all likelihood, the user is finished with the Font panel (at least until the selection has changed) and is ready to resume working in the main window. Under these circumstances, the user should be free to begin working in the main window immediately, without being forced to click in it just to make it the key window.