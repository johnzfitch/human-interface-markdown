---
chunk_index: 2841
ref: "d2b85e77ecbe"
id: "d2b85e77ecbee33ece42ffcaba1df0bfb18e108b42c770b734de9008f3d7e804"
slug: "full-document--highlighting-and-selection"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4035, 4038]
token_estimate: 219
content_sha256: "0abc8e49ed84b6ebfc371080c8f14784018a13eab18347fa4b80ad2c69b1aefd"
compacted: false
heading_path: ["Color Design of Standard Interface Elements","Highlighting and Selection"]
symbol: null
address: null
asset_path: null
---

## Highlighting and Selection

Most things—menu items, icons, buttons, and so forth—should be highlighted when selected by reversing the background with the bits. On black-and-white screens, highlighting means turning white to black and black to white. For example, if the item is black on a white background, it should be highlighted to white on a black background. On color screens, highlighting works differently; colors are darkened when selected, not reversed. For example, if an item appears green on the screen, the green color becomes darker when the item is selected. If the user can set different colors of text, Color TextEdit allows the user to set the highlighting bar color to something other than black to highlight the text better. The user can change the setting; your application should never change it. The default for the highlight color is always black.