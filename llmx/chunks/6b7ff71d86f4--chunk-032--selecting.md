---
chunk_index: 1646
ref: "6b7ff71d86f4"
id: "6b7ff71d86f40e1d8fb0d07cc512e9ef8860ecc8ddbe12da4a77298e8654e16c"
slug: "chunk-032--selecting"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_032.md"
kind: "markdown"
lines: [21, 26]
token_estimate: 409
content_sha256: "6c0b1c8c850b9435c5bc74cdd458bd04f62afd3da8068c729008315d2f9727aa"
compacted: false
heading_path: ["Mouse actions","**Pointers**","Selecting"]
symbol: null
address: null
asset_path: null
---

#### Selecting  
Before performing an operation on an object (or several objects), the user must select it to distinguish it from other objects. This selection is typically done by clicking on an object, or by dragging through a range of objects or a portion of text.  
Selecting the object of an operation before identifying the operation itself is a fundamental characteristic of the Apple human interface, and has been referred to earlier as the "noun-verb" paradigm. The paradigm matches the syntax that we normally use in ordinary noncomputer actions: "Hey, you..." (selection) "...do this" (choose an action).  
There is always a visual cue to show that something has been selected. For example, text and icons usually appear in inverse video when selected. The important thing is that there should always be immediate feedback, so the user knows that clicking or <sup>i</sup> dragging the mouse had an effect.  
Separating the selection and action functions gives the user considerable power and flexibility. Selecting before committing to an action means that the user can explore land change direction without executing inappropriate or time-consuming routines. ISimply selecting an object—for example, <sup>a</sup> document—doesn't alter the contents of [this object. Making a selection needn't commit the user to anything; there is no |penalty for making an incorrect selection.  
In most cases, the user can undo any selection by making any other selection. When is is not possible, either use an alert box to warn the user, or implement cancel or indo commands to let the user gracefully back out of undesired situations.