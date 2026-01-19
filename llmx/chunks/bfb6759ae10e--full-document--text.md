---
chunk_index: 965
ref: "bfb6759ae10e"
id: "bfb6759ae10e792382b7de6efd9784a36a4221ea2e567ee380e341391538c0ce"
slug: "full-document--text"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [2060, 2063]
token_estimate: 159
content_sha256: "51e970655aaac707acd14cc60cbb7c3bb3044a6ac3375abf51a2e0a5f19ea2d8"
compacted: false
heading_path: ["Macintosh Guidelines Localization","**Text**"]
symbol: null
address: null
asset_path: null
---

#### **Text**

For legibility, some non-Roman characters need higher resolution than Roman characters. On the Japanese Macintosh Plus, for example, this requires the system font to be larger than normal: it must allow for 16-by-16 pixel characters. The Macintosh Plus' ROM sets the system font size and family according to new low-memory globals. For example, it is possible to specify text in dialogs and menu bars to be 14-point New York. Applications should not change the system font or font size: this should be left to the user or the system. Applications can use SysFontSize to get the default font size to use for their text.