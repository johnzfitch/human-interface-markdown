---
chunk_index: 3972
ref: "2cd8ae8250d1"
id: "2cd8ae8250d1da9554ed9470d9c6c8a0554a566324e59ca3ba14301ee9218625"
slug: "full-document--programming-note-the-keyboard"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [637, 648]
token_estimate: 290
content_sha256: "99b591631ac8abeea1eb9a8445afc6166bbca74b6b039cf75b1fddb5920b7889"
compacted: false
heading_path: ["*Introduction*","**The Keyboard**","**Modifier Keys**","**Programming Note: The Keyboard**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: The Keyboard**

For most applications, keyboard input is handled automatically. Text entry and display are handled by the Application Kit Text object, and keyboard alternatives are automatically converted into clicks on their associated control. All you have to do is choose the keyboard alternatives (as discussed later in this chapter) and specify them in Interface Builder"'.

You'll need to handle keyboard input if your application doesn't use the Text object for its text entry.

Keyboard alternatives consist of a single keystroke, modified by the Command key (and possibly another modifier key). The Command key is required so that keystrokes that make something happen (give commands) are clearly separated from those that enter data (cause typing to appear).

Keyboard alternatives are most often used for menu commands, although they're permitted in a panel's buttons and pull-down lists, as well.

Although keyboard alternatives are tied to a graphic representation, they don't require the representation to be on-screen. Keyboard alternatives for menu commands and panel buttons work even if the menu or panel is hidden.