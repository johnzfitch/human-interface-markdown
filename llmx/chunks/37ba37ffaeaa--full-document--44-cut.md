---
chunk_index: 84
ref: "37ba37ffaeaa"
id: "37ba37ffaeaa489aa177b4b38abd421b39ebb6d5a1711a7d2917afa5eab5911b"
slug: "full-document--44-cut"
path: "marker/1980 Lisa UI Standards/full_document.md"
kind: "markdown"
lines: [495, 508]
token_estimate: 324
content_sha256: "ab07909d3874c33d74cb9dd1ed6f866c504ad1de679c78150e09167ba2e8e90d"
compacted: false
heading_path: ["43. THE EDIT MENU","44. CUT"]
symbol: null
address: null
asset_path: null
---

## 44. CUT

Choosing the Cut command from the Edit menu places the current selection in the scrap folder, and deletes it from the active folder.

An attempt to Cut when the selection contains no characters makes no change to the document or to the scrap folder. The user is warned that Cut will not work when the selection contains no characters since the menu item is dimly highlighted at those times.

If there was no scrap folder when Cut is first executed, one is automatically created and placed on the desk as a closed folder.

If there is some text in the scrap folder and a new selection is cut from a document (not necessarily from the same document or folder as the previous cut), the old scrap text is lost (unless an Undo is the very next command) and the material just cut becomes the contents of the scrap folder.

When a selection is cut, the remaining text in the document (if any) is "pulled in" following the normal word-wrap rules. If words or sentences are cut, and the wrong number of spaces remain for proper typography, the system fixes things up automatically.

Tot all portions of all documents are cuttable, e.g. protected portions of forms. In first release, at least, the entire Scrap Folder is not only read only, but it is also impossible to make selections in it.