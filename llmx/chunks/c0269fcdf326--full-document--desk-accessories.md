---
chunk_index: 1336
ref: "c0269fcdf326"
id: "c0269fcdf326263bc0a6fcd26585386b2402769aa75e803e9885b48923e28101"
slug: "full-document--desk-accessories"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [965, 986]
token_estimate: 711
content_sha256: "d0edf741bce20460aa27c4e3125347e8525e1e95bf93033d62dad65fcdd16bc9"
compacted: false
heading_path: ["Controls, dialogs, and alerts","**Desk Accessories**"]
symbol: null
address: null
asset_path: null
---

## **Desk Accessories**

A desk accessory is a program with a relatively limited scope that can be opened while another application is running. Desk accessories can be created for a wide range of things. Some imitate useful objects found on real desktops—the standard Macintosh Note Pad, Alarm Clock, and Calculator, for example. Some (the Chooser, for example) are file- or network-related utilities that users may need to access from within a number of different applications. Some are specific to an application or type of application: rulers and other graphics tools that are available only from graphics applications, and spelling checkers that are needed only when a word processing application is being used. There are also "idle" programs that blank the screen or display special graphics after the computer has been idle for a specified period of time.

![](images/_page_67_Figure_0.jpeg)

Figure 24 Some desk accessories

The user can quickly open one or more desk accessories by choosing them from the Apple menu. Generally, all installed desk accessories can be accessed from the Finder or from any other application, except for desk accessories that are specific to a particular application or type of application.

Don't design a full-scale application and implement it as a desk accessory. If it's really an application, treat it as an application. Remember that there is a limit on the number of desk accessories that can be installed at one time. On the other hand, if your application is a relatively small one that is useful in a variety of situations, consider making it a desk accessory.

Desk accessories don't have to be windows, but desk accessories that are windows should behave like windows: the user can move them around the screen and dismiss them by clicking a close box.

A desk accessory can add one (and only one) menu to the application's menu bar. This menu goes away when the desk accessory is closed. Desk accessories should never interfere with the application's menus.

If possible, let users install and remove all desk accessories in one standard way. Users should be able to install all Macintosh desk accessories with the standard Font/DA Mover rather than with a special installation program.

All applications should treat desk accessories in a standard way. If a desk accessory opens a window, that window should remain open on the desktop until the user explicitly closes it or quits the current application. The principle "the user is control" suggests that an application should not close desk accessories just because the user opens or closes document windows. When help systems are implemented as desk accessories, for example, the user can open and close document windows without losing the help window.

There's more on desk accessories under the heading "The Apple Menu" in this chapter.