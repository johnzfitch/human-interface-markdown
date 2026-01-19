---
chunk_index: 2775
ref: "682d6bccae9d"
id: "682d6bccae9dfa5c24888b4952b3434f8fb2cf09ec224f8477a4ee34fadb7219"
slug: "full-document--menu-bar-access"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2985, 2994]
token_estimate: 269
content_sha256: "8a4ceecb353cb03c51c9288980e360ad1682a49f9258999e3fc1cb5af3021cef"
compacted: false
heading_path: ["Movable Modal Dialog Boxes","Movable Modal Dialog Box Behaviors","Menu Bar Access"]
symbol: null
address: null
asset_path: null
---

#### Menu Bar Access

When your application displays a movable modal dialog box, the system software enables the Application menu, the Help menu, and the Keyboard menu; the system software does nothing else to manage the menu bar. Your application should allow or disallow access to the rest of your menu bar as appropriate. Your application should leave the Apple menu enabled so that the user can use it to open other applications while the movable modal dialog box is on the screen. Also, if the movable modal dialog box contains editable text items, your application should enable the Cut, Copy, and Paste commands in the Edit menu as well as other context-appropriate commands

in the Edit menu and other menus. Note that it is the responsibility of your application to always restore the menus to their previous states after removing movable modal dialog boxes. Figure 6-11 shows the Application menu open while a movable modal dialog box is on the screen.

**Figure 6-11** Menu bar access while a movable modal dialog box is open

![](images/_page_211_Picture_4.jpeg)