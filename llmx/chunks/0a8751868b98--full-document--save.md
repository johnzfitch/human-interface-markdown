---
chunk_index: 2715
ref: "0a8751868b98"
id: "0a8751868b988b9a90d9e88c301878b33e31d2eefbc483b56eb2be75c973f022"
slug: "full-document--save"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1894, 1911]
token_estimate: 273
content_sha256: "bcf1b3bee93c7780c04c73cc243bf7157a06380c7694193f9915976a24e84db8"
compacted: false
heading_path: ["Standard Macintosh Menus","File Menu","New","Save"]
symbol: null
address: null
asset_path: null
---

#### Save

The Save command lets the user save the active document to a disk, including any changes made to that document since the last time it was saved. Figure 4-66 shows the Save command.

**Figure 4-66** The Save command

![](images/_page_128_Picture_3.jpeg)

The document remains open. Provide feedback to the user that the document is being saved. Use the animated watch cursor if the save takes approximately one or two seconds. If the operation takes much longer, display a status bar or other message box.

If the user chooses Save for a new untitled document (one that the user hasn't saved yet), display the Save As dialog box described in the next section.

If there's not enough room on the selected disk to save the document, display a caution alert box that says so and suggest that the user can use Save As instead to save the document on another disk. *Don't* destroy the document just because the current disk is full. Figure 4-67 shows a sample alert box for this case.

**Figure 4-67** A sample alert box to use when a disk is full

![](images/_page_128_Figure_8.jpeg)