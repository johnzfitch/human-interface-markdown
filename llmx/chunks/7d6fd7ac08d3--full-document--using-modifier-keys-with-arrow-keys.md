---
chunk_index: 1410
ref: "7d6fd7ac08d3"
id: "7d6fd7ac08d3b4bf7f6f628e14a758b0a4bc0e1f36d7974d68711c1319af428f"
slug: "full-document--using-modifier-keys-with-arrow-keys"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1647, 1656]
token_estimate: 511
content_sha256: "8cf62738d534a8652974a85402ad532c547f8feb0f2dc15ea40d80e5f99ea222"
compacted: false
heading_path: ["Using modifier keys with arrow keys"]
symbol: null
address: null
asset_path: null
---

# Using modifier keys with arrow keys

Holding down the Apple key while pressing an arrow key should move the insertion point to the appropriate edge of the window. If the insertion point is already at the edge of the window, then the document is scrolled one windowful in the appropriate direction and the insertion point moves to the same edge of the new windowful. Apple–Up Arrow moves the insertion point to the top of the window, Apple–Down Arrow to the bottom, Apple–Left Arrow to the left edge, and Apple–Right Arrow to the right edge.

With respect to the arrow keys, the Option key is reserved as a "semantic modifier." The application determines what the semantic units are. For example, in a word processor, where the basic semantic unit is the word, Option–Left Arrow and Option-Right Arrow might move the insertion point to the beginning and end, respectively, of a word. (Movement of the insertion point by word boundaries should use the same definition of word that the application uses for double-clicking.) In a programming-language editor, where the basic semantic unit is the token, Option–Left Arrow and Option–Right Arrow might move the insertion point left and right to the beginning and end of the token, respectively.

In an application (such as a spreadsheet) that represents itself as an array, the basic semantic unit would be the cell. Option-Left Arrow would designate the cell to the left of the currently active cell as the new active cell, and so on. Using modifier keys with arrow keys doesn't do anything to the data; Option-Left Arrow just performs an Enter and moves the selection to the next cell to the left.

Though the use of multiple modifier-key combinations (such as Apple-Option-Left Arrow) is discouraged, it's all right to use the Shift key with any *one* of the other modifier keys for making a selection. (See "Making a Selection With Arrow Keys.") If multiple keys must be pressed simultaneously, they should be fairly close together—otherwise many people won't be able to use that combination.