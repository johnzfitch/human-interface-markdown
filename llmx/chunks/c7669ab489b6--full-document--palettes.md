---
chunk_index: 1996
ref: "c7669ab489b6"
id: "c7669ab489b6ae19be8f40e131488308753d006bef9b2caf9767a2f46ec39dae"
slug: "full-document--palettes"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1933, 1946]
token_estimate: 431
content_sha256: "d82e66ff6c6536587df8c277d3aadecf62a2414c267355aa617231e578ca52c9"
compacted: false
heading_path: ["Hierarchical menus","Pop-up menus","**Palettes**"]
symbol: null
address: null
asset_path: null
---

#### **Palettes**

Some applications use palettes to provide a quick way for the user to change from one operation to another. A palette is a collection of small symbols, usually enclosed in rectangles. A symbol can be an icon, a pattern, a character, or a drawing that stands for an operation. When the user has clicked on one of the symbols (or in its rectangle), it is distinguished from the other symbols (by highlighting, for example), and the previously highlighted symbol goes back to its normal state. Figure 3-45 shows two palettes from MacPaint.

![](images/_page_103_Figure_6.jpeg)

Figure 3-45 Two palettes

Typically, the symbol that's selected determines what operations the user can perform. Selecting a tool from a palette puts the user into a mode. Modes are generally discouraged but can be justified when changing from one mode to another is almost instantaneous and when the user can always see at a glance which mode is in effect. (Changing the shape of the pointer is one way to indicate that a mode has been set.) Like all modal features, palettes should be used only when they're the most natural way to structure an application.

A palette can be either part of a window (as in MacDraw) or separate from the main window (as in MacPaint). Each has its disadvantages. If the palette is part of the window, then parts of the palette may be concealed if the user makes the window smaller. On the other hand, if it's not part of the window, then it takes up extra space on the desktop (in which case it should at least be movable so the user can move it out of the way).

If an application supports multiple open documents but only one palette, the palette reflects the settings for the active window.