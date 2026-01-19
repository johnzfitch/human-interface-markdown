---
chunk_index: 4041
ref: "ff9cba597054"
id: "ff9cba59705430dd20cef74619afcdad5465266515e9aec09134e64b1564c6e6"
slug: "full-document--the-key-window"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1330, 1347]
token_estimate: 474
content_sha256: "3bab82c05dc7cfb418321b540f227ddf1ddbd67ebc4c20feb0d55f4ce786ea11"
compacted: false
heading_path: ["The Window Interface to Applications","**The Key Window**"]
symbol: null
address: null
asset_path: null
---

## **The Key Window**

Users expect to see their actions on the keyboard and mouse take effect not only in a particular application, but also in a particular window of that application. Each user action is associated with a window by the Window Server and Application Kit. Before acting, the user needs to know which window will be affected-there should be no surprises.

Since the mouse controls a cursor, it's quite easy for the user to determine which window a mouse action is associated with. It's whatever window the cursor is over. But the keyboard doesn't have a cursor, so there's no natural way to determine where typing will appear.

The window associated with keyboard actions, the one where typing will appear, is known as the key window. To mark the key window for users, the Application Kit highlights its title bar (by turning it black).

Key window highlighting is illustrated below.

![](images/_page_74_Picture_5.jpeg)

You can think of the highlighting as a kind of cursor for the keyboard. It shifts from window to window as the key window changes. Key-window status also moves from application to application as the active application changes. Only one window on the screen is marked at a time, and it must be in the active application. There's just one key window per machine and keyboard. Even a system that has two screens, but only one keyboard, has at most one key window.

**Note:** A window doesn't have to become the key window to receive, and act on, keyboard alternatives. It does, however, have to be in the active application.

Since the key window belongs to the active application, its black title bar has the secondary effect of helping to show which application is currently active. The key window is the most prominently marked window in the active application, making it "key" in a second sense: It's the main focus of the user's attention on the screen.