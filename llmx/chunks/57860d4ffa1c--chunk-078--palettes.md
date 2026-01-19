---
chunk_index: 1750
ref: "57860d4ffa1c"
id: "57860d4ffa1c1be3b32b72eafc1c90b8831436732a218ea0f161d47f931890b5"
slug: "chunk-078--palettes"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_078.md"
kind: "markdown"
lines: [18, 24]
token_estimate: 432
content_sha256: "a1d68645d6deb1dcd70a2646e23b5335795432ffacc4b50150cc842c473b005b"
compacted: false
heading_path: ["**Palettes**"]
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