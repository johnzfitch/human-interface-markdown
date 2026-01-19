---
chunk_index: 3792
ref: "bd80beadb803"
id: "bd80beadb8030c9f54a03a414eeffccbdb6b32c164bba86c84778f351f457726"
slug: "chunk-159"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_159.md"
kind: "markdown"
lines: [1, 16]
token_estimate: 479
content_sha256: "71b970ef9cb660dd158657d3583e7ede2d4bfeb8f359e184ec48daa386d2a65a"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 159 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 784 -->
A button's appearance during a click (or while it's pressed) should change in one of the following ways:  
- It can highlight.
- It can both highlight and appear to be pushed in.
- It can change the image it displays.  
**Note:** Highlighting can be done either automatically by the Application Kit or by changing the image to a custom, "highlighted" image.  
Buttons normally both push in and highlight. However, for aesthetic reasons, buttons that are right next to each other (such as scroll buttons and graphical radio buttons) shouldn't push in. This is because buttons that have no space around their bezeled edges look less three-dimensional than normal.  
**Note:** Although it's possible to have a button only push in (without highlighting), this isn't recommended because it's hard to see.  
The recommended changes for action (one-state) buttons are illustrated in the following figure. The scroll button in the bottom row doesn't push in, since it's very small and is right up against another scroll button.  
![](images/_page_152_Picture_9.jpeg)  
The possibilities for two-state buttons are illustrated in the following figure.  
![](images/_page_152_Picture_11.jpeg)  
Note: In the figure showing two-state buttons, the button in the bottom row is a graphical radio button. It doesn't push in because it's right next to the other radio buttons in its group (although they aren't shown in this figure).  
The figure of two-state buttons also illustrates some of the principles that determine how a button looks during a click:  
- A button must change its appearance during a click, as soon as the mouse button goes down.
- The appearance of a button during a click should reflect what's about to happen. Buttons that display a state should reflect the new state both during and after the click.