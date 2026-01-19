---
chunk_index: 1997
ref: "796f830a81ea"
id: "796f830a81ea9a7ab4a91cd8aed96f98843d6a03258fe91a4b49fb25d4ed072a"
slug: "full-document--tear-off-menus"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1947, 1972]
token_estimate: 423
content_sha256: "eab268e29aa01375ff5ebaf494606babaee4ef6d60a68da1e105e38e487564fd"
compacted: false
heading_path: ["Hierarchical menus","Pop-up menus","**Palettes**","Tear-off menus"]
symbol: null
address: null
asset_path: null
---

#### Tear-off menus

A tear-off menu is a menu, generally graphic rather than textual, that the user can "tear" from the menu bar and move around the screen like a window. Tear-off menus save desktop space, allow larger windows, and give the user more flexibility than do fixed palettes.

The user can choose a pattern from the tear-off menu shown in Figure 3-46 simply by pulling down the menu like any other menu, then dragging the pointer to the desired pattern and releasing the mouse button.

![](images/_page_104_Picture_5.jpeg)

Figure 3-46 Graphic pull-down menu

If the user holds down the Apple key while opening such a menu, then moves the pointer more than ten pixels from any edge of the menu, an outline of the menu follows the pointer. When the mouse button is released, the menu appears at its new location (Figure 3-47).

![](images/_page_105_Picture_0.jpeg)

Figure 3-47
Torn-off menu

Even after a menu has been torn off, it can still be accessed from the menu bar. The state of the torn-off menu must be reflected in its pull-down counterpart, and vice versa (Figure 3-48). A given menu can exist in torn-off form only once: if the user tears it off a second time, the first instance disappears.

![](images/_page_105_Picture_3.jpeg)

Figure 3-48
Torn-off menu also available in menu bar

Like document windows, torn-off menus can be dragged around the screen and closed with a close box. To avoid confusion, however, tear-off menus don't look exactly like document windows. Tear-off menus are always "in front" of all open document windows. If a single application can have more than one menu torn off at a time, the application must determine their order of precedence.