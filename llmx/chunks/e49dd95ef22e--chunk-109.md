---
chunk_index: 1810
ref: "e49dd95ef22e"
id: "e49dd95ef22ec97337e7cf257c5158e71ee68a7deecb1896ada49b5349b0189c"
slug: "chunk-109"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_109.md"
kind: "markdown"
lines: [1, 4]
token_estimate: 307
content_sha256: "7743df2e7937b85a2c5efcbfb0faa3ca8312a2bf806a123d60338647f9fa7898"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 109 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 277 -->
In the Macintosh Plus ROM, the Menu Manager uses the system font and the system font size in setting up the height of the menu bar, and of the items in menus. Because the system font size can vary, the height of the menu bar can also vary. When determining window placement on the screen, do not assume that the menu bar height is 20. Applications should use the low memory variable MBarHeight (instead of 20) as the height of the menu bar.  
If <sup>a</sup> menu contains too many items to display at once, on <sup>a</sup> Macintosh Plus the menu scrolls to reveal the hidden items. This feature was devised only for the menus to which the user can add many items—the Font menu specifically. Application programmers should not create menus that are too long to be seen without scrolling.  
Applications should avoid using too many menus, because translation into other languages almost always widens menu titles, forcing some far to the right (possibly conflicting with the Switcher), or even off the screen. Applications should always leave room for the menu that some desk accessories add to the menu bar.