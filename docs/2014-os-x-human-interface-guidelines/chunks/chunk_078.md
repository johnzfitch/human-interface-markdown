<!-- Chunk 78 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 967 -->
A window consists of window-frame areas and a window body. The **window-frame areas** are the title bar and toolbar, which are typically combined. (In rare cases, a window might also have a bottom bar, which is a window-frame area that appears at the bottom edge of the window.) The **window body** can extend from the top edge of the window (that is, underneath the combined title bar/toolbar area) to the bottom edge of the window.  
The window body represents the main **content area** of the window. For example, in a Mail message viewer window, the window body contains the mailbox list, the message list, and the selected message.  
![](images/_page_118_Figure_2.jpeg)  
OS X defines appearancesthat can affect the look of controls and viewsin particular contexts,such as a window's sidebar. For example, the Mail window shown here uses the vibrant light appearance in the sidebar area. To learn more about this appearance, see NSAppearanceNameVibrantLight.  
The Mail sidebar uses a "behind window" blending mode, which brings colors from the content behind the window into the sidebar. In contrast, the toolbar uses an "in window" blend mode, which means that content within the window can blend with content in the toolbar. To learn more about these blending modes, see NSVisualEffectBlendingMode.  
OS X specifies a set of control/style combinations that are designed to look good on the toolbar, whether the toolbar is translucent or opaque. You can learn more about these controls in Some [Controls](#page-176-1) Can Be Used in the [Window](#page-176-1) Frame (page 177). OS X also defines system colors that are designed to look good on the system-provided appearances. You can learn about these colorsin Use System [Colorsto](#page-38-1) Work Well With System [Appearances](#page-38-1) (page 39).  
Every document window, app window, and panel has, at a minimum:  
- A title bar (or a combined title bar and toolbar), so that users can move the window.
- A close button, so that users have a consistent way to dismiss the window.  
A standard document window may also have the following additional elements that an app window or panel might not have:  
- Transient horizontal or vertical scroll bars, or both (if not all the window's contents are visible)
- Minimize and fullscreen buttons (note that the fullscreen button changes to a zoom button if the window doesn't support fullscreen mode or when users hold down the Option key)
- A proxy icon and a versions menu (after the user has given a document a name and save location for the first time)
- The title of the document (that functions as the title of the window)
- Transient resize controls  
For example, the TextEdit document window shown here contains a title, a proxy icon, the close, minimize, and fullscreen buttons, and the title bar Versions menu. You can'tsee the resize controlsin this window, because they are visible only when the pointer rests above a window edge. Similarly, the only part of the Versions menu that's visible in this window is the disclosure control that's to the right of the document title.  
![](images/_page_120_Figure_2.jpeg)  
The TextEdit window shown above also includes an optional window element called the scope bar. A **scope bar** appears below the toolbar and allows users to narrow down a search operation or to filter objects or other operations by identifying specific sets of characteristics. To learn more about scope bars, see [Searching](#page-130-0) In a [Window](#page-130-0) (page 131).  
Rarely, a window displays a **bottom bar**, which is a window frame area that appears below the main content area of the window body. A bottom bar contains controls that directly affect the contents and organization of the window, such as the "Add a buddy" and chat controls at the bottom of the Messages window.  
![](images/_page_121_Picture_2.jpeg)