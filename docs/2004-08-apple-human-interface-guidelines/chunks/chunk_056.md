<!-- Chunk 56 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 543 -->
<span id="page-43-14"></span><span id="page-43-7"></span><span id="page-43-5"></span>If the source and destination are in the same container (for example, a window or a volume), a drag-and-drop operation is interpreted as a move (that is, cut and paste). Dragging an item from one container to another initiates a copy (copy and paste). The user can perform a copy operation within the same container by pressing the Option key while dragging. When performing a copy operation, indicate a copy operation to the user by using the copy cursor. (See ["Standard Cursors"](#page-68-1) (page 69).)  
When determining whether to move or copy a dragged item, you must consider the underlying data structure of the contents in the destination window. For example, if your application allows two windows to display the same document (multiple views of the same data), a drag-and-drop operation between these two windows should result in a move.  
<span id="page-43-11"></span><span id="page-43-8"></span>The principle driving these drag-and-drop guidelines is to prevent the user from accidental data loss. Because an Undo command in the destination application does not trigger an Undo in the source application, moving data across applications may result in potential data loss. Moving data within the same window (or same volume, as in the case of the Finder) does not lead to data loss.  
<span id="page-43-10"></span><span id="page-43-3"></span>**Table 3-1** Common drag-and-drop operations and results  
<span id="page-43-12"></span><span id="page-43-9"></span>  
| Dragged item       | Destination             | Result                    |
|--------------------|-------------------------|---------------------------|
| Data in a document | The same document       | Move                      |
| Data in a document | Another document        | Copy                      |
| Data in a document | The Finder              | Copy (creates a clipping) |
| Finder icon        | An open document window | Copy                      |
| Finder icon        | The same volume         | Move                      |
| Finder icon        | Another volume          | Copy                      |