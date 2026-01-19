---
chunk_index: 4100
ref: "032ccae0841b"
id: "032ccae0841bbb957af14726b6f9141b599d58a1ed7cc8d94b825fc937b69535"
slug: "full-document--implementing-the-quit-panel"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1914, 1939]
token_estimate: 461
content_sha256: "44fdd2e060519a989ed4252577bad7c6a11642642a4a9af7405fde852725c155"
compacted: false
heading_path: ["5 *Panels*","**Implementing the Quit Panel**"]
symbol: null
address: null
asset_path: null
---

## **Implementing the Quit Panel**

When the user tries to quit an application that has unsaved or uncompleted work, the application should bring up a Quit panel. For example, if the user has edited a document and not saved the changes, or if the application is still computing (for example, a command is executing in a UNIX shell), a Quit panel should appear. In both cases, one or more of the application's windows should have a broken close button, as described in "Using the Close Button" in Chapter 4.

The Quit panel should be an attention panel that has the following buttons:

- A Cancel button (only when the panel is brought up as the result of choosing the application's Quit command)
- A Quit Anyway button
- A Review Unsaved button (only for document-oriented applications) that cycles through unsaved documents, letting users decide which ones to save before quitting.

The buttons are arranged as follows:

Cancel Quit Anyway Review Unsaved

An application could also add a Save All button that saves every unsaved document, exactly as the Save All command does.

**Important:** Because applications can't cancellogouts and poweroffs, the Quit panel shouldn't have a Cancel button when it's brought up as the result of a logout or poweroff:

Quit Anyway Review Unsaved

Review Unsaved is the default button. It brings up a Review Unsaved panel for each unsaved document. This panel is essentially the same as the Close panel described above, though with a different name to reflect the different manner in which it's invoked.

The Cancel button in the Review Unsaved panel cancels the review process and returns the user to the Quit panel. Once the user has finished cycling through all the documents (without clicking Cancel), the application should quit.

Note: Do *not* bring up a Quit panel unless work is about to be lost.