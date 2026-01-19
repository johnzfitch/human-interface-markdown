<!-- Chunk 86 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 353 -->
#### Windows  
- are difficult to recover from, such as
- actions that are difficult or impossible to cancel (the Send button in Mail)
- dismissing a dialog without knowing what action was taken (for example, it's not easy to "unsave" a document)
- removing the user from the current context (selecting a new item in a column, for example, can change the target of the Finder window)  
<span id="page-83-0"></span>Clicking in one of these situations should result in the window being brought forward but no action being taken.  
**Figure 5-12** The Save button on the inactive window does not support click-through  
![](images/_page_83_Picture_8.jpeg)  
In general, you can implement click-through for an item that provides confirmation feedback before taking place—in other words, the user can cancel the action—such as deleting a user in Accounts preferences. If you want to implement click-through on an item that doesn't provide confirmation feedback, consider how difficult it will  
<span id="page-84-2"></span>be for the user to undo the action. For example, in Mail, it would be inadvisable to implement click-through for the Delete button, which deletes a message without providing feedback first, because its resulting action is harmful. You could, however, provide click-through for the Add to Favorites button in the Save dialog because its resulting action is not harmful and is fairly easy to undo.