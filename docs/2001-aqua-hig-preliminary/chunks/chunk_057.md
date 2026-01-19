<!-- Chunk 57 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 627 -->
An item that provides click-through is one that a user can activate on an inactive window with one click, rather than clicking first to make the window active and then clicking the item. Click-through provides greater efficiency in performing such tasks as closing or resizing inactive windows, and copying or moving files. In many cases, however, click-through could confuse a user who clicks an item unintentionally.  
<span id="page-59-4"></span>On an inactive window, an item that provides click-through has its text or glyph (such as arrows) in 100-percent black; if the item is usually colored (such as a radio button), it is colorless in its click-through state. Items that do not provide click-through appear in their disabled state (50-percent dimmed).  
<span id="page-59-1"></span>**Figure 5-6** Controls in an inactive window in click-through or disabled state  
![](images/_page_59_Picture_6.jpeg)  
You can provide click-through for such items as  
■ pop-up menus  
- text fields
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
In general, you can implement click-through on an item that provides confirmation feedback before taking place—in other words, the user can cancel the action—such as deleting a user in Users preferences. If you want to implement click-through on an item that doesn't provide confirmation feedback, consider how difficult it will be for the user to undo the action. For example, in Mail, it would be inadvisable to implement click-through on the Delete button, which deletes a message without providing feedback first, because its resulting action is harmful. You could, however, provide click-through on the Add to Favorites button in the Save dialog because its resulting action is not harmful and is fairly easy to undo.