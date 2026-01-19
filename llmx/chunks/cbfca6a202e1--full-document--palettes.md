---
chunk_index: 1379
ref: "cbfca6a202e1"
id: "cbfca6a202e1813db1805ded1fba7a3573c5216864425541e4edff099dcc47d9"
slug: "full-document--palettes"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1415, 1428]
token_estimate: 428
content_sha256: "30ac793cac4569fc46e71ba59a9bf6a60e42a782706cea5dab8b658025e77bc2"
compacted: false
heading_path: ["Special menu types","**Palettes**"]
symbol: null
address: null
asset_path: null
---

## **Palettes**

Some applications use palettes as a quick way for the user to change from one operation to another. A palette is a collection of small symbols, usually enclosed in rectangles. A symbol can be an icon, a pattern, a character, or a drawing that stands for an operation. When the user has clicked on one of the symbols (or in its rectangle), it is distinguished from the other symbols (by highlighting, for example), and the previously highlighted symbol goes back to its normal state. Figure 44 shows two palettes from MacPaint.

![](images/_page_96_Figure_2.jpeg)

Figure 44 Two palettes

Typically, the symbol that's selected determines what operations the user can perform. Selecting a tool from a palette puts the user into a mode. Modes are generally discouraged but can be justified when changing from one mode to another is almost instantaneous and when the user can always see at a glance which mode is in effect. (Changing the shape of the pointer is one way to indicate that a mode has been set.) Like all modal features, palettes should be used only when they're the most natural way to structure an application.

A palette can be either part of a window (as in MacDraw) or separate from the main window (as in MacPaint). Each has its disadvantages. If the palette is part of the window, then parts of the palette may be concealed if the user makes the window smaller. On the other hand, if it's not part of the window, then it takes up extra space on the desktop (in which case it should at least be movable so that the user can move it out of the way).

If an application supports multiple open documents but only one palette, the palette reflects the settings for the active window.