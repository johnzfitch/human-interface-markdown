<!-- Chunk 98 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 712 -->
To use arrow keys to make a text selection, the user holds down Shift while pressing an arrow key. If it's important that your Macintosh application makes use of the numeric keypad, you shouldn't use these Shift-arrow key combinations. This is because the key codes for the four Shift-arrow key combinations are the same as those for the keypad's +, \*, /, and - keys. If the use of a Shift-arrow key combination for making selections is more important to your application than is the numeric keypad, the following paragraphs describe how it should work.  
When <sup>a</sup> Shift-arrow key combination is pressed, the active end of the selection moves and the range over which it moves becomes selected. If both the Shift key and another modifier key are held down, the end of the selection moves as defined for the particular modifier key, and the range over which it moves becomes selected. For example, Option-Shift-Left Arrow selects the whole word that contains the character to the left of the insertion point (just like double-clicking on a word).  
A selection made by using the mouse isno different from one made by using arrow keys. A selection started with the mouse can be extended by using Shift and Left or Right Arrow.  
In a text application, pressing Shift and either Left Arrow or Right Arrow selects a single character. Assuming that the Left Arrow key was used, the anchor point of the selection is on the right side of the selection, the active end on the left. Each subsequent Shift- Left Arrow adds another character to the left side of the selection. A Shift-Right Arrow at this point shrinks the selection. Figure 3-57 summarizes these actions.  
| word<br>a<br>point<br>Insertion<br>is within<br>1. | wdrd  |
|----------------------------------------------------|-------|
| is pressed<br>Shift-*—<br>2.                       | wBrd  |
| Another<br>Shift-*-<br>3.                          | BBrd  |
| Shift<br>4.                                        | wgrd  |
| more<br>Three<br>times<br>Shift—<br>5.             | woffl |  
Figure 3-57 Selecting with Shift and arrow keys  
Pressing Option-Shift and either Left Arrow or Right Arrow (in a text application) selects the entire word containing the character to the left of the insertion point. Assuming Left Arrow was pressed, the anchor point is at the right end of the word, the active end at the left. Each subsequent Option-Shift-Left Arrow adds another word to the left end of the selection, as shown in Figure 3-58.  
| word<br>point<br>a<br>Insertion<br>is within<br>1. | another<br>wofd |
|----------------------------------------------------|-----------------|
| Is pressed<br>Option-Shift-*-<br>2.                | another         |
| Another<br>Option-Shift-—<br>3.                    |                 |  
Figure 3-58 Selecting with Option-Shift and arrow keys