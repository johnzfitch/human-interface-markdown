<!-- Chunk 38 | Source: 2000 Adopting the Aqua Interface.pdf | Est. Tokens: 322 -->
The Window menu (which is optional) provides a listing of open document window and provides keyboard shortcuts for minimizing windows and bringing an application's windows to the front. If you choose to implement the Window menu, you can add commands to show and hide auxiliary windows such as palettes and modeless dialogs.  
If an application uses a single window, it is not necessary to create a Window menu simply to provide the Minimize Window command; you can simply provide a minimize in the window's title bar and support for the Command-M keyboard equivalent.  
Menu Layout **35**  
**Figure 1-29** A Window menu  
![](images/_page_35_Picture_3.jpeg)  
The ordering of items in the Window menu is Minimize Window, <separator>, Bring All to Front, <separator>, followed by the window list. The Close Window menu item has been relocated to the File menu; it was previously located in the Window menu in the menu layout guidelines for Mac OS X Server.  
Every application has a Help menu, which is always the rightmost menu. The first item is the name of the application and the word "Help" (Mail Help, for example). As with Mac OS 8 and 9, you can add more items to the Help menu if needed. However, fewer choices are better and a single application help choice is the best approach.