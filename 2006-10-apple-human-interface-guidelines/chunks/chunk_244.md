<!-- Chunk 244 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 419 -->
Most of the time, the user should be in control of scrolling. Your application must perform automatic scrolling in these cases:  
- When your application performs an operation that results in making a new selection or moving the insertion point (for example,when the user searches for some text and your application locates it), scroll the document to show the new selection.
- When the user enters information from the keyboard at a location not visible within the window (for example, the insertion point is on one page and the user has navigated to another page), scroll the document automatically to incorporate and display the new information.
- Your application determines the distance to scroll.
- When the user moves the pointer past the edge of the window while holding down the mouse button to make an extended selection, scroll the document in the direction the pointer moves.
- When the user selects something, scrolls to a newlocation, and then tries to perform an operation on the selection, scroll so the selection is showingbeforeyour application performs the operation.  
Window Behavior **201**  
Whenever your application scrolls a document automatically, move the document only as much as is necessary. That is, if part of a selection is showing after the user performs an operation, don't scroll at all. If your application can scroll in only one direction to reveal the selection, don't scroll in both.  
<span id="page-201-2"></span>When autoscrolling to a selection, try to show the selection in context. When the selection is too large to show in its entirety, it might be a good idea to show some context instead of having the selection fill the window.