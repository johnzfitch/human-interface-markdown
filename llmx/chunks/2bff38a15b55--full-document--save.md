---
chunk_index: 917
ref: "2bff38a15b55"
id: "2bff38a15b5514eff203f83665751798596f9d9c63d793c5d0188d742b6f0124"
slug: "full-document--save"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1490, 1499]
token_estimate: 316
content_sha256: "83ad53b8cd42e007d2b15052615d02be8cbc7d60e1c4ba33b8c90a1f91c775bf"
compacted: false
heading_path: ["Standard Menus","The Apple **Menu**","*Open*","Save"]
symbol: null
address: null
asset_path: null
---

#### Save

This menu item lets the user write (to the appropriate disk file) the active document, including any changes made to the that document since the last time it was saved. The document remains open. Users appreciate seeing, at this point, a message (or at least a wristwatch pointer) telling them the document is indeed being saved.

If no changes have been made since the last save, the Save option should be dimmed. Save becomes available as soon as any change has been made to the document—the user can save changes as often as she likes. If Save isn't dimmed and the user chooses Save even though no changes have been made, an application shouldn't simply ignore the Save request—it should instead display a brief message noting that no save is being done, and why.

If the user chooses Save for a new untitled document (one the user hasn't named yet), the application presents the Save As dialog box (shown below). This dialog box allows the user to name the document before the application continues with the save. The active document remains active.

If there's not enough room on the disk to save the document, the application says so. The application then suggests that the user can choose Save As instead, to save the document on another disk.