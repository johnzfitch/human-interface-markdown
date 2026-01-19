<!-- Chunk 49 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 895 -->
Some applications can keep several windows on the desktop at the same time. Each window is in <sup>a</sup> different plane. Windows can be moved around on the desktop much as pieces of paper can be moved around on a real desktop. Each window overlaps those behind it and is overlapped by those in front of it. Even when windows don't overlap, they retain their front-to-back ordering.  
Each application may deal with the meaning and creation of multiple windows in its own way. Different windows can represent  
- separate documents being viewed or edited simultaneously
- related parts of a logical whole (such as the listing, execution, and debugging of a program)
- different views of the same information (such as a spreadsheet and a graph that represent the same number  
The disadvantage of multiple windows isthat the desktop can become cluttered. Some applications provide, in the menu bar, <sup>a</sup> Windows menu. This menu allows the user to quickly choose <sup>a</sup> window even though it may be out of sight under other windows.  
Figure 3-4 illustrates multiple windows.  
![](images/_page_57_Picture_8.jpeg)  
Figure 3-4 Multiple windows  
#### The active window  
Although several windows can be open on the desktop at the same time, the user can work in only one window at a time. This window is called the **active window**. All other open windows are **inactive**. Things can be happening to documents in inactive windows, but only the active window can be manipulated directly. For example, if the user chooses Close from the File menu, only the active window is closed.  
To make a window active, the user clicks anywhere inside it. Making a window active has two immediate consequences:  
- ☐ The window changes its appearance: its title bar is striped and the scroll bars, close box, zoom box, and size box appear.
- ☐ The window "moves" to the frontmost plane, so that parts that had been covered by other windows become visible.  
Clicking in an inactive window activates it, but makes no other changes. To make a selection within the window, the user must click again. When the user clicks in a window that has been deactivated, the window should be reinstated just the way it was when it was deactivated, with the scroll box in the same position and the same selection highlighted.  
When a window becomes inactive, the visual changes that took place when it was activated are reversed. The title bar is no longer striped and the scroll bars, close box, zoom box, and size box disappear. Although the information within the window remains visible (except where obscured by other windows), any selection is deselected. Figure 3-4 shows the visual difference between active and inactive windows.  
#### Moving a window  
Although each application has its own way of initially placing windows on the screen, the user can move an active window—to make more room on the desktop or to uncover a window it's overlapping—simply by dragging it by its title bar. A dotted outline of the window follows the pointer until the user releases the mouse button. At the release of the button the full window is redrawn in its new location. Moving a window doesn't affect the appearance of the icons or document within the window; they move right along with the window.  
The act of moving an inactive window makes it active—unless the user holds down the Apple key while moving the inactive window, in which case the window moves, in the same plane, without becoming active.  
The application should ensure that a window can never be moved completely off the screen.