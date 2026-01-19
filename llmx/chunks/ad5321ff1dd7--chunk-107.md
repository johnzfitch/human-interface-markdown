---
chunk_index: 2304
ref: "ad5321ff1dd7"
id: "ad5321ff1dd7d249a86f5bbdc13d55b4de8e64d88fb87bb3f9d551eb63cc2cad"
slug: "chunk-107"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_107.md"
kind: "markdown"
lines: [1, 9]
token_estimate: 585
content_sha256: "070c1dc417ef4c285eaa3526ef377d7f2d546455ed3b88e916a8dc76ecc13e79"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 107 | Source: 1992 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 560 -->
The **Size menu** provides size choices for fonts. Font sizes are measured in points. A **point** is a typographical unit of measure equivalent to 1/72 inch. Indicate the current font size with a checkmark. As described in the section "Checkmarks and Dashes in Menus," which begins on page 64, use dashes to indicate when more than one font size applies to the current selection. Figure 4-85 shows a typical Size menu.  
**Figure 4-85** A Size menu  
![](images/_page_145_Picture_9.jpeg)  
System 7 supports both bitmapped and TrueType fonts. To incorporate basic support for TrueType fonts into your application, provide support for all font sizes in your application. Don't set an upper limit for font sizes. Outline the font sizes in the menu for those sizes that appear in the user's System file. Use plain type for font sizes that aren't in the System file. If a TrueType font is present, outline all sizes of that font that you display in the menu. Provide a way for users to choose whatever font size they desire.  
One way that you can support TrueType fonts is to add an Other command to the end of the Size menu. When the user chooses Other, display a dialog box that allows the user to choose any available font size by typing in a text box. If the user enters a font size not currently on the menu, add a checkmark to the Other command and include the font size as part of the Other command name. Show the font size in parentheses after the word Other. If a selection contains more than one nonstandard size, include the word Mixed in parentheses following the word Other. In this case, leave the text box of the font size dialog box blank when the user chooses the Other (Mixed) command. Figure 4-86 displays a sample pull-down Size menu and font size dialog box. See *Inside Macintosh: Text* for more information on supporting fonts in your application.  
**Figure 4-86** A sample pull-down Size menu and font size dialog box  
![](images/_page_146_Picture_5.jpeg)  
It's possible to implement the Size and Style menus as submenus in a hierarchical menu. For information on doing so and the tradeoffs that you need to consider before implementing the menus this way, see the section "Hierarchical Menus," which begins on page 79.