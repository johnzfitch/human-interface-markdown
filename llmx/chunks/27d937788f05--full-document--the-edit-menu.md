---
chunk_index: 923
ref: "27d937788f05"
id: "27d937788f05308564a35f45e42e6fa509f4d5db455496b4c64c7c34a7bed070"
slug: "full-document--the-edit-menu"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1536, 1561]
token_estimate: 357
content_sha256: "725c4cc86dfdcc88ad39ac7c7333b86a043022180bf6c60b14e425f79a3e8e16"
compacted: false
heading_path: ["Standard Menus","The Apple **Menu**","*Revert to Saved*","The Edit Menu"]
symbol: null
address: null
asset_path: null
---

#### The Edit Menu

There are two important principles behind the Edit menu:

- Anything the user can do, the user can also undo.
- Data can easily be moved from one part of a document to another part, from one document to another, and even between documents that are created by different

applications or desk accessories. A system file called the Clipboard (a holding area for text or graphics) makes this possible.

The Edit menu allows access to the operations that delete, move, and copy objects, as well as Undo, Select All, and Show Clipboard. You can add other items to the Edit menu if your application requires them—and if they're related to the standard items already there.

All applications should support Undo and cut and paste. This requires that the first five lines in the Edit menu must be exactly as shown in Figure 30: Undo followed by a dotted line, then Cut, Copy, Paste, and Clear. This is important even if your application doesn't itself make use of undo and cut and paste—those features are available to desk accessories only through the Edit menu.

| Edit           |      |  |  |
|----------------|------|--|--|
| Undo (lest)    | ₩Z   |  |  |
| 01             | 0011 |  |  |
| Cut            | *H   |  |  |
| Copy           | ₩C   |  |  |
| Paste          | ₩U   |  |  |
| Clear          |      |  |  |
| Select All     |      |  |  |
| Show Clipboard |      |  |  |

Figure 30. Standard Edit Menu