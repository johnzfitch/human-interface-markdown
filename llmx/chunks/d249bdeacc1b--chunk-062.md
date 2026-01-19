---
chunk_index: 3649
ref: "d249bdeacc1b"
id: "d249bdeacc1befd61e0090d0223c7c1692fcd5e1c14a78e98618a3be671dfbb2"
slug: "chunk-062"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_062.md"
kind: "markdown"
lines: [1, 3]
token_estimate: 271
content_sha256: "6756017636af5d055b04870c835e0a2de086b9d836cee482de0c7319e3e77466"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 62 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 244 -->
A visible cursor is essential for mouse actions, but it can get in the way when the user is concentrating on using the keyboard. Therefore, the Text object automatically hides the cursor-making it disappear from the screen-when the user begins entering text. A hidden cursor returns to the screen as soon as the user moves the mouse, signaling a shift in attention away from the keyboard back to the mouse.  
The cursor should also be hidden whenever the user selects an insertion point or a range of text. (This is not currently implemented by the Text object, so each application should do this for itself.) A new selection is a good indication that the user is ready to begin typing again. Hiding the cursor when the user selects a new insertion point avoids confusion between the I-beam cursor and the vertical bar representing the insertion point. Unless it's hidden, the I-beam can obscure the vertical bar. Again, the cursor reappears as soon as the user moves the mouse.