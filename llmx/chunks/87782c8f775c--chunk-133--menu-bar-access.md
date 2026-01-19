---
chunk_index: 2345
ref: "87782c8f775c"
id: "87782c8f775c7f60d427b356fbb32951bc5b3e34d56660591876d4f9bd242912"
slug: "chunk-133--menu-bar-access"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_133.md"
kind: "markdown"
lines: [6, 10]
token_estimate: 270
content_sha256: "1d2b500977181fdeae0416ab9a5e885b97e7380e572435152f243dd10d3701ef"
compacted: false
heading_path: ["Menu Bar Access"]
symbol: null
address: null
asset_path: null
---

#### Menu Bar Access  
When your application displays a movable modal dialog box, the system software enables the Application menu, the Help menu, and the Keyboard menu; the system software does nothing else to manage the menu bar. Your application should allow or disallow access to the rest of your menu bar as appropriate. Your application should leave the Apple menu enabled so that the user can use it to open other applications while the movable modal dialog box is on the screen. Also, if the movable modal dialog box contains editable text items, your application should enable the Cut, Copy, and Paste commands in the Edit menu as well as other context-appropriate commands  
in the Edit menu and other menus. Note that it is the responsibility of your application to always restore the menus to their previous states after removing movable modal dialog boxes. Figure 6-11 shows the Application menu open while a movable modal dialog box is on the screen.  
**Figure 6-11** Menu bar access while a movable modal dialog box is open  
![](images/_page_211_Picture_4.jpeg)