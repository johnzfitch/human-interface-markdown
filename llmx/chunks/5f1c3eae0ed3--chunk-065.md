---
chunk_index: 765
ref: "5f1c3eae0ed3"
id: "5f1c3eae0ed3fe6a4f47765bff1cce19919eb4a55d3aa25ca71c00a319418f7e"
slug: "chunk-065"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_065.md"
kind: "markdown"
lines: [1, 10]
token_estimate: 485
content_sha256: "ce678f031f6567ea62d4c786e5e5b55ea747efc1c198d318a2077cb3828a1a4b"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 65 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 458 -->
Some applications use palettes as a quick way for the user to change from one operation to another. A palette is a collection of small symbols, usually enclosed in rectangles. A symbol can be an icon, a pattern, a character, or drawing that stands for an operation. When the user has clicked on one of the symbols (or in its rectangle), it is distinguished from the other symbols (by highlighting, for example), and the previously highlighted symbol goes back to its normal state. Figure 37 shows two palettes from the MacPaint application.  
Drawing tool palette, with paintbrush selected  
![](images/_page_76_Picture_2.jpeg)  
Pattern palette with solid black selected  
![](images/_page_76_Figure_4.jpeg)  
Figure 37. Two Palettes  
Typically, the symbol that's selected determines what operations the user can perform. Selecting a palette symbol puts the user into a mode. Modes are generally discouraged (see "Modelessness") but can be justified when changing from one mode to another is almost instantaneous and when the user can always see at a glance which mode is in effect. Changing the shape of the pointer is one way to indicate that a mode has been set. Like all modal features, palettes should be used only when they're the most natural way to structure an application.  
A palette can be either part of a window (as in MacDraw) or a separate window (as in MacPaint). Each system has its disadvantages. If the palette is part of the window, then parts of the palette may be concealed if the user makes the window smaller. On the other hand, if it's not part of the window, then it takes up extra space on the desktop. If an application supports multiple  
documents open at the same time, it might be better to put a separate palette in each window, so that a different palette symbol can be in effect in each document.