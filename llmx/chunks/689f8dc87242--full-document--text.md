---
chunk_index: 1439
ref: "689f8dc87242"
id: "689f8dc87242a77389fe06123519504f4caf36a0d836dcb08126d621e3b9721c"
slug: "full-document--text"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [2139, 2142]
token_estimate: 159
content_sha256: "e54f9376b8b01a0232707f1d51bc804d6721a8c89cbf25bce8de7bf370cbba23"
compacted: false
heading_path: ["Macintosh localization","Text"]
symbol: null
address: null
asset_path: null
---

#### Text

For legibility, some non-Roman characters need higher resolution than Roman characters. On the Japanese Macintosh Plus, for example, the system font must be larger than normal: it must allow for 16-by-16 pixel characters. The Macintosh Plus ROM sets the system font size and family according to low-memory variables. For example, it is possible to specify text in dialogs and menu bars to 14-point New York. Applications should not change the system font or font size: let the user (or the system, where that is possible) make such changes. Applications can use SysFontSize to get the default font size to use for their text.