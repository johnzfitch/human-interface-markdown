<!-- Chunk 141 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 311 -->
When an item is dragged from an application to the desktop, a clipping is created that contains the data in the dragged item. If discontinuous selections are dragged from a source to the Finder, a separate clipping is created for each selected item.  
Your application should provide a number ofrepresentations (such as TEXT, PICT, and native formats) to ensure flexibility with different subsequent destinations. Regardless of which representations are stored, round-trip data integrity should be preserved; a clipping dragged back into its source should be identical to the original item.  
Clippings **127**  
#### **C HAPTER 9**  
Drag and Drop  
<span id="page-128-0"></span>Although Mac OS X uses graphics as a primary means of user-computer interaction, text is prevalent throughout the interface for such things as button names, pop-up menu labels, dialog messages, and onscreen help. Using text consistently and clearly is a critical component of interface design.  
Your product development team should include a skilled writer who is responsible for reviewing all user-visible onscreen text aswell the instructional documentation. Thewriter should referto the *Apple Publications Style Guide* for guidance on Apple-specific terminology.