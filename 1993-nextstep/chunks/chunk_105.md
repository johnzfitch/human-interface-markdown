<!-- Chunk 105 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 698 -->
In general, ordinary panels are unobtrusive. They're in the lowest tier on-screen, and they disappear when their application is deactivated. Sometimes, though, an ordinary panel needs to be more prominent, as described in the following sections.  
#### **Persisting Panels**  
By default, an ordinary panel is removed from the screen when its application is deactivated. The user sees only panels related to the active application. This prevents confusion-such as might arise when similar Find panels for two different applications are on-screen at once.  
An application can override this default behavior and allow a panel to remain on-screen after the application has been deactivated, but only if the panel contains information that would be pertinent to the user's activities in another application. This should be a rare occurrence.  
An example is the Workspace Manager Info panel, which contains system-level information such as the amount of memory in the computer. Because the user might want to copy this information down-for example, into a mail message-this panel persists even when the Workspace Manager is deactivated.  
#### **Floating Panels**  
Ordinary panels are normally in the same tier as standard windows. Sometimes, though, it's useful to have a panel float above all other standard windows and ordinary panels. For example, a small panel containing a palette of drawing tools is most useful if it floats above the application's other windows. An example of a palette is below.  
![](images/_page_93_Picture_2.jpeg)  
A panel should be allowed to float above standard windows only if it passes all four of the following tests:  
- It's oriented to the mouse rather than the keyboard. Thus a panel that can become the key window should not be made a floating panel, unless it becomes the key window only when the user is ready to type (see "Becoming the Key Window" earlier in this chapter).
- It's important that the panel remain visible while the user works in the application's standard windows. This test is passed if the user must frequently move the cursor from a standard window to the panel and back again (as for a tool palette) or the panel gives information relevant to the user's actions in the standard window (as in some inspector panels).
- It's small enough not to obscure much of what's behind it.
- It doesn't persist (remain on-screen) when the application is deactivated.  
Thus, panels float for some of the same reasons that menus do.  
#### **Panels with Variable Contents**  
Two types of ordinary panels—multiform panels and inspector panels—are used in many applications to show specialized information in a limited amount of space. Both multiform and inspector panels can be used for many different purposes, even within the same application.