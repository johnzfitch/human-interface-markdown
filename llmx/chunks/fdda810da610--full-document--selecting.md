---
chunk_index: 1411
ref: "fdda810da610"
id: "fdda810da61035ef1bb4e62b76a06526f3238d95b4f0a5d53dcf78bbbedda8c1"
slug: "full-document--selecting"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1657, 1671]
token_estimate: 386
content_sha256: "476361bb8a796a7856aceac8621b8fa5ed955352d1ce1e4bf9a0ac1d6e91e315"
compacted: false
heading_path: ["Selecting"]
symbol: null
address: null
asset_path: null
---

# Selecting

Before performing an operation on an object (or several objects), the user must select it, usually by clicking on it, to distinguish it from other objects. Selecting the thing to be operated on before identifying the operation itself is a fundamental characteristic of the Apple human interface. The pattern is usually something like this:

- 1. The user selects an object (a noun, the thing to be operated on).
- 2. The user chooses an operation (a verb, the thing to be done).

This is sometimes called the "noun-verb paradigm" or "Hey, you—do this!"

There is always a visual cue to show that something has been selected. For example, text and icons in a monochrome environment usually appear in inverse video when selected. In some situations, other forms of highlighting may be more appropriate. The important thing is that there should always be immediate feedback, so that the user knows that the click had an effect.

Selecting an object never alters the object itself. Making a selection shouldn't commit the user to anything; there should never be a penalty for making an incorrect selection. The user can undo any selection by making any other selection.

How something is selected depends on what it is. Although there are many ways to select objects, they fall into easily recognizable groups. Users get used to selecting objects in a certain way, and applications that use these methods are easier to learn. Some of these methods apply to every type of application, and some only to particular types of applications.