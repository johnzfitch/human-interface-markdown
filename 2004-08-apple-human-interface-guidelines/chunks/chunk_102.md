<!-- Chunk 102 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 497 -->
<span id="page-77-5"></span><span id="page-77-2"></span>Menu item names should be either actions performed on an object or attributes applied to an object:  
- Actions are verbs or verb phrases that declare the action that occurs when the user chooses the item. For example, Save means *save my file* and Copy means *copy the selected data.* Your action menu commands should begin in the same way, with an action verb in its base (simplest) form.
- Attributes are adjectives or adjective phrases that describe the change the command implements. Adjectives in menus *imply* an action and should fit into the sentence "Change the selected object to …" —for example, *Bold* or *Italic*.  
<span id="page-77-3"></span>When a menu item is unavailable—because it doesn't apply to the selected object or to the selected object in its current state, or because nothing is selected, for example—the item should appear dimmed (gray) in the menu and is not highlighted when the user moves the pointer over it.  
<span id="page-77-4"></span>Use title-style capitalization in your menus. See ["Capitalization of Interface Elements"](#page-53-0) (page 54) for more information on this style.  
<span id="page-77-1"></span>It may be appropriate in some cases to provide **dynamic menu items**—commands that change when the user presses a modifier key. For example, if the user opens the Window menu in the Finder and then presses the Option key, some of the menu items change, as shown in Figure 7-4. The system appropriately sizes the menu to hold the widest item, including Option-enabled commands.  
**Figure 7-4** Dynamic menu items  
W thout mod f er key pressed  
![](images/_page_77_Picture_11.jpeg)  
W th mod f er key pressed  
![](images/_page_77_Picture_13.jpeg)  
**Carbon:** Use SetMenuItemAttributes with the kMenuItemAttrDynamic attribute.  
**Cocoa:** Use the setAlternate: method in NSMenuItem to designate one menu item as the alternate of another. This can be done in Interface Builder.