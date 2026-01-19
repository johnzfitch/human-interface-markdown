---
chunk_index: 3995
ref: "b2303e33dc9a"
id: "b2303e33dc9af9dc6dbd2a89dd07e8a954060024b1381090db1b22ddf00cb261"
slug: "full-document--reserved-keyboard-alternatives"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [835, 856]
token_estimate: 348
content_sha256: "77c324e9f0c42f88fdbb4471645e7473500a4e8ac791b00313c7a5cb4182916c"
compacted: false
heading_path: ["*Introduction*","**Choosing Keyboard Alternatives**","**Reserved Keyboard Alternatives**"]
symbol: null
address: null
asset_path: null
---

#### **Reserved Keyboard Alternatives**

Reserved keyboard alternatives must be used for the commands that follow, and cannot be used for any others. If your application implements the functionality that a command represents, it must provide both the command and the keyboard alternative.

For example, if your application opens files, it must have an Open command with Command-o as the keyboard alternative. If your application doesn't allow the user to open files, it won't have an Open command and must not use Command-o as a keyboard alternative.

| Keyboard Alternative | Command      | Menu          |
|----------------------|--------------|---------------|
| Command-?            | Help         | Info menu     |
| Command-a            | Select All   | Edit menu     |
| Command-c            | Copy         | Edit menu     |
| Command-h            | Hide         | main menu     |
| Command-n            | New          | Document menu |
| Command-o            | Open         | Document menu |
| Command-p            | Print        | main menu     |
| Command-q            | Quit         | main menu     |
| Command-s            | Save         | Document menu |
| Command-v            | Paste        | Edit menu     |
| Command-w            | Close Window | Windows menu  |
| Command-x            | Cut          | Edit menu     |
| Command-z            | Undo         | Edit menu     |