---
chunk_index: 2696
ref: "3ba7d45759a4"
id: "3ba7d45759a4c17e80a2920e90e376f136eaa0ba44d00a161aa0b3585253b525"
slug: "full-document--a-diamond-mark-in-the-application-menu"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1483, 1494]
token_estimate: 283
content_sha256: "7fc4a5f3d3abbd7d74e9019f002c02af0386de77c1a07d1327ecd86172cd9219"
compacted: false
heading_path: ["Standard Characters and Text Style in Menus","A Diamond Mark in the Application Menu"]
symbol: null
address: null
asset_path: null
---

## A Diamond Mark in the Application Menu

When your application is running a background task and you need to notify the user of something that needs attention, you can use various techniques provided by the Notification Manager to get the user's attention. At the minimum, display a diamond-shaped mark next to your application's name in the Application menu to indicate that it is the application that is asking for the user's attention and alternate a small icon in the menu bar with the icon for the Application menu. In general, you should use the small icon that corresponds to your application or system extension, so that the user gets an additional visual clue about which application is requesting attention.

Figure 4-25 shows an example of a notification symbol in a menu.

**Figure 4-25** The Application menu with a notification symbol

![](images/_page_95_Picture_4.jpeg)

There are other notification techniques as well. You can also play a sound and put up an alert box to notify the user. See *Inside Macintosh: Processes* for more information on notification techniques and implementing the Notification Manager.