<!-- Chunk 152 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 552 -->
<span id="page-117-15"></span><span id="page-117-6"></span><span id="page-117-5"></span><span id="page-117-4"></span>If the source and destination are in the same container (for example, a window or a volume), a drag-and-drop operation is interpreted as a move (that is, cut and paste). Dragging an item from one container to another initiates a copy (copy and paste). The user can perform a copy operation within the same container by pressing the Option key while dragging. When performing a copy operation, indicate a copy operation to the user by using the copy cursor. (See ["Standard](#page-156-1) Cursors" (page 157))  
When determining whether to move or copy a dragged item, you must consider the underlying data structure of the contents in the destination window. For example, if your application allows two windows to display the same document (multiple views of the same data), a drag-and-drop operation between these two windows should result in a move.  
<span id="page-117-11"></span><span id="page-117-9"></span><span id="page-117-7"></span><span id="page-117-3"></span>The principle driving these drag-and-drop guidelinesisto prevent the user from accidental data loss. Because an Undo command in the destination application does not trigger an Undo in the source application, moving data across applications may result in potential data loss. Moving data within the same window (or same volume, as in the case of the Finder) does not lead to data loss.  
**Table 9-1** Common drag-and-drop operations and results  
<span id="page-117-13"></span><span id="page-117-8"></span>  
| Dragged item       | Destination             | Result                    |
|--------------------|-------------------------|---------------------------|
| Data in a document | The same document       | Move                      |
| Data in a document | Another document        | Copy                      |
| Data in a document | The Finder              | Copy (creates a clipping) |
| Finder icon        | An open document window | Copy                      |
| Finder icon        | The same volume         | Move                      |
| Finder icon        | Another volume          | Copy                      |