---
chunk_index: 3605
ref: "af5fef663d88"
id: "af5fef663d880957b899f2d6fba8dfbec2c6595519f03f359bfc0be61f98f0bf"
slug: "chunk-034--programming-note-the-keyboard"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_034.md"
kind: "markdown"
lines: [15, 20]
token_estimate: 291
content_sha256: "fdd369134736db12459cb9bb2f2a92d9854f87965a95c82599dcc6677b0aedda"
compacted: false
heading_path: ["**Modifier Keys**","**Keyboard Alternatives**","**Programming Note: The Keyboard**"]
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