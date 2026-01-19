<!-- Chunk 135 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 527 -->
Windows have two distinct looks in Mac OS X. There is the standard default look of windows, as shown in the examples so far. There is also a brushed metal look available, shown in Figure 8-11. You can use a brushed metal window if your application:  
- Provides an interface for a digital peripheral, such as a camera, or an interface for managing data shared with digital peripherals—iPhoto or iSync, for example
- Strives to re-create a familiar physical device—Calculator or DVD Player, for example
- Provides a source list to navigate information—for example, iTunes or the Finder  
Don't use the brushed metal look indiscriminately. Although it works well for some types of applications, some applications appear too heavy when using this look. For example, it works well for the iSync application window (see Figure 8-11), but it does not work very well for the TextEdit document window (see Figure 8-12).  
<span id="page-111-0"></span>**Figure 8-11** A brushed metal application window  
![](images/_page_111_Picture_3.jpeg)  
**Figure 8-12** Metal and regular versions of a document window  
<span id="page-111-1"></span>![](images/_page_111_Figure_5.jpeg)  
Use brushed metal window look for the primary application window and other windows that meet the above criteria—for example, the Equalizer window in iTunes. Don't use it for supporting windows, such as preferences and other dialogs. It is acceptable to have a mix of standard Aqua windows and brushed metal windows within an application, as the Finder does.  
<span id="page-112-2"></span>**Figure 8-13** Mixing standard and brushed metal versions of windows  
![](images/_page_112_Picture_3.jpeg)  
If a brushed metal window has a drawer or a toolbar, it automatically inherits the brushed metal look.  
<span id="page-112-4"></span>Users can move metal windows by dragging anywhere on the brushed metal surface (not just the title bar).  
**Carbon:** Use the window type defined in MacWindows.h.  
**Cocoa:** Apply the NSTexturedBackgroundWindowMask to a titled window. Avoid using a borderless window, which doesn't have rounded corners.