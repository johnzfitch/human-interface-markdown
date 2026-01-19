---
chunk_index: 4003
ref: "8bd40eed907d"
id: "8bd40eed907dec48810a151dec4203c4347de276f8715182a05ec8d1f7d184e3"
slug: "full-document--reacting-to-clicking"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [946, 954]
token_estimate: 391
content_sha256: "919424ab4f9b0cb2a790f29a79d49cdb104228be223ed7cec49b5583bdf3acad"
compacted: false
heading_path: ["*Introduction*","**Reacting to Clicking**"]
symbol: null
address: null
asset_path: null
---

## **Reacting to Clicking**

When the user clicks an object on-screen, the object should provide immediate graphic feedback to the user when the mouse button goes down. However, depending on the intent of the click, the object may wait for the mouse button to go back up before doing anything more:

- If the click is intended to initiate a targeted action or choose a tool, then in general the object should act when the mouse button goes up. This gives users an opportunity to change their minds. If they move the cursor away from the object before releasing the button, the action is canceled. Suppose, for example, that a user presses the mouse button while the cursor points to the Cut command in the Edit menu. The command is highlighted, but nothing is cut until the mouse button is released. If the user moves the cursor outside the menu before releasing the mouse button, the command won't be carried out.
- If the click is intended to manipulate the object itself, the object should react immediately when the mouse button goes down. For example, when a window is clicked, it comes to the front of the screen without waiting for the mouse button to go up. Similarly, when editing text, the user is committed to a new selection as soon as the mouse button is pressed.

Note: You can implement multiple-clicks so that they act when the mouse button is pressed the second (or third) time, instead of waiting for the mouse button to go back up (as is usual for a single click). This implementation can help improve the perceived speed of your application.