<!-- Chunk 204 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 999 -->
- Is always visible and available, except in circumstances such as duringa slideshow(see discussion below)
- Always contains:
- ❏ The Apple menu (provided by the operating system)
- ❏ The Spotlight icon (provided by the operating system)
- ❏ The application menu (titled with the application name or an appropriate abbreviation if space is limited)
- ❏ A Window menu
- May contain the following menus, if they make sense in your application:
- ❏ A File menu
- ❏ An Edit menu
- ❏ A Format menu
- ❏ A View menu
- ❏ A Help menu  
- ❏ Application-specific menus
- May contain menu bar extras determined by the user  
The ordering of application-specific menus in the menu bar should reflect the natural hierarchy of objects in your application. Examine the user's mental model of the tasks your application performs to help you determine what this natural hierarchy is (see ["Reflect](#page-39-0) the User's Mental Model" (page 40) for more information on discovering the user's mental model). For example, if your application helps users create computer animation, the application-specific menus might be Scenes, Characters, Backgrounds, and Projects. Because a user probablysees the project as a high-level entitythat contains scenes, each of which contains backgrounds and characters, a natural ordering of these menus is Projects, Scenes, Backgrounds, and Characters.  
<span id="page-159-0"></span>In general, place the menus that display commands to handle higher-level, more universal objects toward the left of the menu bar and the menus that focus on the more specific entities toward the right.  
**Figure 12-12** The menu bar displayed when the Finder is active  
![](images/_page_159_Picture_7.jpeg)  
If there is insufficient room to display all of an application's menus, the menu bar status items are omitted. If there is still insufficientroom to displayall menus, the application's menus maybe omitted, starting with the rightmost menu.  
<span id="page-159-1"></span>If your application can display full-screen images (such as slideshows), you may allow users to hide the menu bar. If you implement this feature, provide a clearly visible way, such as a button, for the user to make the menu bar reappear. If there is no button visible, pressing the Escape key or moving the mouse to the top of the screen should display the menu bar.  
A menu's title is displayed undimmed even if all of the menu's commands are unavailable (dimmed) at the same time. Users should always be able to view a menu's contents, whether or not they are currently available.  
<span id="page-160-1"></span>**Figure 12-13** A menu title is undimmed, even when all items are unavailable  
![](images/_page_160_Picture_3.jpeg)  
**Carbon:** See *Menu Manager Reference* in Carbon User Experience Documentation.  
**Cocoa:** See *Application Menu and Pop-up List Programming Topics* in Cocoa User Experience Documentation.  
The following sections discuss the individual menus in the menu bar. The sections are listed in the orderthat the menus should appearin the menu bar. With the exceptions of the Apple menu (provided by the system), the application menu, and the Window menu, all other menus are optional.  
Within each section, a checkmark ( ) next to a menu item indicates that unless your application cannot support the item's action or attribute, the item is required. The unmarked commands are ones that are not appropriate for all applications, but if theyare appropriate in yours,you should implement and label them as discussed.  
<span id="page-160-0"></span>If there is an appropriate keyboard shortcut for a menu item, it is listed. Except for those items with a checkmark next to them, you should implement keyboard shortcuts only for those commands that will be frequently used. Unnecessary use ofkeyboard shortcuts can makeyour application confusing. For more discussion on assigning keyboard shortcuts for pull-down menu items, see ["Keyboard](#page-97-0) [Shortcuts"](#page-97-0) (page 98).