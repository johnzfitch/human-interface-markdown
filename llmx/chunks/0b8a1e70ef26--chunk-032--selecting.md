---
chunk_index: 1074
ref: "0b8a1e70ef26"
id: "0b8a1e70ef26e535d4981b8b4cdbdb6e48408bcea5a5c8e29693a3962df88655"
slug: "chunk-032--selecting"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/chunks/chunk_032.md"
kind: "markdown"
lines: [20, 26]
token_estimate: 403
content_sha256: "0b577372d056e63a8e1252fdc1a252ec1deb24602cc52ee5685d61bb31c36413"
compacted: false
heading_path: ["Mouse actions","**Pointers**","Selecting"]
symbol: null
address: null
asset_path: null
---

#### Selecting  
Before performing an operation on an object (or several objects), the user must select it to distinguish it from other objects. This selection is typically done by clicking on an object, or by dragging through a range of objects or a portion of text.  
Selecting the object of an operation before identifying the operation itself is a fundamental characteristic of the Apple human interface. This is sometimes called the "noun-verb" paradigm.  
There is always a visual cue to show that something has been selected. For example, text and icons usually appear in inverse video when selected. The important thing is that there should always be immediate feedback, so that the user knows that the mouse button (click or drag) had an effect.  
Separating the selection and action functions gives the user considerable power and flexibility. The paradigm matches the syntax that we normally use in ordinary non-computer actions: "Hey, you..." (selection) "...do this" (choose an action).  
Selecting before committing to an action means that the user can explore and change direction without executing inappropriate or time-consuming routines. Simply selecting an object—for example a document—doesn't alter the contents of this object. Making a selection needn't commit the user to anything; there is not a penalty for making an incorrect selection.  
In most cases, the user can undo any selection by making any other selection. When this is not possible, either use an alert box to warn the user, or implement cancel or undo commands to let the user back gracefully out of undesired situations.