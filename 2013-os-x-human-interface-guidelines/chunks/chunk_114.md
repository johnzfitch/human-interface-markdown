<!-- Chunk 114 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 1788 -->
A window consists of window-frame areas and a window body. The **window-frame areas** are the title bar and unified toolbar (and, in rare cases, a bottom bar). The **window body** extends from the bottom edge of the title bar (or toolbar, if present) to the bottom edge of the window (not including the bottom bar, if one is present). The window body represents the main **content area** of the window. For example, in a Mail message viewer window, the window body contains the mailbox list, the message list, and the selected message.  
![](images/_page_166_Picture_4.jpeg)  
The window-frame areas have a light gray gradient surface. OS X provides toolbar controls that are specifically designed to look good on the toolbar. To learn about the controls you can use in a toolbar,see ["Window-Frame](#page-237-0) [Controls"](#page-237-0) (page 238).  
In the window body, content views (such as text or column views) display a white background by default; the surrounding window-body background is usually a shade of light gray.  
#### <span id="page-167-0"></span>Window Components  
Every document and app window and panel has, at a minimum:  
- A title bar. Even if a window does not have an actual title (a tools panel, for example), it needs a title bar so that users can move the window.
- A close button, so that users have a consistent way to dismiss the window.  
A standard document window may also have the following additional elements that an app window or panel might not have:  
- Transient horizontal or vertical scroll bars, or both (if not all the window's contents are visible)
- Minimize and zoom buttons
- A proxy icon and a versions menu (after the user has given a document a name and save location for the first time)
- The title of the document
- Transient resize controls  
For example, the TextEdit document window shown here contains a title, a proxy icon, the close, minimize, and zoom buttons, and a scroller. You can't see the resize controls in this window, because they are visible only when the pointer rests above a window edge. Similarly, you can't see the versions menu because the document is not locked (and has not been recently edited) and the pointer is not resting in the title bar to the right of the document title.  
![](images/_page_168_Picture_2.jpeg)  
The TextEdit window shown above also includes an optional window element called the scope bar. A **scope bar** appears below the toolbar and allows users to narrow down a search operation or to filter objects or other operations by identifying specific sets of characteristics. To learn more about scope bars, see ["Using](#page-184-0) a Scope Bar to Enable [Searching](#page-184-0) and Filtering" (page 185).  
Rarely, a window might display a **bottom bar**, which is a window frame area that extends below the main content area of the window body. A bottom bar contains controls that directly affect the contents and organization of the window, such as the add a buddy and chat controls at the bottom of the iChat window.  
![](images/_page_169_Picture_2.jpeg)  
#### <span id="page-169-0"></span>Scrolling  
People scroll to view content that is larger than can fit in the current window. Scroll bars are not persistently visible by default.  
In general, scroll bars can appear when users:  
- Open or resize a window that contains scrolling content
- Open content within a window that is too small to display all of the content at once
- Place two fingers on a trackpad or mouse surface
- Actively scroll content  
In all of these cases, scroll bars appear briefly and then disappear shortly after users stop interacting with the window or the content. This behavior helps users see that the content exceeds the size of the window body, without requiring the scroll bar to occupy valuable space in the content area.  
**Important:** Users can choose to make scroll bars visible all the time by changing the "Show scroll bars" setting in General preferences. A persistently visible scroll bar has a width of 15 points, which extends into the content area of a window.  
An app that was developed to run in an earlier version of OS X might display legacy scroll bars when it runs in OS X. In addition, an app that includes a placard or a control inline with the scroll bar area also displays legacy scroll bars.  
Finally, scroll bars can be persistently visible if there is a connected pointing device that doesn't support scrolling.  
To learn how to use scroll bars in your app, see ["Enabling](#page-181-0) Scrolling" (page 182).  
For example, you can see the scrollers in the Safari window shown here, because it was recently resized.  
![](images/_page_170_Picture_6.jpeg)  
The **scroller** size (relative to the length of the track) reflects how much of the content is visible. For example, a small scroller means that a small fraction of the total content is currently visible. The scroller also represents the relative location, in the whole document, of the portion that can be seen in the window.  
Users scroll content in a window by doing one of the following:  
- Scrolling on a trackpad. This is an easy, natural gesture that strengthens the user's sense of direct manipulation (to learn about the principle of direct manipulation, see "Direct [Manipulation"](#page-29-0) (page 30)). Note that users can also specify whether the content should move in the same direction that their fingers move in, or in the opposite direction.
- Rolling the scroll ball on a mouse. Users can adjust how fast or slow scrolling occurs in Mouse preferences.  
- Dragging the scroller. This method can be the fastest way to move around a large document. The window's contents changes in "real time" as the user drags the scroller.
- When a scroll bar is currently invisible, users must cause it to appear before they can drag the scroller. After a scroller appears, it remains visible for a few seconds so that users have a chance to interact with it.
- Clicking or pressing in the scroll track. Clicking moves the document by a windowful (the default) or to the pointer's hot spot, depending on the user's choice in General preferences. A "windowful" is the height or width of the window, minus at least one unit of overlap to maintain the user's context. The Page Up and Page Down keys also move the document view by a windowful.
- Pressing in the scroll track displays consecutive windowfuls of the document until the location of the scroller catches up to the location of the pointer (or until the user stops pressing).  
When a scroll bar is currently invisible, users must cause it to appear before they can click or press in the scroll track. There is a delay between the appearance and disappearance of the scroll bar, so that users have time to interact with the scroll track.  
<span id="page-171-0"></span>Most of the time, the user controls scrolling. But sometimes, scrolling happens automatically while the user is performing a different task, such as extending a selection past the edge of a window. To learn when your app should support this action, known as **automatic scrolling**, see ["Enabling](#page-181-0) Scrolling" (page 182).