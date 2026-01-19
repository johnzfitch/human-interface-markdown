---
chunk_index: 3784
ref: "ea4fdd3be7a4"
id: "ea4fdd3be7a46d790530b8ea5895f7dcd94b0749c77896812e7fe7ba298468e9"
slug: "chunk-156--how-buttons-work"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_156.md"
kind: "markdown"
lines: [22, 25]
token_estimate: 408
content_sha256: "a818d0626141b7e56d4afaeeca78d1389a5fc44a94242675c45b34ad1d38b180"
compacted: false
heading_path: ["**Buttons**","**How Buttons Work**"]
symbol: null
address: null
asset_path: null
---

#### **How Buttons Work**  
The Application Kit provides two basic kinds of buttons: *one-state* (or *action*) buttons and *two-state* buttons. Action buttons perform a single task, such as scrolling a document forward or starting a search. A two-state button sets a single characteristic on or off, such as whether to restrict a search to whole words. Standard two-state buttons include switches and radio buttons. Some buttons also bring up lists, as described in the following section.  
All buttons respond to a click. Some also respond to being pressed. A button that responds to being pressed sends an instruction to the application as soon as the user pushes the mouse button down. Typically, it repeats the instruction at regular intervals-as long as the mouse button is held down and the cursor is kept over the button on-screen-for a continuous, iterative action. Users can drag away from the button and back again to stop and restart the action. A button that responds only to being clicked sends its instruction to the application when the user releases the mouse button, provided the cursor is over the button on-screen.  
Whether it responds to being clicked or to being pressed, a button changes its appearance as soon as the mouse button goes down. It retains its altered appearance while it's under the cursor and the mouse button remains down. When the user releases the mouse button, the button on-screen keeps its altered appearance long enough for its instruction to be carried out. Usually this is momentary (though it need not be), so users generally notice the button changing as soon as the click is over.