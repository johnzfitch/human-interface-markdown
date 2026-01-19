---
chunk_index: 216
ref: "58757738f55f"
id: "58757738f55f6c8f30ba37bb14c24c660de5515e9d4a17572007795130489eab"
slug: "full-document--apple-ii-series"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [669, 686]
token_estimate: 726
content_sha256: "d62a93b2f3e5a12c31815856b2a97eb48b4be6370ae717957ad8061ff398a55c"
compacted: false
heading_path: ["The (Pascal) Solid-box Cursor","The New Insert/Delete Cursor","Apple II Series"]
symbol: null
address: null
asset_path: null
---

#### Apple II Series

| Keystroke            | Editing Operation                                                                                                                                                    |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Necessary:           |                                                                                                                                                                      |
| LEFT-ARROW           | moves cursor left within input line.                                                                                                                                 |
| RIGHT-ARROW          | moves cursor right within input line.                                                                                                                                |
| CTRL-D               | deletes character to the left of the cursor - Apple II & II+.                                                                                                        |
| DELETE               | deletes character to the left of the cursor - Apple IIe.                                                                                                             |
| RETURN               | accepts entire response, regardless of current cursor position.                                                                                                      |
| CTRL-B               | has no effect on a display with a single input. On a multiple- input display (see next section), CTRL-B accepts entire response, moving user back to previous input. |
| Useful if implementa | tion language allows sufficient speed:                                                                                                                               |
| CTRL-X               | deletes all characters on the input line.                                                                                                                            |
| CTRL-Y               | deletes all chars from present cursor position to end of line.                                                                                                       |
| CTRL-R               | recalls display of default response. If no default, then it acts the same as $\mathtt{CTRL-X}$ .                                                                     |
| Optional:            |                                                                                                                                                                      |
| CTRL-P               | Prints the contents of the display on the default printer.                                                                                                           |