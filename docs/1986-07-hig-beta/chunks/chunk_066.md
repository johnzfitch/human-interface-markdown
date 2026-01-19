<!-- Chunk 66 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 885 -->
There are several kinds of windows: Document windows, dialog windows, and alert windows. Most of this section deals with document windows; dialogs and alerts are discussed together at the end of this section. Because controls appear only in windows, they are also discussed throughout this section.  
Each kind of window is made up of several parts, some of which are optional. The application determines the *content* of the window. This section is about a window's structural components (title bar, size box, close box, zoom box, and scroll bars).  
#### **Document Windows**  
Document indows are the areas on the screen where applications can display the information contained in a document. Because a document may contain more information than the window can display at one time, the window provides a view of a portion of a document. Document indows also provide a graphic representation of opening, closing, and other operations performed on documents. Windows are usually, but not necessarily, rectangles. Figure 38 shows a standard document window and its components.  
![](images/_page_77_Picture_7.jpeg)  
Figure 38. Standard Window  
#### Opening and Closing Windows  
Windows come up onto the screen in different ways as appropriate to the purpose of the window. The application controls at least the initial size and placement of its windows.  
A standard window has a close box. When the close box is clicked, the window goes away, accompanied by a visual cue such as animation showing the window shrinking into the folder or icon from which it was opened.  
The application in control of the window determines what's done with the window visually and logically when the close box is clicked. To the user's eye, a window, once closed, can seem either to retreat into an icon or to simply disappear. In reality, the information in the window may be saved (this is the usual case) and will still be there when the window is reopened, or the window is empty each time it's opened.  
When a document is closed, the user must have the choice whether to save any changes made to the document since the last time it was saved.  
If an application doesn't support closing a window with a close box, it shouldn't include a close box on the window.  
#### Multiple Windows  
Some applications can keep several windows on the desktop at the same time. Each window is in a different plane. Windows can be moved around on the desktop much as pieces of paper can be moved around on a real desktop. Each window can overlap those behind it and can be overlapped by those in front of it. Even when windows don't overlap, they retain their front-to-back ordering.  
Each application may deal with the meaning and creation of multiple windows in its own way. Different windows can represent:  
• separate documents being viewed or edited simultaneously  
• related parts of a logical whole (such as the listing, execution, and debugging of a program)  
• different views of the same information (such as a spreadsheet and a graph that represent the same numbers  
The advantage of multiple windows is that the user can isolate unrelated blocks of information. The disadvantage is that the desktop can become cluttered, especially if some of the windows can't be moved. Some applications provide, in the menu bar, a Windows menu. This menu allows the user to quickly choose a window even though it may be out of sight under other windows.  
Figure 37 illustrates multiple windows.  
![](images/_page_79_Picture_1.jpeg)  
Figure 37. Multiple Windows