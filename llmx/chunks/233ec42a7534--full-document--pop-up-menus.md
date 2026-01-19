---
chunk_index: 1995
ref: "233ec42a7534"
id: "233ec42a753456d69327e12cc84b125114b650632ece12375f1a669c582feec1"
slug: "full-document--pop-up-menus"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1904, 1932]
token_estimate: 507
content_sha256: "d655dd7677042553a0b4399b0ccb785935e5c04f63e83a397f83cc98fe40de8c"
compacted: false
heading_path: ["Hierarchical menus","Pop-up menus"]
symbol: null
address: null
asset_path: null
---

### Pop-up menus

Another type of menu is a pop-up menu. A pop-up menu isn't in the menu bar, but appears somewhere else on the screen (usually in a dialog box) when the user clicks in a particular place.

![](images/_page_102_Picture_0.jpeg)

Figure 3-43 A dialog box with pop-up menus

Pop-up menus are used for setting values or choosing from lists of related items. The indication that there is a pop-up menu is a box around the current value, with a one-pixel-thick drop shadow (Figure 3-43). When the user presses on this box, the pop-up menu appears, with the current value—checked and highlighted—under the pointer (Figure 3-44). If the menu has a title, the title highlights while the menu is visible.

![](images/_page_102_Figure_3.jpeg)

Figure 3-44
A pop-up menu as the pointer is dragged through It

The pop-up menu acts like other menus: the user can move around inside it and choose another item, which then appears highlighted in the box, or can move outside it to leave the current value active. If it reaches the top or bottom of the screen, a pop-up menu scrolls like other menus.

If your application uses pop-up menus, keep the following guidelines in mind:

- □ Pop-up menus are used only for lists of values or related items (similar to hierarchical submenus); they should not be used for commands.
- ☐ You must draw the shadowed box indicating that there is a pop-up menu, so the user knows that it's there—pop-up menus are never invisible.
- □ While the menu is showing, its title is inverted. If several pop-up menus are near each other, this clears up the possible ambiguity about which one is being chosen from.

- ☐ The current value always appears under the pointer when the menu appears, so that simply clicking on the box doesn't change the item.
- ☐ Don't use hierarchical pop-up menus.
- □ Pop-up menus don't have Command-key equivalents.

Always consider whether a pop-up menu is the simplest thing to use in each case, or whether a standard menu or a scrolling box might be more appropriate.