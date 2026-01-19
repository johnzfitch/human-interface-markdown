---
chunk_index: 3622
ref: "aa4fc83483ad"
id: "aa4fc83483ad8e04646a4cc97ed8d9a50171da889ad6231ee479ae2c65aef00c"
slug: "chunk-041"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_041.md"
kind: "markdown"
lines: [1, 6]
token_estimate: 451
content_sha256: "b3837dd0d1d9d6fcfac5c0a8b86d9dd77cb5d8d258d267cfaed5c0225368cd05"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 41 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 425 -->
In text, the keyboard's arrow keys are used to position the insertion point or, when modified by the Alternate key, alter the selection. But unlike the mouse, which can select anywhere within a document, the arrow keys operate only relative to the current selection. The descriptions below assume that the current selection, before the user touches an arrow key, is a range of text. The simpler case where the current selection is not a range but an insertion point is not directly addressed, but can easily be derived from the descriptions given.  
**Note:** The arrow keys have nothing to do with the cursor, which is controlled only by the user's mouse movements.  
When used alone (without a modifier key), the left arrow key positions the insertion point one character before the beginning of the current selection. The right arrow key puts the insertion point one character beyond the end of the current selection. These keys move the insertion point to the previous or next line if necessary.  
The up arrow key puts the insertion point one line above the beginning of the current selection, and the down arrow key puts it one line below the end of the current selection. As the up and down arrow keys move it from line to line, the insertion point maintains the same approximate distance from the left margin. It falls at the end of any line that's shorter than that distance, but comes back out to the original distance when a line that's long enough is encountered.  
More information on handling the arrow keys is in "Implementing Special Keys" in this chapter. Modified arrow keys-for example, Alternate-arrow-are discussed in "Implementing the Modified Arrow Keys," later in this chapter.