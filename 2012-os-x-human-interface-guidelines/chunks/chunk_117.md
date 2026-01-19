<!-- Chunk 117 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 1017 -->
People scroll to view content that is larger than can fit in the current window. Scroll bars are not persistently visible by default.  
In general, scroll bars appear when users:  
- Open or resize a window that contains scrolling content
- Open content within a window that is too small to display all of the content at once
- Place two fingers on a trackpad or mouse surface
- Actively scroll content  
In all of these cases, scroll bars appear briefly and then disappear shortly after users stop interacting with the window or the content. This behavior helps users see that the content exceeds the size of the window body, without requiring the scroll bar to occupy valuable space in the content area.  
**Important:** Users can choose to make scroll bars visible all the time by changing the "Show scroll bars" setting in General preferences. A persistently visible scroll bar has a width of 15 points, which extends into the content area of a window.  
An app that was developed to run in an earlier version of OS X might display legacy scroll bars when it runs in OS X. In addition, an app that includes a placard or a control inline with the scroll bar area also displays legacy scroll bars.  
Finally, scroll bars can be persistently visible if there is a connected pointing device that doesn't support scrolling.  
To learn how to use scroll bars in your app, see ["Enabling](#page-183-0) Scrolling" (page 184).  
For example, you can see the scroll track of the horizontal scroll bar in the Safari window shown here, because it was recently resized.  
![](images/_page_172_Picture_6.jpeg)  
The **scroller** size (relative to the length of the track) reflects how much of the content is visible. For example, a small scroller means that a small fraction of the total content is currently visible. The scroller also represents the relative location, in the whole document, of the portion that can be seen in the window.  
Users scroll content in a window by doing one of the following:  
- Scrolling on a trackpad. This is an easy, natural gesture that strengthens the user's sense of direct manipulation (to learn about the principle of direct manipulation, see "Direct [Manipulation"](#page-29-0) (page 30)). Note that users can also specify whether the content should move in the same direction that their fingers move in, or in the opposite direction.
- Rolling the scroll ball on a mouse. Users can adjust how fast or slow scrolling occurs in Mouse preferences.  
- Dragging the scroller. This method can be the fastest way to move around a large document. The window's contents changes in "real time" as the user drags the scroller.
- When a scroll bar is currently invisible, users must cause it to appear before they can drag the scroller. After a scroller appears, it remains visible for a few seconds so that users have a chance to interact with it.
- Clicking or pressing in the scroll track. Clicking moves the document by a windowful (the default) or to the pointer's hot spot, depending on the user's choice in General preferences. A "windowful" is the height or width of the window, minus at least one unit of overlap to maintain the user's context. The Page Up and Page Down keys also move the document view by a windowful.
- Pressing in the scroll track displays consecutive windowfuls of the document until the location of the scroller catches up to the location of the pointer (or until the user stops pressing).  
When a scroll bar is currently invisible, users must cause it to appear before they can click or press in the scroll track. There is a delay between the appearance and disappearance of the scroll bar, so that users have time to interact with the scroll track.  
<span id="page-173-0"></span>Most of the time, the user controls scrolling. But sometimes, scrolling happens automatically while the user is performing a different task, such as extending a selection past the edge of a window. To learn when your app should support this action, known as **automatic scrolling**, see ["Enabling](#page-183-0) Scrolling" (page 184).