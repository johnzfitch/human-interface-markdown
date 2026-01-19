---
chunk_index: 3693
ref: "9cd99c42fcfb"
id: "9cd99c42fcfb28a57ae2dd23f5d3c4bc9a341d346120d581a36e75b233135169"
slug: "chunk-094--programming-note-activating-and-deactivating"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_094.md"
kind: "markdown"
lines: [5, 9]
token_estimate: 103
content_sha256: "0399ecdb4019df94bc2b472e83a0e75713775a64dff8c3f896e35c1ac8693ec1"
compacted: false
heading_path: ["**Programming Note: Activating and Deactivating an Application**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Activating and Deactivating an Application**  
As described in the section "Activating an Application," most applications don't need to explicitly activate or deactivate themselves. However, when necessary, an application can conditionally activate itself with the following code:  
[NXApp activateSelf:NO];  
An application can deactivate itself as follows:  
[NXApp deactivateSelf];