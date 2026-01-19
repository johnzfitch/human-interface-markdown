<!-- Chunk 226 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 512 -->
A **contextual menu** provides convenient access to often-used commands associated with an item. You can think of a contextual menu as a shortcut to commands that make sense in the context of the current task. Contextual menus open when the user presses the Control key while clicking an appropriate interface element or selection.  
A contextual menu behaves like a standard pull-down menu, except that moving the pointer off a contextual menu and onto a standard pull-down menu doesn't activate the second menu; the user must click once to close the contextual menu and click again or press to open the second menu.  
Contextual menus that are too long to display fully use the scrolling indicator (a downward-pointing triangle) and scroll like standard menus.  
Don't set a default item. If the user opens the menu and closes it without selecting anything, no action should occur.  
You define the items in your application's contextual menus. Include a small subset of the most commonly used commands in the appropriate context. For example, Edit menu commands should appear in the contextual menu for highlighted text, but a Save or a Print command should not.  
Always ensure that contextual menu items are also available as menu commands. A contextual menu is hidden by default and a user might not know it exists, so it should never be the only way to access a command. In particular, you should not use a contextual menu as the only way to access an advanced or power-user feature.  
Commands with keyboard shortcuts should be noted in the menu bar menu but not in the contextual menu. Use submenus with caution and keep them to one level.  
Contextual Menus **167**  
<span id="page-167-1"></span>**Figure 12-24** A contextual menu for an icon in the Finder and for a text selection in a document  
![](images/_page_167_Picture_3.jpeg)  
<span id="page-167-2"></span>**Carbon:** See *Menu Manager Reference* in Carbon User Experience Documentation. **Cocoa:** See *Application Menus and Pop-up Lists* in Cocoa User Experience Documentation.