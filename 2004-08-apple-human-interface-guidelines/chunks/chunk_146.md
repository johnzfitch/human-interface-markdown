<!-- Chunk 146 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 754 -->
An item that provides **click-through** is one that a user can activate on an inactive window with one click, instead of clicking first to make the window active and then clicking the item. Click-through provides greater efficiency in performing such tasks as closing or resizing inactive windows, and copying or moving files. In many cases, however, click-through could confuse a user who clicks an item unintentionally.  
Click-through is not a property of a class of controls; any control could support click-through in many contexts, but the same control could disable click-through when its use could be destructive in a particular context.  
In an inactive window, an item that provides click-through should have its text or glyph (such as an arrow) in 100-percent black; if the item usually has color (such as a radio button), it should be colorless in its click-through state. Items that do not provide click-through should appear in their disabled state.  
<span id="page-122-0"></span>**Figure 8-20** An inactive window with controls that support click-through  
![](images/_page_122_Picture_3.jpeg)  
Don't provide click-through for items or actions that:  
- Are potentially harmful (for example, the Delete button in Mail)
- Are difficult to recover from, such as:
- ❏ Actions that are difficult or impossible to cancel (the Send button in Mail)
- ❏ Dismissing a dialog without knowing what action was taken (for example, it's not easy to "unsave" a document)
- ❏ Removing the user from the current context (selecting a new item in a column, for example, can change the target of the Finder window)  
Clicking in any one of these situations should result in the window being brought forward but no action being taken.  
<span id="page-123-2"></span><span id="page-123-1"></span>**Figure 8-21** The Delete button on the inactive window does not support click-through  
![](images/_page_123_Picture_3.jpeg)  
In general, you can implement click-through for a command that provides confirmation feedback before executing—in other words, the user can cancel the action—such as deleting a user in Accounts preferences. If you want to implement click-through for an item that doesn't provide confirmation feedback, consider how difficult it will be for the user to undo the action after it's performed. For example, in Mail, it would be inadvisable to implement click-through for the Delete button, which deletes a message without providing feedback first, because its resulting action is harmful and difficult to undo. Click-through for the New button is OK because its resulting action is not harmful and is easy to undo.  
**Carbon:** Click-through is *off* by default. You must explicitly enable click-through for specific controls.  
<span id="page-123-5"></span><span id="page-123-0"></span>**Cocoa:** Click-through is *on* by default. You must explicitly disable click-through for specific controls. Do not assume that the default behavior is the correct behavior. Make sure to apply the above guidelines.