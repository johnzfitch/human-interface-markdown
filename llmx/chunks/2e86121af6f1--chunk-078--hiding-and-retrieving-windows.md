---
chunk_index: 3669
ref: "2e86121af6f1"
id: "2e86121af6f1836c9c1c04971c52940a0fed5455d48e591baab06108038b739a"
slug: "chunk-078--hiding-and-retrieving-windows"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_078.md"
kind: "markdown"
lines: [9, 15]
token_estimate: 374
content_sha256: "358f53bd8822ba20d7d4523b92887cf6ca0ce54b39888ecd72456ba6aa1c1cde"
compacted: false
heading_path: ["**Hiding and Retrieving Windows**"]
symbol: null
address: null
asset_path: null
---

#### **Hiding and Retrieving Windows**  
The Hide menu command lets the user clear the screen of all the windows belonging to an application. This opens up the workspace so that it's easier to work in another application.  
When an application is hidden, only its application icon remains on-screen. When the user double-clicks the icon, the hidden windows reappear on-screen. Users can resume working in the application, picking up again at exactly the point where they left off.  
Double-clicking an application icon has one other effect: It activates the application (as discussed in the next section), and so may cause the menus and panels of another application to disappear, while those of the newly activated application reappear.  
Double-clicking the icon for a running application activates it and brings its windows to the front, even if the application wasn't hidden. (The user can also bring covered windows forward using commands in the Windows menu, as described in Chapter 6.) The application's menus also return to the screen.  
If the user holds down the' Command key while double-clicking an application icon, the application is activated as usual, but in addition all other applications are hidden.  
**Note:** A window that's completely obscured by other windows is "covered," but not "hidden" in the sense used here. A covered window can be made visible by moving the windows in front of it to the side. A hidden window can't be-it's completely removed from the workspace.