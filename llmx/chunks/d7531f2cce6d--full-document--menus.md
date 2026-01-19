---
chunk_index: 2058
ref: "d7531f2cce6d"
id: "d7531f2cce6d6cdd904713c151b78578d02390322ed1aa055f786eaa85a57a64"
slug: "full-document--menus"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2716, 2723]
token_estimate: 279
content_sha256: "28b7eef0a93eddc34f7aee1ab69e6cc13a445894bebd755d138becdd62434bd5"
compacted: false
heading_path: ["Menus"]
symbol: null
address: null
asset_path: null
---

# Menus

In the Macintosh Plus ROM, the Menu Manager uses the system font and the system font size in setting up the height of the menu bar, and of the items in menus. Because the system font size can vary, the height of the menu bar can also vary. When determining window placement on the screen, do not assume that the menu bar height is 20. Applications should use the low memory variable MBarHeight (instead of 20) as the height of the menu bar.

If <sup>a</sup> menu contains too many items to display at once, on <sup>a</sup> Macintosh Plus the menu scrolls to reveal the hidden items. This feature was devised only for the menus to which the user can add many items—the Font menu specifically. Application programmers should not create menus that are too long to be seen without scrolling.

Applications should avoid using too many menus, because translation into other languages almost always widens menu titles, forcing some far to the right (possibly conflicting with the Switcher), or even off the screen. Applications should always leave room for the menu that some desk accessories add to the menu bar.