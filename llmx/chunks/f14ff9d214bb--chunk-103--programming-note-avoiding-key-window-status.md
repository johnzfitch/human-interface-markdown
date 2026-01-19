---
chunk_index: 3706
ref: "f14ff9d214bb"
id: "f14ff9d214bb20e943f4e84d9809b4a70beadc8a673efc666de8daa5c9c59d3f"
slug: "chunk-103--programming-note-avoiding-key-window-status"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_103.md"
kind: "markdown"
lines: [7, 9]
token_estimate: 110
content_sha256: "78fb1ba41909a0f1814030e36aa264ada81360b1f278e48793f002a6919526ce"
compacted: false
heading_path: ["**Programming Note: Avoiding Key-Window Status**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Avoiding Key-Window Status**  
Panels that need to avoid becoming the key window until the user indicates a readiness to begin typing can use the **setBecomeKeyOnlylfNeeded:** method of the Panel class to do so.  
However, panels that should never become key-a tools palette, for example-must use a different way to avoid becoming the key window. Each panel must remove key-down andkey-up events from itsevent mask.