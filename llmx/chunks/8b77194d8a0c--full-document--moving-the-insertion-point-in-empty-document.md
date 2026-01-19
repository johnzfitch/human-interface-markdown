---
chunk_index: 1409
ref: "8b77194d8a0c"
id: "8b77194d8a0cb458b75decc6157eb8eb33bd6ffee1a8e2be5ba46bf767406d5f"
slug: "full-document--moving-the-insertion-point-in-empty-document"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1639, 1646]
token_estimate: 215
content_sha256: "d72537a00bb842f6f1f22290a90c57477068b13e21e6650677ee8740d3d5ec3c"
compacted: false
heading_path: ["Moving the insertion point in empty documents"]
symbol: null
address: null
asset_path: null
---

# Moving the insertion point in empty documents

Various text-editing programs treat empty documents in different ways. Some assume that an empty document contains no characters, in which case clicking at the bottom of a blank screen causes the insertion point to appear at the top. In this situation, Down Arrow cannot move the insertion point into the blank space (because there are no characters there).

Other applications treat an empty document as a page of space characters, in which case clicking at the bottom of a blank screen puts the insertion point where the user clicked and lets the user type characters there, overwriting the spaces. In this sort of application, Down Arrow moves the insertion point straight down through the spaces.

Whichever of these methods you choose for your application, it's essential that you be consistent throughout.