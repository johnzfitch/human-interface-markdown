<!-- Chunk 152 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 996 -->
| Tout        |         |
|-------------|---------|
| Text        |         |
| Align Left  |         |
| Center      |         |
| Align Right |         |
| Justify     | 9,147-2 |
| (add here)  |         |
| Show Ruler  |         |
| Copy Ruler  | 1       |
| Paste Ruler | 2       |  
The Text menu is a collection of formatting commands that affect text. All the Text menu commands are supported by the Application Kit's Text object. These commands can be isolated into a Text submenu, as shown here, or be included directly in the Format menu. If you have other formatting commands that are more important to your application, those commands, rather than these, should go in the Format menu.  
| Command<br>Align Left | Action<br>Aligns the text at the left margin, leaving a ragged right margin.                                                                                                                                                                                                                                                                 |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Center                | Centers the text between the left and right margins.                                                                                                                                                                                                                                                                                         |
| Align Right           | Aligns the text at the right margin, leaving a ragged left margin.                                                                                                                                                                                                                                                                           |
| Justify               | Aligns the text at both the left and right margins.                                                                                                                                                                                                                                                                                          |
| Show Ruler            | Displays a ruler in the text area, if the ruler isn't currently visible.<br>Otherwise, this command hides the ruler. The name must alternate<br>between Show Ruler and Hide Ruler, depending on the state of the<br>text area. The ruler is a scale containing controls that affect the<br>format of a paragraph (such as margins and tabs). |
| Copy Ruler            | Copies the ruler settings in the first paragraph of the selected text.                                                                                                                                                                                                                                                                       |
| Paste Ruler           | Alters the paragraphs containing the text selection to have the<br>settings most recently copied with the Copy Ruler command.                                                                                                                                                                                                                |  
An application that has many other text-related commands, such as a word processor, can arrange all its text-formatting commands within the Format menu, as best fits its needs. (See also the discussion of the Format menu earlier.) However, for consistency, all applications should, as far as possible, retain the command names shown above for the Text menu, no matter how the commands are arranged.