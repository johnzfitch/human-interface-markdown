---
chunk_index: 4140
ref: "b6f1d85c960e"
id: "b6f1d85c960edc415db3f1bb7dcde490181add6d2db1710c5753fdaa6c6de5e8"
slug: "full-document--the-font-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2422, 2466]
token_estimate: 1186
content_sha256: "a03b6263fc8bff14104edbff9859eb955f7f0bd9d9c3e1a4aa48da7da5c67922"
compacted: false
heading_path: ["5 *Panels*","**The Font Menu**"]
symbol: null
address: null
asset_path: null
---

## **The Font Menu**

| Font        |       |
|-------------|-------|
| Font Panel  | t     |
| Bold        | þ     |
| Italic      | i     |
| Underline   |       |
| Larger      |       |
| Smaller     |       |
| Heavier     | - 1,4 |
| Lighter     | ·     |
| Superscript |       |
| Subscript   |       |
| Unscript    |       |
| (add here)  |       |
| Copy Font   | 3     |
| Paste Font  | 4     |
|             |       |

Applications that support text entry and editing should provide a Font menu and Font panel. The Font panel is described in Chapter 5. It contains controls that let users set and preview fonts. The Font menu has a command to bring up the panel, and commands to make common adjustments to a font.

Each command alters one aspect of the font, such as its size or style, while leaving other aspects intact. The Font menu and Font panel target currently selected text. The Preferences panel should be used to alter the default font.

| Command    | Action                                                                                                                                                                                                   |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Font Panel | Brings up the Font panel.                                                                                                                                                                                |
| Bold       | Makes the current selection bold, if it's not bold already, and makes<br>it unbold if it is. The name of the command must alternate between<br>Bold and Unbold depending on the selection.               |
| Italic     | Makes the current selection italic or oblique, if it isn't already, and<br>makes it unitalic if it is. The name of the command must alternate<br>between Italic and Unitalic depending on the selection. |

( *continued)* 

| Command     | Action                                                                                                                                                                                                       |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Underline   | Underlines the current selection, if it isn't already underlined, and<br>removes the underlining if it is. When the current selection is already<br>underlined, the command name must change to Ununderline. |
| Larger      | Makes the current selection one point larger.                                                                                                                                                                |
| Smaller     | Makes the current selection one point smaller.                                                                                                                                                               |
| Heavier     | Uses a heavier typeface to display the current selection.                                                                                                                                                    |
| Lighter     | Uses a lighter typeface to display the current selection.                                                                                                                                                    |
| Superscript | Moves the currently selected text up an appropriate amount for a<br>superscript. Choosing the command again moves the text that<br>much higher.                                                              |
| Subscript   | Moves the currently selected text down an appropriate amount for<br>a subscript. Choosing the command again moves the text that<br>much lower.                                                               |
| Unscript    | Returns the selected superscripted or subscripted text to the normal<br>baseline of the text.                                                                                                                |
| Copy Font   | Copies from the current selection all the text attributes listed in this<br>menu, including font family, font size, bold, italic, underlining,<br>superscript, and subscript.                                |
| Paste Font  | Alters the current selection so that it has all the font attributes<br>previously copied with the Copy Font command.                                                                                         |