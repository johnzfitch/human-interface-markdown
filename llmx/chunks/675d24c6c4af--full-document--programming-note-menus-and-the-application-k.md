---
chunk_index: 4107
ref: "675d24c6c4af"
id: "675d24c6c4afc97eb22f87e554d5b237d525b6175912155ebc0f4874bf819b77"
slug: "full-document--programming-note-menus-and-the-application-k"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1997, 2007]
token_estimate: 236
content_sha256: "d53306eb3c9634200e3df23766b4b5ef22e0703f92f242b7ef4f83355a5adcd5"
compacted: false
heading_path: ["5 *Panels*","**Programming Note: Menus and the Application Kit**"]
symbol: null
address: null
asset_path: null
---

## **Programming Note: Menus and the Application Kit**

The Application Kit takes care of everything discussed in this section, IIHow Menus Work." Specifically, it provides the following functionality:

- All aspects of displaying and hiding menus and menu commands (although you must specify when a command should be disabled), including tearing off submenus
- Letting you associate menu commands with menus
- Making sure the keyboard alternative works
- Detecting when the user chooses a menu command and reacting appropriately (such as by highlighting and bringing up a panel)

Much of this functionality can also be accessed through Interface Builder. For example, to associate an application-specific command with a menu, the programmer can simply drag a menu command from the Palettes window into the menu. You can then change the name of the command, give it a keyboard alternative if necessary, and associate an action with the command.