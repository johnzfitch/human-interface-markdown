---
chunk_index: 4180
ref: "f7ff8788e476"
id: "f7ff8788e4769be64925c4ed1d20942191bb2648d8c76fe9c66d224bffacbfe1"
slug: "full-document--controls-that-show-state"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2954, 2961]
token_estimate: 290
content_sha256: "80ebabee45be0cb767b8ff5e9b282f83e61dca2692e5bca3fb238414186abef6"
compacted: false
heading_path: ["7! *Controls*","**Controls that Show State**"]
symbol: null
address: null
asset_path: null
---

## **Controls that Show State**

Pop-up lists, selection lists, and two-state buttons are used to show state. (Menu commands should never be used to show state.) Sometimes a single control shows the state of a single option. Often, though, options are grouped. Such a group should have either a one-of-many relationship, where exactly one option is always selected, or an unrestricted relationship, where any number of options (or none at all) might be selected.

**Note:** A third relationship is currently possible only in selection lists: a relationship in which either no choice or one choice can be selected.

Controls that show state should be used strictly to show and set state, not to initiate actions. For example, although double-clicking an item in a selection list might cause an action to happen, the double-click is really a shortcut for selecting the item and then clicking a button. If setting state has visible consequences, such as causing the format of a document to change, then the consequences should merely be immediate feedback that the state has changed, and not a full action such as creating another document with the new format.