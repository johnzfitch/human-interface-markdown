<!-- Chunk 261 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 492 -->
In the case of graphics, all selections are discontinuous selections because graphic objects are discrete. This is not the case with arrays and text, in which an extended selection made by a Shift-click always includes everything between the old anchor point and the new active end. In arrays and text, discontinuous selections are made by clicking while holding down the Command key.  
To make a discontinuous selection in a text or array application, the user selects the first piece in the usual way and holds down the Command key while selecting the remaining pieces. Each piece is selected in the same way as if it were the whole selection, but because the Command key is held down, the new pieces are *added* to the existing selection instead of replacing it. If one of the pieces selected with Command-click is already within an existing part of the selection, then instead of being added to the selection, it's removed from the selection.  
Selecting **291**  
<span id="page-315-0"></span>Figure 10-18 shows the process of adding cells to and removing cells from a discontinuous selection.  
1  
**Figure 10-18** Discontinuous selection within an array  
- 1. Cells B2, B3, C2, and C3 are selected.
- 2 3 4 5  
A BCD  
- 2. The user holds down the Command key and clicks in D5.
- 1 2 3 4 5 A BCD
- 3. The user holds down the Command key and clicks in C3.  
![](images/_page_315_Figure_9.jpeg)  
Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after making a discontinuous selection, but not allow the user to type replacement characters. In this situation, it wouldn't be apparent to users which part of the selection the characters would replace. Decide what makes sense in the context of your application and test it with users to make sure that their needs are met.  
![](images/_page_315_Picture_11.jpeg)