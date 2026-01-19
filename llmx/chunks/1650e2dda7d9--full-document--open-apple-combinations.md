---
chunk_index: 498
ref: "1650e2dda7d9"
id: "1650e2dda7d9bae6abc0faa06326b346d1754cb718cfda8b27196dcac777111c"
slug: "full-document--open-apple-combinations"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [537, 565]
token_estimate: 313
content_sha256: "7cb150e9ce4492234417a51e246c57c9d31542daceb3d3c28a8f13c04b007b21"
compacted: false
heading_path: ["Open-Apple combinations:"]
symbol: null
address: null
asset_path: null
---

# Open-Apple combinations:

| Character | Command |
|-----------|---------|
| P         | Print   |
| Q         | Quit    |
| S         | Save    |

Windowing applications reserve these additional commands (see: Commands)

| Character | Command |  |
|-----------|---------|--|
| z         | Undo    |  |
| X         | Cut     |  |
| С         | Сору    |  |
| V         | Paste   |  |

(Note that these keys are the first four on the bottom row on the standard U.S. keyboard. If you translate a program to a keyboard with a different layout, you should change the actual characters typed so that they remain the first four keys on the bottom row.)

- D Drag or move the currently active window
- G Grow or shrink (size) the currently active window
- M Mark a selection

THE KEYBOARD 39

Typing any of these combinations will place the accent, followed by a backspace character, in your file, so that the next character typed will be accented. Display the accent and the character linked by the solid-dash MouseText character ("S"). As the user cannot type a solid dash, there is no ambiguity.

Your program should accept only valid accented characters, throwing away the dead-key character if, for example, a person types OPEN-APPLE-^ followed by an X.