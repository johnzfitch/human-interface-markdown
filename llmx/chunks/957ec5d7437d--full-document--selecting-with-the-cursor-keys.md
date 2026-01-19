---
chunk_index: 535
ref: "957ec5d7437d"
id: "957ec5d7437d6c693194b02ee45f11e6057861391c6e63461d431b13b180bbb8"
slug: "full-document--selecting-with-the-cursor-keys"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1291, 1300]
token_estimate: 374
content_sha256: "b401987d074d569421864079f7325d570963bcc5adb4ffe9b88462d6466c4b81"
compacted: false
heading_path: ["Making a Discontinuous Selection","Selecting with the Cursor Keys"]
symbol: null
address: null
asset_path: null
---

### Selecting with the Cursor Keys

The user can alternatively mark a selection using the cursor keys. To signal the system that a selection is about to be marked, the user presses Open-Apple-M. The current insertion-point then becomes the anchor of the selection, and the selection can be extended in any direction using the four cursor keys.

Pressing Open-Apple-M twice before using the cursor keys is equivalent to a mouse double-click; pressing Open-Apple-M three times is equivalent to a mouse triple-click. In the case of text, the anchor-point is always at the top-left point of the expanded insertion-point and the current cursor position is always at the bottom-right.

a selection, the user presses Solid-Apple-M as an equivalent of Open-Apple-click. There is no equivalent of Solid-Apple-click. Only provide Solid-Apple-M if it is really needed: One of the primary reasons for being able to extend a text selection in the mouse world is that the user needs to go to the scroll-bar to move any significant distance. The cursor-key user does not need to use the scroll bar. Reaching a window end will scroll the window's contents; pressing Open-Apple at the same time as a cursor key will move the cursor by an appropriately large chunk, such as one word horizontally or one page vertically.

Other than the method of signalling the beginning and end of a selection, selecting using the cursor keys follows the same general guidelines as selecting with a mouse. (Differences are noted.)