---
chunk_index: 3989
ref: "03a611346d43"
id: "03a611346d439e540346f37080570ed106d1bcc5b91701f702313709b3097f98"
slug: "full-document--how-the-arrow-keys-affect-a-text-selection"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [778, 789]
token_estimate: 437
content_sha256: "a370df2f41d3938aaa74617a7524266f971a3d45c81f71ea602b8e7bc3cf29c7"
compacted: false
heading_path: ["*Introduction*","**How the Arrow Keys Affect a Text Selection**"]
symbol: null
address: null
asset_path: null
---

## **How the Arrow Keys Affect a Text Selection**

In text, the keyboard's arrow keys are used to position the insertion point or, when modified by the Alternate key, alter the selection. But unlike the mouse, which can select anywhere within a document, the arrow keys operate only relative to the current selection. The descriptions below assume that the current selection, before the user touches an arrow key, is a range of text. The simpler case where the current selection is not a range but an insertion point is not directly addressed, but can easily be derived from the descriptions given.

**Note:** The arrow keys have nothing to do with the cursor, which is controlled only by the user's mouse movements.

When used alone (without a modifier key), the left arrow key positions the insertion point one character before the beginning of the current selection. The right arrow key puts the insertion point one character beyond the end of the current selection. These keys move the insertion point to the previous or next line if necessary.

The up arrow key puts the insertion point one line above the beginning of the current selection, and the down arrow key puts it one line below the end of the current selection. As the up and down arrow keys move it from line to line, the insertion point maintains the same approximate distance from the left margin. It falls at the end of any line that's shorter than that distance, but comes back out to the original distance when a line that's long enough is encountered.

More information on handling the arrow keys is in "Implementing Special Keys" in this chapter. Modified arrow keys-for example, Alternate-arrow-are discussed in "Implementing the Modified Arrow Keys," later in this chapter.