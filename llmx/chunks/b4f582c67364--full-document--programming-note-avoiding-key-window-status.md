---
chunk_index: 4073
ref: "b4f582c67364"
id: "b4f582c673646f0ea21b89fd06b5bdbf4e3e7d50eaf2a69c839ff6e3c694c62b"
slug: "full-document--programming-note-avoiding-key-window-status"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1605, 1610]
token_estimate: 110
content_sha256: "84f3e7c5492167e743e50cd6c830ce6665edfdac94949cf07b5ea8a462f64718"
compacted: false
heading_path: ["5 *Panels*","**Becoming the Key Window**","**Programming Note: Avoiding Key-Window Status**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Avoiding Key-Window Status**

Panels that need to avoid becoming the key window until the user indicates a readiness to begin typing can use the **setBecomeKeyOnlylfNeeded:** method of the Panel class to do so.

However, panels that should never become key-a tools palette, for example-must use a different way to avoid becoming the key window. Each panel must remove key-down andkey-up events from itsevent mask.