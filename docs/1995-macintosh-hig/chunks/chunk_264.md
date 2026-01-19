<!-- Chunk 264 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 483 -->
A word or range of words can also be selected in the same way as any other range; whether this type of selection is treated as a range of characters or as a range of words depends on the operation. For example, in a word processor, a range of individual characters that coincides with a range of words is treated like characters for purposes of extending a selection, but is treated like words for purposes of "intelligent cut and paste" (described in the section "Intelligent Cut and Paste" on page 301).  
The following definition of a word applies in the United States and Canada and in some other countries. In many countries, the definition differs to reflect local formats for numbers, dates, and currency. A word is defined as any continuous string that contains any of the following characters:  
- a letter
- a digit
- a nonbreaking space (Option-space or Command-space)
- a currency symbol (\$, ¢, £, or ¥)
- a percent sign
- a comma between digits
- a period before a digit
- an apostrophe between letters or digits
- a hyphen, but not Option-hyphen (–) or Option-Shift-hyphen (—)  
If the user double-clicks any character *not* on this list, only that character is selected.  
These are examples of words:  
- \$123,456.78
- shouldn't
- 3 1/2 (with a nonbreaking space)
- .5%  
These are examples of strings treated as more than one word:  
- 7/10/6
- blue cheese (with a breaking space)
- "Wow!" (The quotation marks and exclamation point aren't part of the word.)  
<span id="page-318-0"></span>In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parentheses in a pair, as well as all the characters between them, by double-clicking either one of them. The same feature could be implemented for braces and brackets. This would mean that the user could select the entire expression  
[*x*+*y*–(4\*3)^(*n*–1)]  
simply by double-clicking [ or ].