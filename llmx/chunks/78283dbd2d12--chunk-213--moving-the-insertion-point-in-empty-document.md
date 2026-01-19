---
chunk_index: 2446
ref: "78283dbd2d12"
id: "78283dbd2d1278270ca6f3ce72726ba448cbdad9ac7e48b4f012d9adbbf6edb6"
slug: "chunk-213--moving-the-insertion-point-in-empty-document"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_213.md"
kind: "markdown"
lines: [15, 17]
token_estimate: 217
content_sha256: "6e218cd028ee66c3706bbbe68733b3a666f447090b05fcee82929b7b01653199"
compacted: false
heading_path: ["Appropriate Uses for the Arrow Keys","Moving the Insertion Point","Moving the Insertion Point in Empty Documents"]
symbol: null
address: null
asset_path: null
---

#### Moving the Insertion Point in Empty Documents  
Various text-editing programs treat empty documents in different ways. Some assume that an empty document contains no characters, in which case clicking at the bottom of a blank screen causes the insertion point to appear at the top. In this situation, Down Arrow cannot move the insertion point into the blank space because there are no characters there.  
Other applications treat an empty document as a page of space characters, in which case clicking at the bottom of a blank screen puts the insertion point where the user has clicked and lets the user type characters there, overwriting the spaces. In this sort of application, Down Arrow moves the insertion point straight down through the spaces. Whichever of these methods you choose for your application, it's essential that you be consistent throughout.