<!-- Chunk 38 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 533 -->
Menu entries should be written so a novice can understand them, but an expert need read only a few keywords at the beginning. The examples below are a bit wordy, but illustrate the point: (the underlining shows the keywords an expert will use—it would not actually appear on the screen.)  
- 1. Load a file from disk into memory.
- 2. Edit the file currently in memory.  
- 3. Print the current document on the current printer.
- 4. Change printers: select a different printer to print your document.
- 5. Save the current file on disk.  
The most fundamental design element for the filecard metaphor is the three regions defined by the two solid-horizontal lines. These three regions should appear on every display in the program, on any Apple II computer in any mode. As simple as such an element is, it gives the user a visual anchor-point.  
The exact number of lines devoted to the three regions is not cast in stone: the real standard being striven for is that there be three regions with solid lines separating them, that these be devoted to titles, choices presented, and instructions. (The Apple II and Apple II+ can not produce a solid line in text mode; use either their hyphens or their short-underline characters.  
The title region can have up to three titles (usually two in forty-column mode). The middle title (or left title, if only 2) should be the name of the display, and if it is a menu, it should contain the word, "menu". The other displays you will use, such as data-entry and information, will have a similar format, so make sure your user is clearly aware of what he is being asked to do: use a properly descriptive title and do not use the word menu. Similarly, on such information screens, do not number itemized lists; bullet them: otherwise, about 25% of your users will try to type in a "selection". All displays except the main menu should have the words:  
Escape: [name of display]  
in the top, left-hand corner, so the user knows where she or he will go by pressing it.  
You may use or not use other titles as you see fit, but they should have a consistent meaning throughout a given application.