<!-- Chunk 115 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 266 -->
When the user closes a document that has been edited but not saved, the application must bring up a Close panel giving the user an opportunity to cancel the operation, save the document before closing, or confirm that it should be closed without saving. This attention panel should have at least these three buttons:  
Cancel Don't Save Save  
Save is the default option because many users don't think of closing a document and saving the most recent changes to it as separate operations-for many, closing implies saving.  
If closing a document or window has consequences other than that unsaved changes would be lost, the application must still bring up a Close panel informing the user. For example, when the user closes a terminal emulation window, the application should notify the user that closing the window will cause the running command to be terminated. If the panel can't offer the user any way of avoiding the side effects, it should have these buttons:  
Cancel Close Anyway  
**Note:** Do *not* bring up a Close panel unless work is about to be lost.