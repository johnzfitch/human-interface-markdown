---
chunk_index: 1641
ref: "85508c68e73a"
id: "85508c68e73ad6c183ec83fd1495af634c4e28a5af68a9af99390b0afd2e3c37"
slug: "chunk-030--menu-items"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_030.md"
kind: "markdown"
lines: [39, 56]
token_estimate: 650
content_sha256: "13a8467ac026f86b179c463ecd5459756ef6858e5cddf89222707573ad4f33a3"
compacted: false
heading_path: ["Window manipulation","Dialog boxes, alert boxes, and controls","Menus","Menu items"]
symbol: null
address: null
asset_path: null
---

#### Menu items  
Within an application, menu items don't usually vary (the exceptions are "integrated" applications in which, for example, the spreadsheet and the word processor may have different sets of menus). This consistency contributes to the user's sense of stability. Even though certain items are sometimes unavailable, they remain in the menu—dimmed to show that they're unavailable at the moment.  
The user can either browse through menu items—without having to choose any of them—or choose one item to be executed. To browse, the user simply holds the mouse button down and moves the pointer through the menu bar, which pulls down one menu at a time.  
Choosing a menu item is a deliberate process. To choose an item from the menu that's pulled down, the user drags the pointer down to that item and releases the mouse button.  
![](images/_page_39_Picture_0.jpeg)  
Figure 2-6 Menu  
Menus can include a wide range of items, typically grouped by type to make the most sense to the user (Figure 2-6).  
The **Apple menu**, often called the **desk accessory menu**, is always the leftmost menu (Figure 2-7). It lists the desk accessories that are currently installed on the system. This menu changes when the user installs a new desk accessory or deletes an old one. Desk accessories are usually "mini-applications," implemented as device drivers, that can operate at the same time as a full-scale application.  
![](images/_page_39_Picture_4.jpeg)  
Figure 2-7
The Apple menu  
The second menu is the **File menu**, which lets the user perform tasks relative to whole documents—opening, closing, saving, and printing—from within an application (Figure 2-8). A key item in the File menu is the **Quit** operation, which lets the user quit an application at any time. This is in contrast to traditional applications that require the user to step backward to a "Main Menu" before quitting.  
![](images/_page_40_Picture_0.jpeg)  
![](images/_page_40_Picture_1.jpeg)  
Figure 2-8
File and Edit menus  
There are two important principles behind the items in the **Edit menu** (Figure 2-8). First, they make it explicit that anything the user can do, the user can also *undo*. Second, they allow the user to easily move information from one part of a document to another, or between documents—even between documents that are created by different applications.  
Every application should include an Edit menu with Undo, Cut, Copy, Paste, and Clear (in that order). Even if the application itself doesn't use them, those five commands must be available for desk accessories that may need them.