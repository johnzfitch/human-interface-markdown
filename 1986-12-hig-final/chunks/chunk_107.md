<!-- Chunk 107 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 540 -->
"Intelligent" cut and paste is a set of editing features that takes into account the need for spaces between words. To understand why this feature is helpful, consider the following sequence of events in a text application without intelligent cut and paste:  
1. A sentence in the user's document reads  
Returns are only accepted if the merchandise is damaged.  
The user wants to change this to  
#### Returns are accepted only if the merchandise is damaged.  
- 2. The user selects the word *only* by double-clicking. The letters are highlighted, but neither of the adjacent spaces is highlighted.
- 3. The user chooses Cut, clicks just before the word *if*, and chooses Paste.
- 4. The sentence now reads  
Returns are accepted onlyif the merchandise is damaged.  
Note the extra space between *are* and *accepted*, and the lack of a space between *only* and *if*. To correct the sentence, the user has to remove the extra space between *are* and *accepted*, and add one between *only* and *if*. At this point he or she may be wondering why people bother with computers at all.  
If an application supports intelligent cut and paste, the rules are:  
- If the user selects a word or a range of words, the selection itself is highlighted, but spaces adjacent to the selection are not highlighted.
- When the user chooses Cut, if the character to the left of the selection is a space, cut the space along with the selection. If the character to the left of the selection is not a space, but the character to the right of the selection is a space, cut that space along with the selection.
- When the user chooses Paste, if the character to the left or right of the current selection is part of a word, insert a space before pasting.  
If the left or right end of a text selection is a word, follow these rules at that end, regardless of whether there's a word at the other end. Figure 65 shows an example of intelligent cut and paste.  
#### Example 1:  
1. Select a word. Drink to me with thine eyes.  
2. Choose Cut. Drink to me with thine eyes.  
3. Select an insertion point. Drink to me with thine eyes.  
4. Choose Paste. Drink to me with only thine eyes.