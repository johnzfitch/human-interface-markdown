---
chunk_index: 80
ref: "5412bd380fc3"
id: "5412bd380fc3f0e36404eba5c09c371833e84ff60ec8f36782567e9f2747c8f0"
slug: "full-document--40-the-backspace-buffer"
path: "marker/1980 Lisa UI Standards/full_document.md"
kind: "markdown"
lines: [461, 466]
token_estimate: 95
content_sha256: "325982d567f13f0621edf370579169a977450c45612d233204069e2b8bb24097"
compacted: false
heading_path: ["39. BACKSPACE","40. THE BACKSPACE BUFFER"]
symbol: null
address: null
asset_path: null
---

## 40. THE BACKSPACE BUFFER

This is a LIFO stack in which characters backspaced over are stored, and from which they may be retrieved a character at a time by pressing SHIFT-BACKSPACE (un-backspace) or a word at a time by pressing APPLE-SHIFT-BACKSPACE (un-backword).

This buffer is cleared when the mouse button is pressed or a key other than BACKSPACE or its shifts is typed.