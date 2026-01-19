---
chunk_index: 1444
ref: "0b798a2f772a"
id: "0b798a2f772acb8d502e058c774034952dfa2471ee540c242136b3ec10004dea"
slug: "full-document--menu-bar-height"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [2157, 2160]
token_estimate: 115
content_sha256: "3761872064ada4620b2d46a9b1e8baf9cc612e0afabeab17b2b7883e9962ffdd"
compacted: false
heading_path: ["Macintosh localization","Menu bar height"]
symbol: null
address: null
asset_path: null
---

## Menu bar height

In the Macintosh Plus ROM, the Menu Manager uses the system font and the system font size in setting up the height of the menu bar, and of the items in menus. Because the system font size can vary, the height of the menu bar can also vary. When determining window placement on the screen, do not assume that the menu bar height is 20. Applications should use the low memory variable MBarHeight (instead of 20) as the height of the menu bar.