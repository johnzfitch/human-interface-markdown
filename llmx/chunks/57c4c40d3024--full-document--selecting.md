---
chunk_index: 1891
ref: "57c4c40d3024"
id: "57c4c40d3024605704cdfceb5dafd70cc9dfb1cc0bd9a668712aeb06ec70d2b7"
slug: "full-document--selecting"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [881, 892]
token_estimate: 408
content_sha256: "b3a26b7ad164aedd9f64c0e7da3abaee5c462ce8e514eae90394aeecc2e4f060"
compacted: false
heading_path: ["**Human-computer interaction**","**Pointing**","Mouse actions","Selecting"]
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