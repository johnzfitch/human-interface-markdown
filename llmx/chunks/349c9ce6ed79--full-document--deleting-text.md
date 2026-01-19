---
chunk_index: 2899
ref: "349c9ce6ed79"
id: "349c9ce6ed79e3f5ebd57764a49ff5df30b50940877eb11f28962c5f13e1a6b2"
slug: "full-document--deleting-text"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4707, 4719]
token_estimate: 231
content_sha256: "e48c158d5eab17482908191dcb72467777e306fed6a0eedf232fc6dbdf5f6316"
compacted: false
heading_path: ["Editing Text","Deleting Text"]
symbol: null
address: null
asset_path: null
---

## Deleting Text

When the user presses the Delete (or Backspace) key, one of two things happens:

- If the current selection has one or more characters, it's deleted. This behavior is equivalent to choosing Clear from the Edit menu.
- If there is no current selection, but only an insertion point, the character preceding the insertion point is deleted.

In either case, the insertion point replaces the deleted character or characters in the document. The deleted characters don't go into the Clipboard, but the user can undo the deletion by immediately choosing Undo from the Edit menu.

You can also implement the keyboard combination Option-Delete (Backspace) to delete the word that currently contains the insertion point. Be sure to document this behavior if you implement it.

If a keyboard has a Forward Delete (Del) key, the character following the insertion point is deleted each time the user presses the key.