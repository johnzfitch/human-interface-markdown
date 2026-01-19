---
chunk_index: 4028
ref: "7b7568e0d8d2"
id: "7b7568e0d8d255ab900b9e05c112c47a13e350c6df3caee2de7be8e9d6a10695"
slug: "full-document--writing-note-the-meaning-of-window"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1176, 1190]
token_estimate: 452
content_sha256: "baee68016bd233ff617a97a7d290e6449e7a051bedc971cd3416663d7424397e"
compacted: false
heading_path: ["The Window Interface to Applications","**Window Order**","**Writing Note: The Meaning of Window**"]
symbol: null
address: null
asset_path: null
---

#### **Writing Note: The Meaning of Window**

In documentation for users, the term windowgenerally refers only to standard windows, though panels and menus are acknowledged to be windows of a special type. Miniwindows, lists, and icons are referred to only by their specific names; they should not be included within the generic term window as this would imply common behavior that's lacking.

- Other menus are assigned to a tier just below the main menu. They can cover each other, but not the main menu.
- Docked application icons occupy the fifth tier. They can be covered by lists, attention panels, and menus, but not by the ordinary windows of your application.
- Floating panels are in the sixth tier. Floating panels are defined and discussed in Chapter 5.
- All other windows are grouped in the seventh-the last and largest-tier. Most of the windows seen on-screen are in this tier. They can cover each other, but can't come in front of the dock, menus, attention panels, or spring-loaded windows.

This seven-tier system keeps attention panels, menus, and docked application icons in view, and thus readily available to the user; it prevents them from being inadvertently lost in a large pile of windows. Although attention panels, menus, and docked application icons can cover other windows, the user can get them out of the way when needed. Menus can be moved to the side or closed, and the dock can be slid mostly off-screen. Attention panels should be attended to and dismissed.

To get the user's attention, when a window is first placed on-screen it comes up at the front of its tier.

**Note:** Even when a window is totally obscured by other windows, it's still considered to be on-screen; it retains its ranking in the order and can be exposed by moving the windows in front to the side.