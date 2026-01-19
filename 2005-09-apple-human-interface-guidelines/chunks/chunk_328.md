<!-- Chunk 328 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 461 -->
A **search field** is a text fieldwith rounded ends inwhich the user enters newtext or modifies existing text that identifies items to search for. For information on ways to provide search capability in your application, see ["Searching"](#page-60-1) (page 61).  
A search field can be active or disabled. It supports keyboard focus. If it is an integral part of your interface, provide thekeyboard shortcut Command-Option-Ffor users to navigate to itwithout using the mouse.  
Text Controls **259**  
A search field does not need a label.  
The field may initiate the search as the user types, or the user may need to press Return or Enter to initiate a search.  
A search field can include a menu to allow users to choose different types of searches, to allow users to define the context of their search, or to provide a history of recent searches. You can provide placeholdertext that indicates the current menu selection. Users are then able to see the current context of the search without having to open the menu.  
The search field can contain an icon to stop the search or clear the field. It's appropriate to use this icon if the user has to click a button or press a key to initiate the search, especially if there's the possibility of searches taking more than a second or two. If you use this icon, consider displaying a progress indicator for lengthy searches.  
Instead of providing multiple search fields, it's better to have a single search field in a window, with various contexts available from the pop-up menu.  
**Carbon:** Search fields are available in Interface Builder. To create one programmatically, use the function HISearchFieldCreate.  
**Cocoa:** Search fields are available in Interface Builder. To create one programmatically, use the NSSearchField class. See *Search Fields* in Cocoa User Experience Documentation.