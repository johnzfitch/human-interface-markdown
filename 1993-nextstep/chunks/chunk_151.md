<!-- Chunk 151 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 1710 -->
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
#### **Programming Note: The Font Menu**  
By dragging this menu in from Interface Builders Palettes window, you getthis menu and its functionality from the Text object with almost no additional work. Still, you should make sure that every command works, dims, and changes it name as it should.  
**Note:** If the current selection is an insertion point, all the commands in the Font menu affect the next set of characters inserted, rather than any existing text, unless the text area can contain only one font. If an area of text can have only one font, then the Font menu and panel change the font of all the text in the area.  
The only required commands in the Font menu are Font Panel, Copy Font, and Paste Font, although frequently used commands like Bold and Italic should almost always be present. Applications that are not text intensive may decide to omit some of the less frequently used commands, such as Heavier and Lighter.  
Each command leaves the other font attributes intact. For example, Bold will change 11-point Times Roman to 11-point Times Bold and 24-point Courier Oblique to 24-point Courier Bold Oblique.  
If there's more than one font in the selection, Larger and Smaller change each to be one point larger or smaller than its current size. The other commands make only the change that's appropriate for the first character in the selection. For example, if the first character in a multifont selection is italic, the Unitalic command will remove the italic trait from all the text in the selection, but won't change any text that isn't italic. If the first character isn't italic, the same command (but now called Italic) will italicize the entire selection, but won't alter any text that's already italic.  
The Colors command, which brings up the Colors panel, often appears in the Font menu. However, it can appear elsewhere; each application should place the Colors command in a menu that indicates the kind of objects the Colors panel can affect. In Mail and Edit, colors can be applied only to characters (and not to their background), so the Colors command is in the Font menu.