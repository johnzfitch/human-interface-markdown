---
chunk_index: 4081
ref: "8635200fb638"
id: "8635200fb638781cc42d043b93b9333e015014ac28134fdafbea66eb078f1807"
slug: "full-document--implementing-attention-panels"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1664, 1673]
token_estimate: 384
content_sha256: "d6be9e9c178fa355d487e67a8e4d4e5d88a7b0bd66cf2cf03fca301a1f9729ec"
compacted: false
heading_path: ["5 *Panels*","**Implementing Attention Panels**"]
symbol: null
address: null
asset_path: null
---

## **Implementing Attention Panels**

Attention panels are appropriate in only a limited number of situations. Because they create a mode that severely limits the user's freedom of, action, their use should be restricted as much as possible. A panel can be made an attention panel when:

- It gives the user information about the current context. Such panels usually warn of an error, of a potentially dangerous or unexpected result of the user's current course of action, or of a condition that makes it impossible to carry out a requested action. But they may also simply supply information the user will need to proceed intelligently with the application.
- It interrupts an action to give the user an opportunity to take corrective steps-as, for example, the panel that interrupts the Quit command to let users save altered files before the application terminates.
- It clarifies or completes a user action-as, for example, the panel that completes the Save As and Save To menu commands. (In this case, the menu command must have three dots after its name-for example, "Save As ... ". This is discussed under "Commands that Bring Up Panels," in Chapter 6, "Menus.")

Attention panels that interrupt or complete an action must have a Cancel button. The Cancel button gives the user the option of canceling the action, in which case it should be as if the user had never initiated the action in the first place. Panels that inform or warn should, if possible, let the user choose what to do in response to the information they convey.