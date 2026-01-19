---
chunk_index: 937
ref: "df8088a3d87a"
id: "df8088a3d87a342d97de49d2087c302db525fbe67bfd892a19996e8618737d97"
slug: "full-document--palettes"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1696, 1715]
token_estimate: 461
content_sha256: "75e8b885b325b209979440b0479aa371e11f39094a9a54688f501ef6d0b8da73"
compacted: false
heading_path: ["Standard Menus","The Apple **Menu**","**Palettes**"]
symbol: null
address: null
asset_path: null
---

### **Palettes**

Some applications use palettes as a quick way for the user to change from one operation to another. A palette is a collection of small symbols, usually enclosed in rectangles. A symbol can be an icon, a pattern, a character, or drawing that stands for an operation. When the user has clicked on one of the symbols (or in its rectangle), it is distinguished from the other symbols (by highlighting, for example), and the previously highlighted symbol goes back to its normal state. Figure 37 shows two palettes from the MacPaint application.

Drawing tool palette, with paintbrush selected

![](images/_page_76_Picture_2.jpeg)

Pattern palette with solid black selected

![](images/_page_76_Figure_4.jpeg)

Figure 37. Two Palettes

Typically, the symbol that's selected determines what operations the user can perform. Selecting a palette symbol puts the user into a mode. Modes are generally discouraged (see "Modelessness") but can be justified when changing from one mode to another is almost instantaneous and when the user can always see at a glance which mode is in effect. Changing the shape of the pointer is one way to indicate that a mode has been set. Like all modal features, palettes should be used only when they're the most natural way to structure an application.

A palette can be either part of a window (as in MacDraw) or a separate window (as in MacPaint). Each system has its disadvantages. If the palette is part of the window, then parts of the palette may be concealed if the user makes the window smaller. On the other hand, if it's not part of the window, then it takes up extra space on the desktop. If an application supports multiple

documents open at the same time, it might be better to put a separate palette in each window, so that a different palette symbol can be in effect in each document.