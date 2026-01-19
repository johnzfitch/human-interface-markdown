---
chunk_index: 1301
ref: "2b8d4538c190"
id: "2b8d4538c1906c5c05a0d4f25ee822a02b2d6b11591750bfb6d1c86a56b76354"
slug: "full-document--menu-items"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [499, 542]
token_estimate: 763
content_sha256: "68e03f46a39115cbedb7f9db33fb508866c4d96feadbc0c70d27d6377ff7123e"
compacted: false
heading_path: ["Screen elements","Window manipulation","Dialogs, alerts, and controls","Menu items"]
symbol: null
address: null
asset_path: null
---

#### Menu items

Within an application, menu items don't usually vary (the exceptions are "integrated" applications where, for example, the spreadsheet and the word processor may have different sets of menus). This, too, contributes to the user's sense of stability. Even though sometimes certain items are unavailable, they remain in the menu—dimmed to show that they're unavailable at the moment.

The user can either browse through menu items—without having to choose any of them—or choose one item to be executed. To browse, the user simply holds the mouse button down and moves the pointer through the menu bar, which pulls down one menu at a time.

Selecting a menu item is a deliberate process. To choose an item from the menu that's pulled down, the user drags the pointer down to that item and releases the mouse button.

Menus can include a wide range of items, typically grouped by type to make the most sense to the user.

The Apple menu, often called the desk accessory menu, is always the leftmost menu. It lists the desk accessories that are currently installed on the system. This menu changes when the users installs a new desk accessory or deletes an old ne. Desk accessories are usually "mini-applications," implemented as device drivers, that can be run at the same time as a full-scale application.

![](images/_page_37_Picture_0.jpeg)

Figure 7 The Apple menu

The second menu is the **File menu** (Figure 8), which lets the user perform tasks relative to whole documents—opening, closing, saving, and printing—from within an application. A key item in the File menu is the **Quit** operation, which lets the user quit an application at any time. This is in contrast to traditional applications that require the user to step backwards to a "Main Menu" before quitting.

| File                                    |              |
|-----------------------------------------|--------------|
| New                                     | %N           |
| Open                                    | <b>%0</b>    |
| Close<br>Save<br>Save As<br>Revert to S | %\$<br>Saved |
| Page Setur<br>Print                     | )            |
| Quit                                    | жQ           |

| Edit       |       |
|------------|-------|
| Undo       | ЖZ    |
| Cut        | жх    |
| Сору       | ЖС    |
| Paste      | ₩IJ   |
| Clear      |       |
| Select All |       |
|            |       |
| Show Clip  | board |

Figure 8
File and Edit menus

There are two important principles behind the items in the **Edit menu** (Figure 8). First, they make it explicit that anything the user can do, the user can also *undo*. Second, they allow the user to easily move information from one part of a document to another, or between documents—even between documents that are created by different applications.

Every application should include an Edit menu with Undo, Cut, Copy, Paste, and Clear (in that order). Even if the application itself doesn't use them, those five commands must be available for desk accessories that may need them.