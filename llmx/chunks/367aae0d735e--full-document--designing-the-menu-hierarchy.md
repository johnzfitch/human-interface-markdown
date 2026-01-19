---
chunk_index: 4114
ref: "367aae0d735e"
id: "367aae0d735ecaa773afbde691ceb3d20eac84e89de476ace14e0cd3b38f7d39"
slug: "full-document--designing-the-menu-hierarchy"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2075, 2086]
token_estimate: 316
content_sha256: "1b278c14aa9dd777f5a15ac04bf1201c2cd5cb3fbbb878dd7c8adf41ac816b2e"
compacted: false
heading_path: ["5 *Panels*","**Designing the Menu Hierarchy**"]
symbol: null
address: null
asset_path: null
---

## **Designing the Menu Hierarchy**

When designing your application's menu hierarchy, you should start with the standard menus described later in this chapter-in particular, the main menu. Having standard menus, as much as possible, is one of the easiest and best ways to ensure consistency between applications.

Since menus need to be easily accessible to the user, you should try to keep your application's menu hierarchy as shallow as possible. In general, a menu should be located no more than two steps away from the main menu. It's even better to have menus no more than one step away, as long as they don't grow too long or confusing as a result.

![](images/_page_118_Picture_10.jpeg)

A menu should never have fewer than two commands unless it grows and shrinks dynamically and happens to shrink to fewer than two. If an application has a menu with only one item in it, that item should be bumped up one level and replace the command that brings up the menu. (A specific example of this is discussed later in this chapter under "The Info Menu.")

A menu can have as many submenus as it has commands, although only one at a time can be attached to the menu. A menu should appear only once in the menu hierarchy-it should not be the submenu of two menus.