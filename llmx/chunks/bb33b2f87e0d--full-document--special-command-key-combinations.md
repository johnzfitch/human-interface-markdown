---
chunk_index: 3993
ref: "bb33b2f87e0d"
id: "bb33b2f87e0d6b8bb6af36939391786e86b604239fe2fd8bc0f1db1c149a07c0"
slug: "full-document--special-command-key-combinations"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [812, 828]
token_estimate: 580
content_sha256: "16c673ba148a4a10e5dbf465b8896163783d36ff3e6ef60a5dbc91eab1036587"
compacted: false
heading_path: ["*Introduction*","**Special Command-Key Combinations**"]
symbol: null
address: null
asset_path: null
---

## **Special Command-Key Combinations**

A handful of Command-key combinations produce special effects. Some playa particular role in the user interface. Others, in effect, give commands to the computer itself, rather than to just one application. They can't be used for other functions than those listed below.

- Command-. (period) should let users abort the current operation in the active application. Although the Application Kit has code to support Command-., it isn't automatic. An application must ask for this functionality
- Command-space should be used for file name completion. In contexts where it's appropriate for the user to type a file name (such as in an Open panel), Command-space displays as many characters as match all possible file names in the directory. If the user first types enough characters to identify a particular file and then presses the space bar with the Command key down, the remaining characters of the file name are filled in. (In many applications, the Esc key also performs file name completion.)
- On keyboards that have no Caps Lock key, Command-Shift is the equivalent of Caps Lock (but only if the Shift key is released before another key is pressed).
- Command-Return is the same as Enter.
- Command-volume down turns the speaker off and on. (Volume down is a system control key on NeXT keyboards.)

- Command-Left Alternate--, produced by holding the Command key and the leftmost Alternate key and pressing the - key, generates an NMI (nonmaskable interrupt) on systems that have only one Command key. An NMI brings up the NMI mini-monitor window.
- Command-Command-- generates an NMI on systems that have two Command keys.
- Command--, produced with just the right Command key for keyboards that have two Command keys, displays a panel that gives the user the option of restarting the computer, turning the power off, or canceling the command.
- Command-Alternate-\*, produced by pressing the Command and Alternate keys at the lower left of the keyboard in conjunction with the \* key on the numeric keypad, performs a reset to reboot the machine. The reset is immediate: No panel or monitor gives the user the option of canceling the instruction.

**Note:** These Command-key combinations aren't keyboard alternatives, since they don't correspond to anyon-screen object.