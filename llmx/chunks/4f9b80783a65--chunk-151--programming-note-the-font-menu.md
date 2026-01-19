---
chunk_index: 3774
ref: "4f9b80783a65"
id: "4f9b80783a65dafb03f14dac55042d8250b11d1664d2166901647e73b02e3db6"
slug: "chunk-151--programming-note-the-font-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_151.md"
kind: "markdown"
lines: [39, 45]
token_estimate: 529
content_sha256: "f054343db829e748a2991a589dbce86a3c29c3ffa37fca9dad6b2206c19c80ae"
compacted: false
heading_path: ["**Programming Note: The Font Menu**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: The Font Menu**  
By dragging this menu in from Interface Builders Palettes window, you getthis menu and its functionality from the Text object with almost no additional work. Still, you should make sure that every command works, dims, and changes it name as it should.  
**Note:** If the current selection is an insertion point, all the commands in the Font menu affect the next set of characters inserted, rather than any existing text, unless the text area can contain only one font. If an area of text can have only one font, then the Font menu and panel change the font of all the text in the area.  
The only required commands in the Font menu are Font Panel, Copy Font, and Paste Font, although frequently used commands like Bold and Italic should almost always be present. Applications that are not text intensive may decide to omit some of the less frequently used commands, such as Heavier and Lighter.  
Each command leaves the other font attributes intact. For example, Bold will change 11-point Times Roman to 11-point Times Bold and 24-point Courier Oblique to 24-point Courier Bold Oblique.  
If there's more than one font in the selection, Larger and Smaller change each to be one point larger or smaller than its current size. The other commands make only the change that's appropriate for the first character in the selection. For example, if the first character in a multifont selection is italic, the Unitalic command will remove the italic trait from all the text in the selection, but won't change any text that isn't italic. If the first character isn't italic, the same command (but now called Italic) will italicize the entire selection, but won't alter any text that's already italic.  
The Colors command, which brings up the Colors panel, often appears in the Font menu. However, it can appear elsewhere; each application should place the Colors command in a menu that indicates the kind of objects the Colors panel can affect. In Mail and Edit, colors can be applied only to characters (and not to their background), so the Colors command is in the Font menu.