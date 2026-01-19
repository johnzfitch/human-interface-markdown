---
chunk_index: 4018
ref: "4d5dae46b20b"
id: "4d5dae46b20bd5fae046bbe91d15fec85f526a6ee57fb4a913bed82511a3674b"
slug: "full-document--when-discontinuous-selection-isn-t-implement"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1098, 1103]
token_estimate: 147
content_sha256: "728b86d2282b50a0442f4c718d0800b4f101ead57cdeb20f9d11b79e71354aa1"
compacted: false
heading_path: ["*Introduction*","**When Discontinuous Selection Isn't Implemented**"]
symbol: null
address: null
asset_path: null
---

## **When Discontinuous Selection Isn't Implemented**

Sometimes an application implements selection for an area but doesn't implement discontinuous selection. In this case, the application should make the Shift key act like the Alternate key during selection, so that both keys cause continuous selection.

For example, discontinuous selection is not implemented in the Application Kit Text object, so both Shift-clicking and Alternate-clicking extend the selection continuously. This saves the user from making errors due to pressing the wrong key when trying to extend the selection.