---
chunk_index: 4092
ref: "3edbf22f8ae9"
id: "3edbf22f8ae9571eb66223003533becd8a19f7b161cc0e0f4ab99cc18888bb23"
slug: "full-document--implementing-the-find-panel"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1823, 1842]
token_estimate: 464
content_sha256: "b182be0434ad142a28826cd4620a342e983f0d680b531e883460643c191a43bf"
compacted: false
heading_path: ["5 *Panels*","**Implementing the Find Panel**"]
symbol: null
address: null
asset_path: null
---

## **Implementing the Find Panel**

![](images/_page_104_Picture_1.jpeg)

This ordinary panel should have at least a text field to enter the search string and a button to find the next instance of the string. It's also good to have a button for finding the previous instance of the string.

**Note:** Although we recommend that buttons have verbs as titles, it isn't appropriate in the panel above, for two reasons. First, changing the titles to Find Previous and Find Next hides the real difference between the buttons; it's easy to miss the second word in a button. Second, since Find is already mentioned in the panel twice (and no other verb is), it's redundant to put Find in the button titles. See "Choosing the Button's Image or Label" in Chapter 7 for more information on naming buttons.

Many Find panels have more controls than the one shown above, such as the following:

- A check box that lets the user choose whether capitalization matters (by default, it shouldn't)
- A check box to choose whether partial words should be considered matches (by default, they should)
- A Replace With text field (and related buttons-see Edit for an example) so that the user can replace the selected string
- Radio buttons that determine the scope of global searches or replacements (by default, the scope should be global rather than just the selected region)
- Options for finding objects other than strings (such as paragraph characteristics)

Although the Find panel usually stays up until the user explicitly closes it, it's common to dismiss the panel early in one case. This case is described in "Determining the Action that Is Performed" in Chapter 3, "User Actions: The Keyboard and Mouse."

The Find Panel menu command brings up this panel. The Find Next and Find Previous commands correspond to its two buttons. (See "The Find Menu" in Chapter 6.)