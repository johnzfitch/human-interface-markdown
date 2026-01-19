<!-- Chunk 143 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 1698 -->
People use scroll bars to change which part of a document is shown in a window. Only the active window can be scrolled. This section describes the appearance and behavior of scroll bars and their controls. Figure 5-27 shows a conceptual view of a document and the portion of it that appears in a window.  
**Figure 5-27** Relationship between a window and a document  
![](images/_page_181_Picture_5.jpeg)  
#### Scroll Bars 5  
A **scroll bar** is a light gray rectangle that has an arrow in a box at each end of the rectangle. Windows can have a horizontal scroll bar, a vertical scroll bar, or both. A vertical scroll bar appears on the right side of the associated window. A horizontal scroll bar runs along the bottom of the window. Inside the scroll bar is a rectangle called the **scroll box.** At either end of the scroll bar is an arrow that points towards the portion of a document still hidden from view; clicking the arrow displays more of the document by scrolling it into view. The rest of the scroll bar is called the *gray area.* Figure 5-28 shows the elements of a scroll bar.  
**Figure 5-28** The elements of a scroll bar  
![](images/_page_182_Picture_5.jpeg)  
A scroll bar represents one dimension, top to bottom or right to left, of the entire document. The scroll box represents the relative location, in the whole document, of the portion that can be seen in the window.  
If the user clicks a scroll arrow or clicks in the gray area, the document "moves" and the scroll box moves along with it. If the user drags the scroll box and releases the mouse button, the document "moves" along with it. Figure 5-29 illustrates these behaviors.  
**Figure 5-29** Using scroll arrows and the scroll box  
![](images/_page_182_Picture_9.jpeg)  
Window Behaviors **159**  
<span id="page-183-0"></span>If the document is no larger than the window, the scroll bars are inactive. This means that the rectangles are outlined, but there is no gray area, no scroll box, and the arrows are hollow (their outlines appear). If the document window is inactive, don't show the elements of the scroll bar at all; only the outline of the scroll bar as a whole should appear. Figure 5-30 shows an *active* document window with inactive scroll bars and an *inactive* document window with inactive scroll bars.  
**Figure 5-30** Inactive scroll bars in active and inactive document windows  
![](images/_page_183_Picture_4.jpeg)  
Active window with inactive scroll bars  
![](images/_page_183_Picture_6.jpeg)  
Inactive window with inactive scroll bars  
If a document has a fixed size that is smaller than the maximum size of the window, and the user scrolls to the right or bottom edge of the document, your application can display a gray background between the edge of the document and the window frame. This background indicates to the user that the content area has a fixed size that is smaller than the maximum size of the window. Figure 5-31 shows an example of a document with this gray background.  
<span id="page-184-0"></span>**Figure 5-31** Background between the content and the window frame  
![](images/_page_184_Picture_5.jpeg)  
![](images/_page_184_Picture_6.jpeg)  
Many applications add features like controls to windows in the scroll bar region. Since the scroll bars are used frequently, it's best not to add lots of additional controls to this area of the window. Generally it's best to minimize the complexity of your application's interface and use the established graphical language. It's OK to add one control, like a split bar, which allows users to split a window into panels, to the top of the vertical scroll bar. But if you add more than one control to this area, it's hard for people to distinguish controls, and to click exactly the desired control. Also from an implementation standpoint, it's difficult to design small symbols and pictures that effectively convey the action of the control.  
Another addition to the window that's not too intrusive is a status bar at the left side of the horizontal scroll bar. This bar doesn't take up much space, while providing useful information to the user. It also doesn't reduce the working size of the scroll bar by too much.  
Window Behaviors **161**  
Figure 5-32 shows scroll bars with acceptable additions; the horizontal scroll bar has a page indicator and the vertical scroll bar has a split bar.  
<span id="page-185-0"></span>**Figure 5-32** Acceptable additions to the scroll bar region  
![](images/_page_185_Picture_4.jpeg)  
Some applications include a page number inside the scroll box to indicate the position of the document. This allows the user to see the page number change as the document scrolls. It also provides information without adding complexity to the window.  
To ensure that the controls that you include in the window are easy to use and understand, it's best to place the majority of your features in the menus as commands. Figure 5-33 shows a window with too many controls in the scroll bars. If you really want to provide additional access to features, consider creating a utility window such as a palette with buttons. For more information on palettes, see "Tear-Off Menus and Palettes" on page 92 in Chapter 4, "Menus."  
**Figure 5-33** Too many controls in the scroll bar  
![](images/_page_185_Picture_8.jpeg)  
#### <span id="page-186-0"></span>Scrolling With the Scroll Arrows 5  
When the user clicks or presses one of the scroll arrows, more of the document in the direction of the scroll arrow appears, so the document seems to move in the opposite direction. Clicking the arrow means, "Show me more of the document that's hidden in this direction." When the user clicks the bottom scroll arrow, for example, the document moves up, bringing what was just below the window into view. Pressing the scroll arrow causes continuous movement in the appropriate direction. Figure 5-34 shows the change in a document when a user scrolls by clicking a scroll arrow.  
**Figure 5-34** Scrolling by clicking a scroll arrow  
![](images/_page_186_Picture_7.jpeg)  
**1.**  
![](images/_page_186_Picture_9.jpeg)  
**2.**  
The scroll box moves in the direction of the arrow being clicked. It continues to represent the approximate position of the visible part of the document in comparison to the whole document.  
Each click in a scroll arrow causes movement of the content a distance of one unit in the chosen direction. Your application determines what one unit equals. For example, a word processor would move one line of text for each click in the arrow. A spreadsheet would move one row or one column depending on the direction of the arrow. To ensure smooth scrolling effects, it's usually best to specify units of the same size throughout a document.  
Window Behaviors **163**