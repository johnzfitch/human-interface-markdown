---
chunk_index: 1324
ref: "6600b1f228fb"
id: "6600b1f228fbd165ed0e0a0adc13eb064d7073fa166b1e787babdd08b3be0f40"
slug: "full-document--automatic-scrolling"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [789, 804]
token_estimate: 692
content_sha256: "7e8190ad2ce175348c840806063a49fd5ad1979c49895da318024c14fa3cfed6"
compacted: false
heading_path: ["Proportional scroll boxes","Automatic scrolling"]
symbol: null
address: null
asset_path: null
---

#### Automatic scrolling

There are four instances when the application, rather than the user, scrolls the document. These instances involve some potentially sticky problems about how to position the document within the window after scrolling.

- When the user reaches the edge of the window while entering information into the document from the keyboard, scrolling happens automatically. The distance scrolled depends on the application: one line in a word processor, one field in a data base or spreadsheet.
- When the user moves the pointer past the edge of the window while holding down the mouse button, the window keeps up with the selection by scrolling automatically in the direction the pointer has been moved. The rate of scrolling is the same as if the user were pressing on the corresponding scroll arrow or arrows.
- When the user performs an operation on a selection that isn't currently showing in the window, it's usually because the user has scrolled the document after making a selection. In this case, the application scrolls the window so that the selection is showing before performing the operation. This makes it clear to the user what is being changed.
- When the application performs an operation whose side effect is to make a new selection or move the insertion point, scrolling happens automatically. An example is a search operation, after which the object of the search is selected. If the new selection isn't already showing in the window, the application must scroll the document to show it. Another example: After a paste operation, the insertion point is after the end of the thing that was pasted, which sometimes makes scrolling necessary.

The second and third cases present the same problem: Where should the selection be positioned within the window after scrolling? The primary rule is that the application should avoid unnecessary automatic scrolling. Users prefer to retain control over the positioning of a document. The following guidelines should be helpful:

- If part of the new selection is already showing in the window, don't scroll at all. An exception to this rule is when the part of the selection that isn't showing is more important than the part that is showing.
- If scrolling in one orientation (either horizontal or vertical) is enough to reveal the selection, don't scroll in both orientations.
- If the selection is smaller than the window, position the selection so that some of its context is showing on each side. It's better to put the selection somewhere near the middle of the window than right up against the corner.
- Even if the selection is too large to show in the window, it might be preferable to show some context rather than to try to fit as much as possible of the selection in the window.