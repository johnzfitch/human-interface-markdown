---
chunk_index: 3805
ref: "857fc519a1ca"
id: "857fc519a1ca3b94eb4f6622dabf6f9638b53caf32d2398d95d0c6f2b375c571"
slug: "chunk-165--programming-note-scrolling"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_165.md"
kind: "markdown"
lines: [6, 7]
token_estimate: 121
content_sha256: "85df75c0e42641d5a5c5aa9102b1a9e29ecdac17a3105ec6e1431bbf5b0f805b"
compacted: false
heading_path: ["**Programming Note: Scrolling**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Scrolling**  
Using Interface Builder, it's easy to put scrollers around an area. The Application Kit handles all scrolling behavior, including Alternate-clicking to scroll a large amount and Alternate-dragging to scroll a tiny amount. All you might want to do is adjust the amount that a click scrolls (even for graphics, it should be a distance comparable to a single line of text) and optimize drawing performance so that scrolling is as fast as possible.