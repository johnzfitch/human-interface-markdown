---
chunk_index: 549
ref: "e6fa13a7d478"
id: "e6fa13a7d478130ad30337fd46608caacbd3a33501af913c71ca8d50214d6c20"
slug: "full-document--cursor-key-scrolling"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1505, 1512]
token_estimate: 315
content_sha256: "dde6bfdd1c8227e71496d7e4c05c35cd7795dcf8781a89714c27821549df181b"
compacted: false
heading_path: ["Cursor-Key Scrolling"]
symbol: null
address: null
asset_path: null
---

# Cursor-Key Scrolling

The Apple II interface also includes the ability to move and scroll using the cursor keys. Each press of a cursor key moves the insertion point one unit in the chosen direction, with the unit of distance being appropriate to the application. When the insertion point has been moved to a window edge, the insertion point locks, and the contents of the window begin to be shifted one unit in the opposite direction. At that point, that cursor key acts like the equivalent scroll arrow.

The user can increase the extent of the movement by holding down Open-Apple while pressing the cursor key. The insertion point will then move by the next larger contextual unit. For example, in a word-processor, Open-Apple-Left-Arrow moves one word at a time, Open-Apple-Up-Arrow moves one windowful at a time.

You may also provide a method to substitute for the large leaps the mouse user can make by dragging the scroll box. Text programs, for example, have historically used Open-Apple with the numbers 1 through 9 to move to an absolute position, with 1 being the first character in a file and 9 being the last. Array windows, such as spreadsheets, will probably want to allow the user to enter a column or row designation to move directly there.