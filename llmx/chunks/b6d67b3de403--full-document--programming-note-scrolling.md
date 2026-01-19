---
chunk_index: 4172
ref: "b6d67b3de403"
id: "b6d67b3de40375e65bb92148207f99e7edd70e36c821726ac4ff7651386c3c21"
slug: "full-document--programming-note-scrolling"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2871, 2874]
token_estimate: 121
content_sha256: "07242ebe00ec54326eb02048e895ce2305798e28d7551b84bf5011e10ecf72bc"
compacted: false
heading_path: ["7! *Controls*","**The Scroll Buttons**","**Programming Note: Scrolling**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Scrolling**

Using Interface Builder, it's easy to put scrollers around an area. The Application Kit handles all scrolling behavior, including Alternate-clicking to scroll a large amount and Alternate-dragging to scroll a tiny amount. All you might want to do is adjust the amount that a click scrolls (even for graphics, it should be a distance comparable to a single line of text) and optimize drawing performance so that scrolling is as fast as possible.