<!-- Chunk 249 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 525 -->
Some Macintosh keyboards include four arrow keys: Up Arrow, Down Arrow, Left Arrow, and Right Arrow. These keys are shown in Figure 10-12.  
Figure 10-12 Arrow keys  
![](images/_page_304_Picture_9.jpeg)  
Arrow keys  
#### Appropriate Uses for the Arrow Keys  
As a general rule, arrow keys are used to move the insertion point and, when used with the Shift key, to extend or shrink selections. The guidelines in this section apply both to moving the insertion point and to making selections. They are the minimum guidelines for arrow keys. You may expand these guidelines if you need to, keeping in mind their spirit.  
Arrow keys are never used to duplicate the function of the scroll bars or to move the mouse pointer. They may be used as a shortcut to move the insertion point and, under some circumstances, to make selections.  
An application should use the arrow keys only when appropriate to the task. Applications that deal with text or arrays, such as word processors, spreadsheets, and databases, have an insertion point. This insertion point could be moved both by the mouse and by the arrow keys.  
If the user makes a selection and then presses the Right Arrow or Left Arrow key, your application should shrink the selection to zero length and place the insertion point at the right or left edge of the selection. This action doesn't move the location of the selection.  
The Keyboard 281  
<span id="page-305-0"></span>In a graphics application, the arrow keys can be used for fine movement of selected objects, particularly since graphics applications typically have no insertion point. If a graphics application uses arrow keys, it should be only to move the selected object by the smallest possible increment (one pixel or one grid unit). For example, the user could select an object and use the arrow keys to move one pixel per keystroke in the direction of the arrow key pressed. Generally, graphics applications shouldn't use arrow keys to change a selection or use modifier keys to multiply the effect of arrow keys. (Note that the Finder uses arrow keys to change the selection.)