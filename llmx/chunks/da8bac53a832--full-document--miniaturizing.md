---
chunk_index: 4035
ref: "da8bac53a832"
id: "da8bac53a832f73bf3b375a57689be280e48578f514dbba61a3698d1fc1fb8e7"
slug: "full-document--miniaturizing"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1250, 1263]
token_estimate: 356
content_sha256: "713159c5b33b428c5b471aa473a829a42c2a6015da1aa43948934d0492eb042c"
compacted: false
heading_path: ["The Window Interface to Applications","**Miniaturizing**"]
symbol: null
address: null
asset_path: null
---

## **Miniaturizing**

Miniaturizing a window removes it from the screen without destroying it or its contents. From the user's point of view, the window is transformed into a miniwindow. Double-clicking the mini window reverses the miniaturization.

Most standard windows and some panels have a miniaturize button. Windows that have a miniaturize button can be miniaturized using either the button or the standard Miniaturize Window menu command. A group of windows representing a single document can be miniaturized into a single miniwindow, as described under "The Document Menu" in Chapter 6.

Users can't work in a miniaturized window, but programs can continue to alter the window's display. For example, if you begin compiling a program in a Terminal window, and then miniaturize the window, you'll see any error messages written by the compiler when you return the window to the screen. '

Miniaturizing differs from closing in a number of ways:

- Miniaturizing preserves the window as it was last seen on-screen. A window that's closed can't necessarily be retrieved in the same state.
- Miniaturizing a window leaves behind a mini window so that it can be brought back to the screen. Closing a window doesn't provide the user with a way of getting it back.
- Miniaturizing a window that displays a file won't close the file or change the way it's displayed. Closing a window usually closes the file it displays.