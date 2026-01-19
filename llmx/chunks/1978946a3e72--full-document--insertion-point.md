---
chunk_index: 537
ref: "1978946a3e72"
id: "1978946a3e727449326e9b2c1b7147ee83fbbf6accff891e076684e58de95b82"
slug: "full-document--insertion-point"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1313, 1320]
token_estimate: 234
content_sha256: "d10d319e4229ae3b2de3c28e383c05d93b4879cd51f2bad249be14b7544b52f3"
compacted: false
heading_path: ["Insertion Point"]
symbol: null
address: null
asset_path: null
---

# Insertion Point

The insertion point is a zero-length text selection. The user establishes the location of the insertion point by clicking between two characters. The insertion point then appears at the nearest character boundary. If the user clicks to the right of the last character on a line, the insertion point appears immediately after the last character. The converse is true if the user clicks to the left of the first character in the line.

The insertion point shows where text will be inserted when the user begins typing, or where the contents of the Clipboard will be pasted. After each character is typed, the insertion point is relocated to the right of the insertion.

If, between the mouse-down and the mouse-up, the user moves the pointer more than about half the width of a character, the selection is a range selection rather than an insertion point. The cursor-key user begins the same process with Open-Apple-M.