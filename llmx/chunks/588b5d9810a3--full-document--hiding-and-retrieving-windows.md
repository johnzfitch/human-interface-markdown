---
chunk_index: 4036
ref: "588b5d9810a3"
id: "588b5d9810a3613e0dc67a3466148bb04ecd63b2870a64af4cc43bcbeb6aff5a"
slug: "full-document--hiding-and-retrieving-windows"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1264, 1277]
token_estimate: 372
content_sha256: "e42430eebbbc5822d8ea147cab061c2f03edebb59b9b2960554e1b26e33b21f8"
compacted: false
heading_path: ["The Window Interface to Applications","**Miniaturizing**","**Hiding and Retrieving Windows**"]
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