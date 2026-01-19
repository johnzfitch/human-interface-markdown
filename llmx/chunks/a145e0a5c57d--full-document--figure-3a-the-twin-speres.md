---
chunk_index: 524
ref: "a145e0a5c57d"
id: "a145e0a5c57df465f07371e8abf9a3db496670f439ab146703685b9a043f2b1b"
slug: "full-document--figure-3a-the-twin-speres"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1134, 1156]
token_estimate: 555
content_sha256: "d6602a6693b47e61104b41aec212e4afba60779fc5c44db30ba62c4672a7df6d"
compacted: false
heading_path: ["Figure 3A. The Twin Speres"]
symbol: null
address: null
asset_path: null
---

# Figure 3A. The Twin Speres

Conceptually, the Keyboard and Mouse interfaces exist as overlapping spheres, with many operations, such as typing text, in common. They differ in how the non-mouse user performs the various pointing-and-choosing operations:

- Choosing from a menu: pressing Escape takes the user to the menu, the cursor keys moves around the menu, Return accepts the current item, and Escape cancels. See: "The menu bar".

1/15/85 Tognazzini

/INTF/STRUC

THE KEYBOARD MOUSE

67

- Moving and sizing a window: Open-Apple-D for drag redefines the cursor keys to move the window; Open-Apple-G for grow redefines the cursor keys to grow or shrink the window. See: "Moving a Window" and "Changing the size of a Window".
- Selecting text: Open-Apple-M for mark begins a text-selection mode. Moving the cursor keys marks the text, Return accepts, Escape cancels. See: "Selecting Text".
- Clicking on controls: Solid-Apple, by itself, acts as a mouse button to click on buttons, check boxes, and radio buttons. See: "Controls"
- Moving the insertion point: Pressing the cursor keys moves the insertion point. See: "Selecting".

As much keyboard support as is practical has been installed within the various mouse toolkits; where you must provide your own, follow the direction and philosophy of these guidelines and the toolkits themselves. When using a toolkit-based application, the keyboard user can directly emulate a mouse by holding down the Open-Apple key and pressing, then releasing Solid-Apple. The cursor keys then affect the mouse cursor so the user can move around the display, using Solid-Apple as the mouse button to click, press, or drag. When the Open-Apple key is released, mouse emulation is terminated.

The mouseless mouse is included as a safety net should a developer fail to discover in testing that there is a necessary feature that the keyboard user cannot get to without a mouse. It is also allows for rather flashy live demonstrations of your software's independence of the mouse. It is not intended as a substitute for the proper design of a keyboard-only interface: it was designed for ease of learning rather than ease of use, and to lower memory and documentation requirements.