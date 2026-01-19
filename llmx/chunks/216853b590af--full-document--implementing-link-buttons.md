---
chunk_index: 4162
ref: "216853b590af"
id: "216853b590af77fad6b4b83a12da602503e1df70b2b8e0c1228420de9cec5bb0"
slug: "full-document--implementing-link-buttons"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2720, 2727]
token_estimate: 258
content_sha256: "86c48dc7aecdf50da19687cf52477de4175a10dc65cbde3bfd69a34cdd73627f"
compacted: false
heading_path: ["7! *Controls*","**Implementing Link Buttons**"]
symbol: null
address: null
asset_path: null
---

## **Implementing Link Buttons**

Link buttons are different from most buttons because they're usually created by the user, instead of built into the application. Because link buttons often appear in custom content areas-areas that can be unique to each application that implements link buttons-link buttons require a little more support from the application than do other kinds of buttons. When implementing link buttons, you should be careful that they act in the following way:

- Clicking a link button highlights it briefly and brings up the document containing the information that the link refers to. An unmodified click should never select the link button.
- Shift-clicking a link button selects it.
- If the user presses the mouse button while the cursor is over the link button and then drags away without releasing the mouse button, the button should lose its highlight. However, if the user then drags back over the link button while still keeping the mouse button down, the link button should become highlighted again.