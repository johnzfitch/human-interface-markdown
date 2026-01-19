---
chunk_index: 218
ref: "f6ad7a28a5a6"
id: "f6ad7a28a5a633f9d24f8c2ae4de082164455d3a13d99a2f5960251ceecbd853"
slug: "full-document--apple-iii-series"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [707, 726]
token_estimate: 1399
content_sha256: "52638e6506b9feb3eb11c7a71fa2ca952d75e086c4b3f4a1ac757c231d12f7f0"
compacted: false
heading_path: ["The (Pascal) Solid-box Cursor","Apple III Series"]
symbol: null
address: null
asset_path: null
---

## Apple III Series

| Keystroke                                     | Editing Operation                                                                                                                                                                                                                                                                   |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Necessary:                                    |                                                                                                                                                                                                                                                                                     |
| LEFT-ARROW                                    | moves cursor left within input line.                                                                                                                                                                                                                                                |
| R I G H T – A R R O W                         | moves cursor right within input line.                                                                                                                                                                                                                                               |
| Either:                                       |                                                                                                                                                                                                                                                                                     |
| CTRL-SPACE,<br>CTRL-LEFT-<br>ARROW, or DELETE | will delete the character to the left of the cursor.                                                                                                                                                                                                                                |
| Either:                                       |                                                                                                                                                                                                                                                                                     |
| CTRL-RIGHT-<br>ARROW Or<br>CTRL-DELETE        | will delete the character to the right of the cursor.                                                                                                                                                                                                                               |
| RETURN                                        | accepts entire response, regardless of current cursor position.                                                                                                                                                                                                                     |
| CTRL-B                                        | has no effect on a display with a single input. On a multiple-input display (see next section), CTRL-RETURN accepts entire response, moving user back to previous input. Programs often use                                                                                         |
| CTRL-RETURN                                   | in addition to CTRL-B for accept and move back: CTRL-RETURN is indistinguishable from CTRL-M, or CTRL-whatever-character-your-user-has-defined-to-be-in-M's-standard-keyboard-position. Please take this potential risk into account before enabling CTRL-RETURN as well as CTRL-B. |
| CTRL-E                                        | deletes (erases) all characters on the input line.                                                                                                                                                                                                                                  |
| CTRL-K                                        | deletes all chars from present cursor position to end of line.                                                                                                                                                                                                                      |
| CTRL-U                                        | (Un-do) recalls display of default response. If no default, then it acts the same as $\mathtt{CTRL-E}.$                                                                                                                                                                             |
| Optional:                                     |                                                                                                                                                                                                                                                                                     |
| CTRL-P                                        | Prints the contents of the display on the default printer.                                                                                                                                                                                                                          |