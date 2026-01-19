---
chunk_index: 1498
ref: "38034379186f"
id: "38034379186f5f535f35b1b2939b12390c3d3206d9076219b7dd40c82010a36b"
slug: "full-document--5-pop-up-menus"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [2549, 2579]
token_estimate: 561
content_sha256: "a2d1fbfc8501d5bca8bec90c6f27dbd5b8e21d033e9be365a2f18db24d1744ea"
compacted: false
heading_path: ["#5. Pop-up Menus"]
symbol: null
address: null
asset_path: null
---

# #5. Pop-up Menus

By: Katie Withey Date: 31 March 87

This information will be in the final versions of Inside Macintosh, vol. V and Human Interface Guidelines: the Apple Desktop Interface (to be published by Addison Wesley)

Another new new sort of menus are pop-up menus. A pop-up menu is one that isn't in the menu bar, but appears somewhere else on the screen (usually in a dialog) when the user presses in a particular place.

![](images/_page_166_Picture_6.jpeg)

Figure 1. A dialog box with pop-up menus

Pop-up menus are used for setting values or choosing from lists of related items. The indication that there is a pop-up menu is a box with a one-pixel thick drop shadow, drawn around the current value. When the user presses on this box, the pop-up menu appears, with the current value—checked and highlighted—under the pointer. If the menu has a title, the title highlights while the menu is visible.

![](images/_page_167_Figure_0.jpeg)

Figure 2. A pop-up menu as the pointer is dragged through it.

The pop-up menu acts like other menus: the user can move around in it and choose another item, which then appears in the box, or can move outside it to leave the current value active. If it reaches the top or bottom of the screen, a pop-up menu scrolls like other menus.

When designing an application that uses pop-up menus, keep in mind the following points:

- Pop-up menus should only be used for lists of values or related items (much like hierarchical menus); they should not be used for commands.
- You must draw the shadowed box indicating that there is a pop-up menu, so the user knows that it's there—pop-up menus should never be invisible.
- While the menu is showing, its title should be inverted. If several pop-up menus are near each other, this clears up the possible ambiguity about which one is being chosen from.
- The current value should always appear under the pointer when the menu appears, so that simply clicking on the box doesn't change the item.
- Hierarchical pop-up menus should not be used.
- Pop-up menus don't have Command-key equivalents.

Always consider whether a pop-up menu is the simplest thing to use in each case, or whether a standard menu or a scrolling box might be more appropriate.