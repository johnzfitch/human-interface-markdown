<!-- Chunk 181 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 583 -->
Mac OS X supports 32-bit RGBA pointers in sizes up to 64 x 64 pixels. If you need a pointer larger than that, you can implement it as a window that tracks with the pointer.  
Before you design your own pointer, ask yourself if it is going to add value to the user interface. Recognize that by doing so you are introducing a new, potentially confusing user interface element. If you decide you really need a new pointer, keep the following in mind:  
- You need to indicate where the hot spot of the pointer is.
- Your pointers need to be able to work on older hardware that may not provide hardware video acceleration.
- If you create a custom version of a standard pointer, you need to also create new versions of related pointers. For example, if you create a larger arrow pointer you need to also create custom pointers for copy, move, alias, poof, and so forth.  
If creating a custom pointer is necessary, both Cocoa and Carbon applicationsshould use NSCursor methods to do so.  
#### **CHAPTER 12**  
Pointers  
<span id="page-164-5"></span><span id="page-164-4"></span><span id="page-164-0"></span>Menus present lists of items—commands, attributes, or states—from which the user can choose. Menus are based on the interface principle of see and point: People don't have to remember commands or options because they can view all options at any time.  
Menus are user interface elements that users refer to frequently, especially when they are seeking a function for which they know of no other interface. Ensuring that menus are correctly organized, are worded clearly, and behave correctly is crucial to the user's ability to explore and accessthe functionality of your applications.  
<span id="page-164-2"></span>Menus appear in several different forms in the Mac OS X interface. This chapter describes pull-down menus in the menu bar, Dock menus, and contextual menus. These types of menus are illustrated in Figure 13-1.  
**Figure 13-1** Menu bar, Dock, and contextual menus  
![](images/_page_164_Picture_6.jpeg)  
<span id="page-164-1"></span>Menus that are part of controls—for example, pop-up menus, command pop-down menus, and the menus in pop-up icon buttons and bevel buttons—are discussed in ["Controls"](#page-254-0) (page 255). Note that some concepts from this chapter are applicable to those menu types as well.