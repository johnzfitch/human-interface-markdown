<!-- Chunk 206 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 560 -->
Menu item names should be either actions performed on an object or attributes applied to an object:  
- <span id="page-145-1"></span>■ Actions are verbs or verb phrases that declare the action that occurs when the user chooses the item. For example, Save means *save my file* and Copy means *copy the selected data.* Your action menu commands should begin in the same way, with an action verb in its base (simplest) form.
- Attributes are adjectives or adjective phrases that describe the change the command implements. Adjectives in menus *imply* an action and should fit into the sentence "Change the selected object to …" —for example, *Bold* or *Italic*.  
<span id="page-145-2"></span>When a menu item is unavailable—because it doesn't apply to the selected object or to the selected object in its current state, or because nothing is selected, for example—the item should appear dimmed (gray) in the menu and is not highlighted when the user moves the pointer over it.  
Use title-style capitalization in your menus. See ["Capitalization of Interface Elements"](#page-121-1) (page 122) for more information on this style.  
<span id="page-145-3"></span>An **ellipsis character**(…) after a menu item indicates to the user that additional information is required to complete a command. For information on when to use an ellipsis in menu items, see ["Using the](#page-120-1) [Ellipsis Character"](#page-120-1) (page 121).  
<span id="page-145-0"></span>It may be appropriate in some cases to provide **dynamic menu items**—commands that change when the user presses a modifier key. For example, if the user opens the Window menu in the Finder and then presses the Option key, some of the menu items change, as shown in Figure 12-4. The system appropriately sizes the menu to hold the widest item, including Option-enabled commands.  
**Figure 12-4** Dynamic menu items  
Without modifier key pressed  
![](images/_page_145_Picture_10.jpeg)  
With modifier key pressed  
![](images/_page_145_Picture_12.jpeg)  
**Carbon:** Use SetMenuItemAttributes with the kMenuItemAttrDynamic attribute.  
**Cocoa:** Use the setAlternate: method in NSMenuItem to designate one menu item as the alternate of another. This can be done in Interface Builder.