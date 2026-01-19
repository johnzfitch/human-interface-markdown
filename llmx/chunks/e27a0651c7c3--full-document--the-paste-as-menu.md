---
chunk_index: 4134
ref: "e27a0651c7c3"
id: "e27a0651c7c34b0a457d080c4afee4fde3debd8d2eef88a8009577bf0efeb032"
slug: "full-document--the-paste-as-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2338, 2345]
token_estimate: 175
content_sha256: "b1bf0791a1c3cadc4700de4334334cbbd3bbd2c2412215bfb855472e8325ba2e"
compacted: false
heading_path: ["5 *Panels*","**The Paste As Menu**"]
symbol: null
address: null
asset_path: null
---

## **The Paste As Menu**

![](images/_page_132_Picture_1.jpeg)

The Paste As menu is rarely needed because applications can take care of pasteboard data types without user intervention. However, sometimes it's useful for the user to be able to specify the format in which data is pasted. For example, the user of a page layout program might want to choose whether text is pasted as ASCII or Rich Text Format (RTF), or whether graphics are pasted as EPS or TIFF.

This menu should include only the types appropriate for its application. As usual, the programmer should disable invalid menu commands. For example, when the pasteboard contains only text data, any graphics formats should be disabled.