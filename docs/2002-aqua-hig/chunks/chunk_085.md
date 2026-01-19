<!-- Chunk 85 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 375 -->
An item that provides click-through is one that a user can activate on an inactive window with one click, rather than clicking first to make the window active and then clicking the item. Click-through provides greater efficiency in performing such tasks as closing or resizing inactive windows, and copying or moving files. In many cases, however, click-through could confuse a user who clicks an item unintentionally.  
Click-through is not a property of a class of controls; any control could support click-through in many contexts, but the same control could disable click-through when its use could be destructive in a particular context.  
In an inactive window, an item that provides click-through should have its text or glyph (such as an arrow) in 100-percent black; if the item usually has color (such as a radio button), it should be colorless in its click-through state. Items that do not provide click-through should appear in their disabled state.  
<span id="page-82-0"></span>**Figure 5-11** An inactive window with controls that support click-through  
![](images/_page_82_Picture_3.jpeg)  
You can provide click-through for such items as  
- pop-up menus
- text fields
- window controls in title bars (close, minimize, and zoom buttons)
- title bars, including proxy icons
- toolbar buttons (when the button's action is not potentially harmful)
- scroll bars  
Don't provide click-through for items or actions that  
■ are potentially harmful (for example, the Delete button in Mail)