<!-- Chunk 86 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 356 -->
The following are a summary of the practices which should be observed to make code easily localizable:  
- Text strings should be kept in separate source files.
- If custom routines are used instead of the ones in ROM , to perform screen 110, they should be isolated in a self-contained module.  
![](images/_page_101_Picture_0.jpeg)  
- Sorting routines should also be kept in separate modules ( they probably do not work in a foreign language).
- Any graphic symbol should be approved by Apple's Human Interface Group.
- <sup>s</sup> Strings should not be concatenated to build longer messages or cut to form a singular form or change the meaning of a word.
- Data compression should not be used: the algorythm would probably not work with the extended character set of a foreign language.
- Documentation should be provided outlining the structure of each program so that a translator will be able to understand what each source code file does. If necessary, include special notes just for the translator.
- A build procedure should be provided of sufficient detail to allow a translator with minimal technical knowledge to create a running version· of the program without intervention from the author.  
I "  
• Commands, help screen, key strokes and any other table which might contain text, should be kept completely separate from the code and accessed only by symbolic addresses.  
![](images/_page_103_Picture_0.jpeg)