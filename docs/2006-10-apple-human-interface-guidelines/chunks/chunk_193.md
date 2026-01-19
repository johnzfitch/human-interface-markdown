<!-- Chunk 193 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 575 -->
Mac OS X supports 32-bit RGBA cursors in sizes up to 64 x 64 pixels. If you need a cursor larger than that, you can implement it as a window that tracks with the cursor.  
Before you design your own cursor, ask yourself if it is going to add value to the user interface. Recognize that by doing so you are introducing a new, potentially confusing user interface element. If you decide you really need a new cursor, keep the following in mind:  
- You need to indicate where the hot spot of the cursor is.
- Your cursors need to be able to work on older hardware that may not provide hardware video acceleration.
- Ifyou create a custom version of a standard cursor,you need to also create newversions ofrelated cursors. For example, if you create a larger arrow cursor you need to also create custom cursors for copy, move, alias, poof, and so forth.  
**Carbon:** Not available.  
**Cocoa:** Use NSCursor methods to support a large, custom cursor.  
#### **C HAPTER 1 1**  
Cursors  
<span id="page-148-5"></span><span id="page-148-4"></span><span id="page-148-0"></span>Menus present lists of items—commands, attributes, or states—from which the user can choose. Menus are based on the interface principle of see and point: People don't have to remember commands or options because they can view all options at any time.  
Menus are user interface elements that users refer to frequently, especially when they are seeking a function for which they know of no other interface. Ensuring that menus are correctly organized, are worded clearly, and behave correctly is crucial to the user's ability to explore and access the functionality of your applications.  
<span id="page-148-2"></span>Menus appear in several different forms in the Mac OS X interface. This chapter describes pull-down menus in the menu bar, Dock menus, and contextual menus. These types of menus are illustrated in Figure 12-1.  
**Figure 12-1** Menu bar, Dock, and contextual menus  
![](images/_page_148_Picture_6.jpeg)  
<span id="page-148-1"></span>Menus that are part of controls—for example, pop-up menus, command pop-down menus, and the menus in pop-up icon buttons and bevel buttons—are discussed in ["Controls"](#page-230-0) (page 231). Note that some concepts from this chapter are applicable to those menu types as well.