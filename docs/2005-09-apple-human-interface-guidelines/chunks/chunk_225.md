<!-- Chunk 225 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 703 -->
Windows have two distinct looks in Mac OS X. There is the standard default look of windows, as shown in most of the examples so far. There is also a brushed metal look available, shown in Figure 13-11.  
Don't use the brushed metal look indiscriminately. In particular, don't use the brushed metal appearance merely to make your application stand out. Instead, follow the design guidelines in ["The](#page-24-0) Design [Process"](#page-24-0) (page 25) and "Human [Interface](#page-30-0) Design" (page 31) to distinguish your application by reflecting the user's mental model.  
The brushed metal appearance works well for some types of applications, but most applications appear too heavy when using this look. For example, it works well for the iSync application window (shown in Figure 13-11), because iSync helps you manage your digital hub. On the other hand, the brushed metal look does not work well for the TextEdit document window (shown in Figure 13-12), because TextEdit is document-based.  
<span id="page-179-0"></span>**Figure 13-11** A brushed metal application window  
![](images/_page_179_Picture_3.jpeg)  
**Figure 13-12** Metal and regular versions of a document window  
<span id="page-179-1"></span>![](images/_page_179_Figure_5.jpeg)  
You can use a brushed metal window if your application:  
- Is a single-window application that provides a source list to navigate information—for example, iTunes or the Finder
- Strives to re-create a familiar physical device—Calculator or DVD Player, for example  
■ Provides an interface for a digital peripheral, such as a camera, or an interface for managing data shared with digital peripherals—iPhoto or iSync, for example  
You should not use a brushed metal window if your application:  
- Is a multi-window application—for example, Interface Builder
- Is a document-based application—for example, TextEdit  
Use the brushed metal window look for the primary application window and other windows that meet the above criteria—for example, the Equalizer window in iTunes. Don't use it for supporting windows, such as preferences and other dialogs. It is acceptable to have a mix of standard Aqua windows and brushed metal windows within an application, as the Finder does.  
<span id="page-180-0"></span>**Figure 13-13** Mixing standard and brushed metal versions of windows  
![](images/_page_180_Picture_8.jpeg)  
If a brushed metalwindowhas a drawer or a toolbar, it automaticallyinherits the brushed metal look.  
<span id="page-180-1"></span>Users can move metal windows by dragging anywhere on the brushed metal surface (not just the title bar).  
**Carbon:** Use the window type defined in MacWindows.h.  
**Cocoa:** Applythe NSTexturedBackgroundWindowMask to a titledwindow. Avoid usinga borderless window, which doesn't have rounded corners.