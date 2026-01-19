---
chunk_index: 1994
ref: "51a917bff8db"
id: "51a917bff8dbaeef9dfdea2e5794bfc6fbc693ecb17e1f5e79cd57dcf6b12e22"
slug: "full-document--hierarchical-menus"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1878, 1903]
token_estimate: 592
content_sha256: "f6f7d9675003cdc86043b43881ba7ed87db8e888d0f10066050240783765b1c6"
compacted: false
heading_path: ["Hierarchical menus"]
symbol: null
address: null
asset_path: null
---

# Hierarchical menus

Hierarchical menus are <sup>a</sup> logical extension of the standard menu metaphor: another dimension is added to a menu, so that <sup>a</sup> menu item can be the title of a submenu. When the user drags the pointer through <sup>a</sup> hierarchical menu item, <sup>a</sup> submenu appears after a brief delay.

Hierarchical menu items have an indicator at the right edge of the menu, as shown in Figure 3-41.

![](images/_page_100_Picture_5.jpeg)

Figure 3-41 Main menu before and after a submenu appears

One main menu can contain both standard menu items and submenus; both levels can have Command-key equivalents. (The submenu title can't have <sup>a</sup> Command-key equivalent, of course, because it's not a command. Key combinations aren't used to pull down menus.)

Two delay values enable submenus to function smoothly, without jarring distractions to the user. The submenu delay is the length of time before <sup>a</sup> submenu appears as the user drags the pointer through <sup>a</sup> hierarchical menu item. It prevents flashing caused by rapid appearance-disappearance of submenus. The drag delay allows the user to drag diagonally from the submenu title into the submenu, briefly crossing part of the main menu, without the submenu disappearing (which would ordinarily happen when the pointer was dragged into another main menu item). This is illustrated in Figure 3-42.

![](images/_page_101_Figure_0.jpeg)

Figure 3-42
Dragging diagonally to a submenu item

Other aspects of submenus—menu blink, and so forth—behave exactly the same way as in standard menus.

Using standard menus, the user can drag the mouse across the menu bar and immediately see *all* of the choices currently available. Although this isn't true when hierarchical menus are used, it's important that this original capability be maintained as much as possible. To keep this essential simplicity and clarity, these guidelines should be followed:

- ☐ Hierarchical menus are used only for *lists of related items*, such as fonts or font sizes (in this case, the title of the submenu clearly tells what the submenu contains).
- □ Only one level of hierarchical menu is used. This one extra layer of menus potentially increases by an order of magnitude the number of menu items that can be used; more layers than this can make an application very confusing.