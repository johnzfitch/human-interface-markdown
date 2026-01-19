---
chunk_index: 2983
ref: "d874ec5166b6"
id: "d874ec5166b66a46ecae652f5b3dc9dc5b7b98f3002d00db262a5f907f8d626b"
slug: "full-document--windows"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [5910, 5928]
token_estimate: 521
content_sha256: "98cec9dc0446b24930ce7a113660f741487253e1374e15f2739a3c59649e01db"
compacted: false
heading_path: ["Windows"]
symbol: null
address: null
asset_path: null
---

# Windows

- Do the standard window size and position take into account the dimensions of the screen?
- Is the standard state of a window best suited to working on the document (such as no wider than the page width), and not necessarily as large as the full screen?
- Does your application make sense when it chooses to open a window in either the standard or the user-selected state?
- Can each sizable window be made as large as the smaller of either the maximum document size or the maximum size of the displays, including multiple monitor displays?
- Is the default position of a window contained on a single screen?
- Is each additional window opened below and to the right of its predecessor?
- If a user drags a window from one monitor to another monitor, does your application open subsequent windows on the second monitor?
- Do you use the lowercase letters "untitled" in a new window title? Do you avoid using additional punctuation in window titles? Do you avoid using blank titles? Do you avoid adding a number to the title of the first new window?
- Before closing a window, do you check to see if the user has changed its size or position? Do you save window positions, and then reopen windows in the size and position in which the user left them?
- Before reopening a window, do you make sure that the size and position are reasonable for the user's current monitor or monitors, which may not be the same as the monitor on which the document was last open?

**354** Icons

- When zooming from the user state to the standard state, do you check if the size of the standard state would fit completely on the screen without moving the upper-left corner? If so, is the upper-left corner anchored? If not, is the window moved to an appropriate default location?
- When a window becomes inactive, do the close box, zoom box, size box, stripes in the title bar, and scroll bars disappear?
- Do you avoid displaying the selection in an inactive window? (You can use a secondary selection technique such as an outline to indicate where the selection is in an inactive window.)