---
chunk_index: 4151
ref: "25a8de70a9e4"
id: "25a8de70a9e40c918374814403320e56440a87447442a6cb7a8601e49756a57b"
slug: "full-document--how-buttons-work"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2601, 2608]
token_estimate: 407
content_sha256: "cdc74b480265e1325d2954acba1c83a54a058edc4b85d44d9754fa4fc4199468"
compacted: false
heading_path: ["7! *Controls*","**Buttons**","**How Buttons Work**"]
symbol: null
address: null
asset_path: null
---

#### **How Buttons Work**

The Application Kit provides two basic kinds of buttons: *one-state* (or *action*) buttons and *two-state* buttons. Action buttons perform a single task, such as scrolling a document forward or starting a search. A two-state button sets a single characteristic on or off, such as whether to restrict a search to whole words. Standard two-state buttons include switches and radio buttons. Some buttons also bring up lists, as described in the following section.

All buttons respond to a click. Some also respond to being pressed. A button that responds to being pressed sends an instruction to the application as soon as the user pushes the mouse button down. Typically, it repeats the instruction at regular intervals-as long as the mouse button is held down and the cursor is kept over the button on-screen-for a continuous, iterative action. Users can drag away from the button and back again to stop and restart the action. A button that responds only to being clicked sends its instruction to the application when the user releases the mouse button, provided the cursor is over the button on-screen.

Whether it responds to being clicked or to being pressed, a button changes its appearance as soon as the mouse button goes down. It retains its altered appearance while it's under the cursor and the mouse button remains down. When the user releases the mouse button, the button on-screen keeps its altered appearance long enough for its instruction to be carried out. Usually this is momentary (though it need not be), so users generally notice the button changing as soon as the click is over.