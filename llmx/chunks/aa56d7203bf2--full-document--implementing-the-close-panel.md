---
chunk_index: 4091
ref: "aa56d7203bf2"
id: "aa56d7203bf20757d5a9492554fa2a218843ff0d9b4cfa3d4fefb056c9b08cab"
slug: "full-document--implementing-the-close-panel"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1809, 1822]
token_estimate: 275
content_sha256: "b75631a0dcaa257338bd4f8417eef598add0696c7c56ab6d0485a651130bfea1"
compacted: false
heading_path: ["5 *Panels*","**Implementing the Close Panel**"]
symbol: null
address: null
asset_path: null
---

## **Implementing the Close Panel**

When the user closes a document that has been edited but not saved, the application must bring up a Close panel giving the user an opportunity to cancel the operation, save the document before closing, or confirm that it should be closed without saving. This attention panel should have at least these three buttons:

Cancel Don't Save Save

Save is the default option because many users don't think of closing a document and saving the most recent changes to it as separate operations-for many, closing implies saving.

If closing a document or window has consequences other than that unsaved changes would be lost, the application must still bring up a Close panel informing the user. For example, when the user closes a terminal emulation window, the application should notify the user that closing the window will cause the running command to be terminated. If the panel can't offer the user any way of avoiding the side effects, it should have these buttons:

Cancel Close Anyway

**Note:** Do *not* bring up a Close panel unless work is about to be lost.