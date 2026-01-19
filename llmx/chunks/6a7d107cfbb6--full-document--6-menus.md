---
chunk_index: 4102
ref: "6a7d107cfbb6"
id: "6a7d107cfbb60f12953d3531ddf08eaf597ebc399b20bacfb3dd8e0346fe0464"
slug: "full-document--6-menus"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1948, 1962]
token_estimate: 335
content_sha256: "8ae7a3e7577d7f8313adc28f55e0c43a29643762428777c74972735011eff326"
compacted: false
heading_path: ["5 *Panels*","6 *Menus*"]
symbol: null
address: null
asset_path: null
---

## 6 *Menus*

=

Menus provide users a point of entry for all the functionality of an application, its obscure and common features alike. Because of this special role, they behave in a special way:

- All the visible menus for an application disappear when the user starts working in another application. They reappear when the user returns to the application. (Menus that weren't previously on-screen don't reappear.)
- Menus are segregated into two of the frontmost tiers of on-screen windows. They appear to float above everything else on-screen except attention panels and spring-loaded windows such as pop-up lists.
- Menus can't be miniaturized. They don't need to be, since they're small and can be easily retrieved after they've been closed.
- Menus are hierarchically arranged. Choosing a command in one menu can produce another menu with its own list of commands.

The first three of these points were discussed earlier in this manual. (See "The Active Application," "Window Order," and "Miniaturizing" in Chapter 4, "The Window Interface to Applications.")

Applications should make use of the menu system's hierarchy to arrange commands in distinct, functionally identifiable menus. A well-defined set of hierarchical menus aids users both in finding the commands they need and in understanding the structure of the application.