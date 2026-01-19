---
chunk_index: 3992
ref: "d6cef36b967e"
id: "d6cef36b967e5291bf079a2e9f7272038173ece963b370ed6babc9a5de327821"
slug: "full-document--handling-arrow-characters"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [806, 811]
token_estimate: 150
content_sha256: "51b97501d809ceeed3627401e2e3a46372881dd13d90c2a71accad07d3350574"
compacted: false
heading_path: ["*Introduction*","**Handling Arrow Characters**"]
symbol: null
address: null
asset_path: null
---

## **Handling Arrow Characters**

Because the arrow keys generate the same character codes as the Symbol font's arrow characters, text objects should check which key generated the character. The arrow keys never produce visible arrow characters. However, when a nonarrow key (perhaps modified by the Alternate key) produces an arrow character code, it *should* produce visible arrow characters, and not result in arrow key functionality.

For example, Alternate-F should produce a visible left arrow symbol, as shown in the *User's Guide,* instead of moving the insertion point left one character.