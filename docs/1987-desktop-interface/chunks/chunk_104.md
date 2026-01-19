<!-- Chunk 104 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 713 -->
"Intelligent" cut and paste is a set of editing features that takes into account the need for spaces between words. To understand why this feature is helpful, consider the following sequence of events in a text application without intelligent cut and paste:  
1 A sentence in the user's document reads  
Returns are only accepted if the merchandise is damaged.  
The user wants to change this to  
Returns are accepted only if the merchandise is damaged.  
- 2 . The user selects the word only by double-clicking. The letters are highlighted, but neither of the adjacent spaces is highlighted.
- 3 . The user chooses Cut, clicks just before the word if and chooses Paste.
- 4 . The sentence now reads  
Returns are accepted onlyifthe merchandise is damaged.  
Note the extra space between are and accepted, and the lack of a space between only and if. To correct the sentence, the user has to remove the extra space between are and accepted, and add one between only and if. At this point he or she may be wondering why people bother with computers at all.  
If an application supports intelligent cut and paste, these are the rules:  
- a If the user selects a word or a range of words, the selection itself is highlighted, but spaces adjacent to the selection are not highlighted.
- When the user chooses Cut, if the character to the left of the selection is <sup>a</sup> space, cut the space along with the selection. If the character to the left of the selection is not a space, but the character to the right of the selection is a space, cut that space along with the selection.
- When the user chooses Paste, if the character to the left or right of the current selection is part of a word, insert a space before pasting.  
If the left or right end of a text selection is a word, follow these rules at that end, regardless of whether there's <sup>a</sup> word at the other end. Figure 3-65 shows two examples of intelligent cut and paste.  
1 Select a word  
2. Choose Cut  
3. Select an Insertion point  
4. Choose Paste  
Drink to me HflBwith thine eyes  
Drink to me|with thine eyes  
Drink to me with (thine eyes  
Drink to me with only|thine eyes  
1  
3. Select an Insertion point How|, brown cow  
Select a word How IWBB brown cow  
2. Choose Cut How,| brown cow  
4. Choose Paste How now|, brown cow  
Figure 3-65  
Intelligent cut and paste  
Note that the selected text is not necessarily exactly the same range that will be cut and, eventually, pasted.  
Intelligent cut and paste should be used only if the application supports the full definition of a word (as detailed in this chapter under "Selections in Text"), rather than the definition of a word as "anything between two spaces." These rules apply to any selection consisting of one or more whole words, whether the user selected it with a double click or as a range selection.