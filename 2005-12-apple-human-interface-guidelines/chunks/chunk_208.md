<!-- Chunk 208 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 843 -->
<span id="page-147-2"></span>There are a few standard symbols you can use to indicate additional information in menus. These are listed in Table 12-1 and discussed in the following text. Don't use other, arbitrary symbols in menus, because they add visual clutter and may confuse people.  
**Table 12-1** Acceptable characters for use in menus  
| Character | Meaning                                                                                                   |
|-----------|-----------------------------------------------------------------------------------------------------------|
|           | The active document in the Window menu; in other menus, a setting that applies to the<br>entire selection |
|           | A setting that applies to only part of the selection                                                      |
|           | A window with unsaved changes                                                                             |
|           | In the Window menu, a document that is currently minimized in the Dock                                    |  
In the Window menu, a **checkmark** should appear next to the active document's name. Checkmarks can also be used in other menus to indicate that the setting applies to the entire selection. You can use checkmarks for mutually exclusive attribute groups (the user can select only one item in the group, such as font size) or accumulating attribute groups (more than one item can be selected at once, such as Bold and Italic).  
Use a **dash** to indicate that an attribute applies to only part of the selection. For example, if selected text has two styles applied to it, put a dash next to each style name. When it's appropriate, you can combine checkmarks and dashes in the same menu. See ["Toggled Menu Items"](#page-149-0) (page 150) for more information on how to use checkmarks and dashes in menus.  
<span id="page-148-3"></span><span id="page-148-2"></span>**Note:** Include a menu command, such as Plain, for removing all formatting from mixed-state text.  
<span id="page-148-1"></span>Use a **bullet** next to a document with unsaved changes and a **diamond** for a document the user has minimized into the Dock. A minimized document with unsaved changes should have a diamond only. If the active window has unsaved changes, the checkmark should override the bullet in the Window menu.  
**Carbon:** In the standard Window menu, these symbols are managed automatically. Otherwise, use the SetItemMark function with a char parameter of kCheckCharCode for the active document, kBulletCharCode for a document with unsaved changes, and kDiamondCharCode for a minimized document. These constants work only in the Window menu.  
**Cocoa:** These symbols are managed by the Cocoa framework.  
<span id="page-148-0"></span>Figure 12-7 and Figure 12-8 show some examples of how to use and how not to use symbols in menus.  
![](images/_page_148_Picture_9.jpeg)  
**Figure 12-7** Symbols in menus  
<span id="page-149-1"></span>**Figure 12-8** Don't use arbitrary symbols in menus  
![](images/_page_149_Picture_3.jpeg)  
<span id="page-149-4"></span><span id="page-149-2"></span><span id="page-149-0"></span>If you have a Style menu, you may display menu items in the actual style so users can see what effect the menu item will have. Don't use text styles in menus other than a Style menu.