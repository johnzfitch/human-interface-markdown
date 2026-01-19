---
chunk_index: 3709
ref: "8eb2ffba215c"
id: "8eb2ffba215ca29786a9618e3ca803eb26565b30e5e429c9a944b09d06e131b3"
slug: "chunk-105--persisting-panels"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_105.md"
kind: "markdown"
lines: [3, 6]
token_estimate: 222
content_sha256: "eb998755a3aa7a7907d5f0a44c62fdcb234b7687e16160b0eb17f6e5118d1516"
compacted: false
heading_path: ["**Persisting Panels**"]
symbol: null
address: null
asset_path: null
---

#### **Persisting Panels**  
By default, an ordinary panel is removed from the screen when its application is deactivated. The user sees only panels related to the active application. This prevents confusion-such as might arise when similar Find panels for two different applications are on-screen at once.  
An application can override this default behavior and allow a panel to remain on-screen after the application has been deactivated, but only if the panel contains information that would be pertinent to the user's activities in another application. This should be a rare occurrence.  
An example is the Workspace Manager Info panel, which contains system-level information such as the amount of memory in the computer. Because the user might want to copy this information down-for example, into a mail message-this panel persists even when the Workspace Manager is deactivated.