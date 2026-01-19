<!-- Chunk 87 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 418 -->
- window controls in title bars (close, minimize, and zoom buttons)
- title bars, including proxy icons
- toolbar buttons (when the button's action is not potentially harmful)
- scroll bars  
Don't provide click-through for items or actions that  
- are potentially harmful (for example, the Delete button in Mail)
- are difficult to recover from, such as
- actions that are difficult or impossible to cancel (the Send button in Mail)
- dismissing a dialog without knowing what action was taken (for example, it's not easy to "unsave" a document)
- removing the user from the current context (selecting a new item in a column, for example, can change the target of the Finder window)  
Clicking in one of these situations results in the window being brought forward but no action being taken.  
<span id="page-80-1"></span>**Figure 5-10** The Save button on the inactive window does not support click-through  
![](images/_page_80_Picture_3.jpeg)  
In general, you can implement click-through for an item that provides confirmation feedback before taking place—in other words, the user can cancel the action—such as deleting a user in Users preferences. If you want to implement click-through on an item that doesn't provide confirmation feedback, consider how difficult it will be for the user to undo the action. For example, in Mail, it would be inadvisable to implement click-through for the Delete button, which deletes a message without providing feedback first, because its resulting action is harmful. You could, however, provide click-through for the Add to Favorites button in the Save dialog because its resulting action is not harmful and is fairly easy to undo.