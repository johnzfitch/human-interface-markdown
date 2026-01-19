---
chunk_index: 3999
ref: "73bf6ca8663f"
id: "73bf6ca8663f59870e56c864554d85e9086cf257cf765e5951a30131a996036c"
slug: "full-document--choosing-the-character"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [909, 916]
token_estimate: 262
content_sha256: "2f2518379c534e29a898abf1fc1e9249e1752ff7ce35568bdc1d9ca0003db1f7"
compacted: false
heading_path: ["*Introduction*","**Creating Application-Specific Keyboard Alternatives**","**Choosing the Character**"]
symbol: null
address: null
asset_path: null
---

#### **Choosing the Character**

Any character except period (.) and space can be used in a keyboard alternative. If the character is a letter, it can be either uppercase or lowercase, although lowercase characters are preferred because they don't require the user to press two modifier keys (Shift and Command) at once.

When choosing the character for a keyboard alternative, try to make it mnemonic. If possible, it should be the first letter of the command it performs. If it's closely related to a command that already has a keyboard alternative, then you might want to choose a character physically near the existing one.

For example, the Find command's keyboard alternative is Command-f, taken from the first letter of the command. The Find command has two related commands: Find Next and Find Previous. The Find Next command's keyboard alternative (Command-g) was chosen because it's just to the right of the Find command's keyboard alternative. Similarly, the Find Previous command's keyboard alternative (Command-d) is just to the left.