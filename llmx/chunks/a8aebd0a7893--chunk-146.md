---
chunk_index: 3767
ref: "a8aebd0a7893"
id: "a8aebd0a78936fd45f284689fd9bedf4a5fa05eaca7c63d46a85417c72be0aa0"
slug: "chunk-146"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_146.md"
kind: "markdown"
lines: [1, 4]
token_estimate: 195
content_sha256: "b71478d826017b25ca9c6590a2eddd76750d39ebf8ed446e78803de84ab3d918"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 146 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 168 -->
![](images/_page_132_Picture_1.jpeg)  
The Paste As menu is rarely needed because applications can take care of pasteboard data types without user intervention. However, sometimes it's useful for the user to be able to specify the format in which data is pasted. For example, the user of a page layout program might want to choose whether text is pasted as ASCII or Rich Text Format (RTF), or whether graphics are pasted as EPS or TIFF.  
This menu should include only the types appropriate for its application. As usual, the programmer should disable invalid menu commands. For example, when the pasteboard contains only text data, any graphics formats should be disabled.