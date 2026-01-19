---
chunk_index: 4004
ref: "2e55989ffca1"
id: "2e55989ffca115777aa1e283441a331d1ef00468d4f6ba2126401f317d2ebaf4"
slug: "full-document--the-first-click-in-a-window"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [955, 963]
token_estimate: 290
content_sha256: "00ea959b5509780ecdcfa08e0a7879f3cf84e8a74aa699fad66baf50a6d1e35d"
compacted: false
heading_path: ["*Introduction*","**The First Click in a Window**"]
symbol: null
address: null
asset_path: null
---

## **The First Click in a Window**

Clicking can be used not only to operate an object, but also simply to bring a window forward. When the user clicks in a window that isn't already in front, a question arises concerning intent: Did the user intend the click just to bring the window forward, or was it also intended to do some work within the window? This question is addressed by the following guidelines:

- If the user chooses a particular control-for example, by clicking a button or clicking in a scroller-the click should not only bring the window forward, but should also operate the control. Since controls are small, it's reasonable to assume that the user chose to click the control, not just the window.
- If the click is just generally within the content area of the window, the click will bring the window forward but shouldn't have any result within the window. Specifically, it shouldn't alter the current selection.

However, if the user chooses to double-click within the content area of the window, the normal double-click action should be performed. Double-clicking on a word should select the word whether the window is in front or not.