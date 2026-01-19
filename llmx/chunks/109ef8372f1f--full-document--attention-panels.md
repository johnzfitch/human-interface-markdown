---
chunk_index: 4066
ref: "109ef8372f1f"
id: "109ef8372f1f5459a3508832bcc322ce3a950f24cbbd398374c1d76f03af5587"
slug: "full-document--attention-panels"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1552, 1573]
token_estimate: 452
content_sha256: "1c595c6447b37342650cb2770112ce9c10d6ba144a9e6ac1db7083276df54f46"
compacted: false
heading_path: ["5 *Panels*","**Attention Panels**"]
symbol: null
address: null
asset_path: null
---

## **Attention Panels**

An attention panel demands attention from users by denying them the ability to work in any other window of the active application. Until it's explicitly dismissed, the panel limits what the user can do within the application to just rearranging windows. Nothing else-title bar buttons, text entry, miniwindows, or controls in other panels-will work. The only menu commands that work are those that can affect the panel itself-for example, Cut, Copy, and Paste, if the panel includes a text field.

It's possible to activate another application while an attention panel is on-screen, but when the user returns to the previous application, the mode created by the attention panel is still in effect.

An attention panel differs from ordinary panels in the following ways:

- It has an empty title bar.
- It's closed by one or more buttons in its content area, not by a button in the title bar.
- It stays on-screen-even when the application isn't active-until dismissed by the user.
- It's the key window whenever the application is active.
- It's isolated in a tier above everything on the screen except spring-loaded windows such as pop-up lists.

Attention panels come up centered in the upper part of the screen, so the user can't overlook them. (The user can move them out of the way, though.)

Because an attention panel sets an exclusive mode for itself, in effect disabling the rest of the application, it must be unmistakable and immediately apparent to the user. Some of the features that distinguish attention panels from other windows are illustrated below.

![](images/_page_89_Picture_11.jpeg)

Attention panels are dismissed from the screen as soon as the user takes the required action, which can be as simple as typing Return. When dismissed, the panel's mode ends.