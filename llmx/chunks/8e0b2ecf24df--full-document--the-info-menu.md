---
chunk_index: 4128
ref: "8e0b2ecf24df"
id: "8e0b2ecf24df1a7c6406a4e1aceae0361a6b1500dc7188b5539eebe4c1787d05"
slug: "full-document--the-info-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2230, 2244]
token_estimate: 722
content_sha256: "d9c34f7c5c48cfcc468956cc6761e33dd418489fe1ff4663ab342120bbe389d7"
compacted: false
heading_path: ["5 *Panels*","The Info Menu"]
symbol: null
address: null
asset_path: null
---

## The Info Menu

![](images/_page_127_Picture_1.jpeg)

The Info menu contains commands that let the user get and set information about the application, as a whole. A License command is an example of the kind of command that could be added to this menu.

| Command     | Action                                                                                                                                                                                                                                                                                                                                                                                          |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Info Panel  | Brings up a panel that displays a small amount of basic information about the application. This standard panel is described in Chapter 5, "Panels."                                                                                                                                                                                                                                             |
| Show Menus  | Displays and tiles all the application's menus. There's currently no support for this command in the Application Kit. You can implement it or not as you see fit.                                                                                                                                                                                                                               |
| Preferences | Brings up the application's Preferences panel, which permits the user to customize the application. This standard panel is described in Chapter 5.                                                                                                                                                                                                                                              |
| Help        | Brings up a panel with helpful information on how to use the application. If you implement this command, you should use the standard Help panel, which is described in Chapter 5. If you don't implement this command, then when the user Help-clicks an object in your application, the system brings up a panel informing the user that the application doesn't use the NeXTSTEP help system. |

If an application doesn't support any of the commands in the Info menu except Info Panel, it should omit the menu and make the Info command bring up the panel instead. (The command would then be followed by three dots.)