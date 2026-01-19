---
chunk_index: 3760
ref: "9fe5ac3066eb"
id: "9fe5ac3066eb49eef695ae1a582808b12fb88e7664c7b5df2ce1210a13d82414"
slug: "chunk-141"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_141.md"
kind: "markdown"
lines: [1, 9]
token_estimate: 363
content_sha256: "ec374752d281d773cb38c73a82b872bdd69a1347065f383cb98e437a66927c67"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 141 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 336 -->
The main menu works best when it's short (so that commands are easy to find) and narrow (so that it doesn't take up much screen space). Applications should generally have no more than 11 or 12 commands in the main menu.  
The main menu is also, for the most part, a menu of menus. Commands that are added to the main menu should typically be ones that bring up submenus.  
When designing your application's user interface, you can move a command that the guidelines place in a submenu up one level to the main menu, provided that:  
- The main menu is short enough to accommodate another command.
- The command provides functionality that's considered central, even crucial, to the application. For example, a text editor might bring the Font command up to the main menu from the Format menu, but a spreadsheet would not.  
Like any other command that's added to the main menu, a command that's raised from a submenu should generally control another submenu.  
When a command is promoted to the main menu, it should, for continuity, be located immediately after the command for the submenu it would otherwise be in. For example, if the Font command is raised from the Format menu, it follows the Format command. If the Find command is promoted from the Edit menu, it follows the Edit command, as shown below.  
![](images/_page_126_Picture_8.jpeg)