<!-- Chunk 153 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 571 -->
<span id="page-113-14"></span><span id="page-113-6"></span>If the source and destination are in the same container (for example, a window or a volume), a drag-and-drop operation is interpreted as a move (that is, cut and paste). Dragging an item from one container to another initiates a copy (copy and paste). The user can perform a copy operation within the same container by pressing the Option key while dragging. When performing a copy operation, indicate a copy operation to the user by using the copy cursor. (See ["Standard](#page-142-1) Cursors" (page 143).)  
When determining whether to move or copy a dragged item, you must consider the underlying data structure of the contents in the destination window. For example, if your application allows two windows to displaythe same document (multiple views of the same data), a drag-and-drop operation between these two windows should result in a move.  
<span id="page-113-12"></span><span id="page-113-11"></span><span id="page-113-9"></span><span id="page-113-2"></span>The principle drivingthese drag-and-drop guidelines is to prevent the user from accidental data loss. Because an Undo command in the destination application does not trigger an Undo in the source application, moving data across applications may result in potential data loss. Moving data within the same window (or same volume, as in the case of the Finder) does not lead to data loss.  
| Table 8-1 | Common drag-and-drop operations and results |  |
|-----------|---------------------------------------------|--|
|-----------|---------------------------------------------|--|  
<span id="page-113-13"></span><span id="page-113-10"></span>  
| Dragged item       | Destination             | Result                    |
|--------------------|-------------------------|---------------------------|
| Data in a document | The same document       | Move                      |
| Data in a document | Another document        | Copy                      |
| Data in a document | The Finder              | Copy (creates a clipping) |
| Finder icon        | An open document window | Copy                      |
| Finder icon        | The same volume         | Move                      |
| Finder icon        | Another volume          | Copy                      |