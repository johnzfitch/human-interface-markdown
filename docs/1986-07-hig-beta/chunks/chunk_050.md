<!-- Chunk 50 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 393 -->
"Intelligent" cut and paste is a set of editing features that takes into account the need for spaces between words--even when users can select words by double clicking.  
To understand why this feature is helpful, consider the following sequence of events in an application *without* intelligent cut and paste:  
1. A sentence in the user's document reads  
*Returns are only accepted* if*the merchandise is damaged.*  
The user wants to chage this to  
*Returns are accepted only* if*the merchandise is damaged.*  
- 2. The user selects the word *only* by double clicking. The letters are highlighted, but neither of the adjacent spaces is highlighted.
- 3. The user chooses Cut, clicks just before the word if, and chooses Paste.
- 4. The sentence now reads  
*Returns are accepted onlyifthe merchandise is damaged.*  
To correct the sentence, the user has to remove the extra space between *are* and *accepted,* and add one between *only* and if. At this point he or she may be wondering why people bother with computers at all.  
If an application supports intelligent cut and paste, foe rules are:  
- <sup>o</sup> If the user selects a word or a range of words, highlight the selection, but not any adj acent spaces.
- <sup>o</sup> When the user chooses Cut, if the character to the left of the selection is a space, discard it. Otherwise, if the character to the right of the selection is a space, discard it.
- <sup>o</sup> When the user chooses Paste, if the character to the left or right of the current selection is part of a word, insert a space before pasting.