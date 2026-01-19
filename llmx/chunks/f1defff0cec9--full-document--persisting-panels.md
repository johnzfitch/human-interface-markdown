---
chunk_index: 4076
ref: "f1defff0cec9"
id: "f1defff0cec930dd69b24c01270d6f5119df7ac1fd67f3e601dfc9fe1db84f63"
slug: "full-document--persisting-panels"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1621, 1628]
token_estimate: 221
content_sha256: "1aedb2854a5b6c686f024cd187b1f99d948f28b66b83f8b485163620687b6043"
compacted: false
heading_path: ["5 *Panels*","**Exceptions to Ordinary Panel Behavior**","**Persisting Panels**"]
symbol: null
address: null
asset_path: null
---

#### **Persisting Panels**

By default, an ordinary panel is removed from the screen when its application is deactivated. The user sees only panels related to the active application. This prevents confusion-such as might arise when similar Find panels for two different applications are on-screen at once.

An application can override this default behavior and allow a panel to remain on-screen after the application has been deactivated, but only if the panel contains information that would be pertinent to the user's activities in another application. This should be a rare occurrence.

An example is the Workspace Manager Info panel, which contains system-level information such as the amount of memory in the computer. Because the user might want to copy this information down-for example, into a mail message-this panel persists even when the Workspace Manager is deactivated.