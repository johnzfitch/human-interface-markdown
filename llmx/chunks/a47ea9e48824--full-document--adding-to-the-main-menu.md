---
chunk_index: 4127
ref: "a47ea9e48824"
id: "a47ea9e48824278c39cf74fa02a877708b39af022db6ce77cf41ca9ab54a92b9"
slug: "full-document--adding-to-the-main-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2213, 2229]
token_estimate: 344
content_sha256: "c0c98487e29b4bcc192d45f74b3d4508ffd3ffc2a1709f4f722a46017bd18dc3"
compacted: false
heading_path: ["5 *Panels*","**Adding to the Main Menu**"]
symbol: null
address: null
asset_path: null
---

## **Adding to the Main Menu**

The main menu works best when it's short (so that commands are easy to find) and narrow (so that it doesn't take up much screen space). Applications should generally have no more than 11 or 12 commands in the main menu.

The main menu is also, for the most part, a menu of menus. Commands that are added to the main menu should typically be ones that bring up submenus.

When designing your application's user interface, you can move a command that the guidelines place in a submenu up one level to the main menu, provided that:

- The main menu is short enough to accommodate another command.
- The command provides functionality that's considered central, even crucial, to the application. For example, a text editor might bring the Font command up to the main menu from the Format menu, but a spreadsheet would not.

Like any other command that's added to the main menu, a command that's raised from a submenu should generally control another submenu.

When a command is promoted to the main menu, it should, for continuity, be located immediately after the command for the submenu it would otherwise be in. For example, if the Font command is raised from the Format menu, it follows the Format command. If the Find command is promoted from the Edit menu, it follows the Edit command, as shown below.

![](images/_page_126_Picture_8.jpeg)