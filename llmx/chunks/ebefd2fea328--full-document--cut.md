---
chunk_index: 577
ref: "ebefd2fea328"
id: "ebefd2fea328a1331c4eb2afdc304cba04398a6670bd2816ef7d758e24bca655"
slug: "full-document--cut"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1856, 1865]
token_estimate: 219
content_sha256: "49b60cbeaf7faf54267d1cd5e3fac9e8508cb1f5b29da14d67faf73e6a9cd31d"
compacted: false
heading_path: ["The Clipboard","Undo","Cut"]
symbol: null
address: null
asset_path: null
---

### Cut

The user chooses Cut either to delete the current selection or to move it. If it's a move, it's eventually completed by choosing Paste.

When the user chooses Cut, the application removes the current selection from the document and puts it in the Clipboard, replacing the Clipboard's previous contents. The place where the selection used to be becomes the new selection; the visual implications of this vary among applications. For example, in text, the new selection is an insertion point, while in an array, it's an empty but highlighted cell. If the user chooses Paste immediately after choosing Cut, the document should be just as it was before the cut; the Clipboard is unchanged.

1/15/85 Tognazzini

When the user chooses Cut, the application doesn't know if it's a deletion or the first step of a move. Therefore, it must be prepared for either possibility.