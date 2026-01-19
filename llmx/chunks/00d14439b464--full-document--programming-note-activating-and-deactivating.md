---
chunk_index: 4060
ref: "00d14439b464"
id: "00d14439b464538a348bdef9c75c538514e41f26d405ac4293e7f21e33cfb8d6"
slug: "full-document--programming-note-activating-and-deactivating"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1504, 1513]
token_estimate: 102
content_sha256: "66b15fef77e4abe62a0200218c99eb820816dc6bf38e60b112c1a8bae71b6d49"
compacted: false
heading_path: ["The Window Interface to Applications","**Activating an Application**","**Programming Note: Activating and Deactivating an Application**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Activating and Deactivating an Application**

As described in the section "Activating an Application," most applications don't need to explicitly activate or deactivate themselves. However, when necessary, an application can conditionally activate itself with the following code:

[NXApp activateSelf:NO];

An application can deactivate itself as follows:

[NXApp deactivateSelf];