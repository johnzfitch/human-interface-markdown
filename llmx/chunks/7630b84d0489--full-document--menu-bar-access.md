---
chunk_index: 2779
ref: "7630b84d0489"
id: "7630b84d0489c3f3a0674f3d6ef2c32f50d45fadebcc6c3d182ad2d06bdd8960"
slug: "full-document--menu-bar-access"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [3035, 3048]
token_estimate: 466
content_sha256: "64e70d4f56f22098809c02827d160719fa877e3272d5b3817ff68a23e647b9ea"
compacted: false
heading_path: ["Modal Dialog Boxes","Modal Dialog Box Behaviors","Menu Bar Access"]
symbol: null
address: null
asset_path: null
---

#### Menu Bar Access

When a modal dialog box is displayed, most menus are inaccessible, but sometimes it's useful for the user to have access to certain menus. The Help menu and the Edit menu are usually active. You can choose to enable some commands in some of your application's menus while your application displays a modal dialog box.

The Dialog Manager and the Menu Manager interact to provide various degrees of access to the menus in your menu bar. For modal dialog boxes without editable text items, you can simply allow system software to automatically provide the appropriate access to your menu bar. However, your application should handle its own menu bar access for modal dialog boxes with editable text items by disabling the Apple menu (or the first item in the Apple menu) in order to take control of its menu bar access, and by disabling all of the application's menus except the Edit menu, as well as any inappropriate commands in the Edit menu. Figure 6-15 illustrates how an application disables all of its own menus except its Edit menu when displaying a modal dialog box containing editable text items. Access to the Edit menu can be very helpful for the user who prefers to use the commands in the Edit menu to copy and paste text from one text field to another rather than retyping the text.

![](images/_page_214_Picture_7.jpeg)

**Figure 6-15** Access to the Edit menu when displaying a modal dialog box

When the user dismisses the modal dialog box, the Menu Manager restores all menus to the state they were in prior to the appearance of the modal dialog box—unless your application handles its own menu bar access, in which case you must restore the menus to their previous states.

See *Inside Macintosh: Macintosh Toolbox Essentials* for more information about providing access to the menu bar while a modal dialog box is onscreen.