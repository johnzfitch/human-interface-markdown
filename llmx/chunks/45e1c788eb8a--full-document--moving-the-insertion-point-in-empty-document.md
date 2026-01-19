---
chunk_index: 2876
ref: "45e1c788eb8a"
id: "45e1c788eb8a822534d9545cdc6824c5c886753fa46d620b13109b51d2f17853"
slug: "full-document--moving-the-insertion-point-in-empty-document"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4367, 4372]
token_estimate: 216
content_sha256: "4785b3e2cffd3d69d16234af9620de79ad5e3f0c3d46b172ba13161a5cd240d6"
compacted: false
heading_path: ["The Keyboard","Arrow Keys","Appropriate Uses for the Arrow Keys","Moving the Insertion Point in Empty Documents"]
symbol: null
address: null
asset_path: null
---

#### Moving the Insertion Point in Empty Documents

Various text-editing programs treat empty documents in different ways. Some assume that an empty document contains no characters, in which case clicking at the bottom of a blank screen causes the insertion point to appear at the top. In this situation, Down Arrow cannot move the insertion point into the blank space because there are no characters there.

Other applications treat an empty document as a page of space characters, in which case clicking at the bottom of a blank screen puts the insertion point where the user has clicked and lets the user type characters there, overwriting the spaces. In this sort of application, Down Arrow moves the insertion point straight down through the spaces. Whichever of these methods you choose for your application, it's essential that you be consistent throughout.