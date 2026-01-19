---
chunk_index: 3628
ref: "1a995cd3a5a2"
id: "1a995cd3a5a243e087c5daf3dc1a97ef5dd6466d076bd9e4bb5373b18998c25f"
slug: "chunk-046--reserved-keyboard-alternatives"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_046.md"
kind: "markdown"
lines: [4, 21]
token_estimate: 349
content_sha256: "6766092bbb3c5f143359b65e57df6b4e023f875eb199ae8aeb47adf53fb48ecd"
compacted: false
heading_path: ["**Reserved Keyboard Alternatives**"]
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