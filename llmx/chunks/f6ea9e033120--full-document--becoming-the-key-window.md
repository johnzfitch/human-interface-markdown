---
chunk_index: 4072
ref: "f6ea9e033120"
id: "f6ea9e033120ebad1b00aeaabe276a70f181719e67daa4a24364adbd8f7aa54f"
slug: "full-document--becoming-the-key-window"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1594, 1604]
token_estimate: 356
content_sha256: "2d01d43de69f054df71ab39b08da57739a1efa673e268f90a86c3e27cae22b2b"
compacted: false
heading_path: ["5 *Panels*","**Becoming the Key Window**"]
symbol: null
address: null
asset_path: null
---

## **Becoming the Key Window**

An ordinary panel should become the key window only if it accepts keystrokes (typing) or if it's used independently of any other windows. For example, the Find panel becomes the key window so that the user can type in the word to be found. But the tools palette in a graphics application should never become the key window because it's operated only by the mouse and it's always used in conjunction with a document window. On the other hand, the standard Info panel should become the key window because it contains information that's independent of the application's other windows. In other words, it's the center of the user's attention and thus should be the key window.

A panel that accepts keystrokes can delay becoming the key window until the user indicates a readiness to begin typing (such as by clicking in a text field), provided that both of the following are true:

- Text entry is not essential to using the panel.
- Users typically don't enter text when using it.

This is likely to be the case if most of the control devices in the panel are not text fields (they are buttons, selection lists, and so on) and if the choices that can be made by entering text can also be made in an alternative way (for example, by selecting items from a list). The Font panel is an example. This kind of panel should not show any selection until the user indicates a readiness to begin typing.