<!-- Chunk 148 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 514 -->
Intelligent cut and paste is a set of editing features that take into account the need for spaces between words. To understand why this feature is helpful, consider the following sequence of events in a text application *without* intelligent cut and paste:  
1. A sentence in the user's document reads  
User Input  
*Returns are only accepted if the merchandise is damaged.*  
The user wants to change this to  
*Returns are accepted only if the merchandise is damaged.*  
- 2. The user selects theword *only* by double-clicking. The letters are highlighted, but neither adjacent space is selected.
- 3. The user chooses Cut from the Edit menu, clicks just before the word *if,* and chooses Paste.
- 4. The sentence now reads  
*Returns are accepted onlyif the merchandise is damaged.*  
To correct the sentence, the user has to remove the extra space between *are* and *accepted,* and add a space between *only* and *if.*  
If your application supports intelligent cut and paste, follow these guidelines:  
- If the user selects aword or a range ofwords, the selection itself is highlighted, but spaces adjacent to the selection are not highlighted.
- When the user chooses Cut, if the character precedingthe selection is a space, cut that space along with the selection. If the character precedingthe selection is not a space, but the characterfollowing the selection is a space, cut that space along with the selection.
- When the user chooses Paste, if the character to the left or right of the current selection is part of a word (but not inside a word), insert a space before pasting.  
Use intelligent cut and paste only if the application supports the definition of a word as described in "What [Constitutes](#page-106-0) a Word" (page 107). These rules apply to any selection consisting of one or more whole words, no matter how the user made the selection.  
<span id="page-109-1"></span><span id="page-109-0"></span>**Note:** Intelligent cut and paste doesn't applyto all languages. Thai, Chinese, and Japanese, for example, don't contain spaces.