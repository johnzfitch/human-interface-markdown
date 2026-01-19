---
chunk_index: 2757
ref: "935fe3abe277"
id: "935fe3abe277acd73434c04be13257f0741f35fdf3d9e47f203d38993856a2a3"
slug: "full-document--scroll-bars"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2612, 2665]
token_estimate: 1180
content_sha256: "a14834365bf59fb45b4373b7945a6ae6cee3611a71b74ea592dfda1841963565"
compacted: false
heading_path: ["Window Behaviors","Scrolling a Window","Scroll Bars"]
symbol: null
address: null
asset_path: null
---

#### Scroll Bars

A **scroll bar** is a light gray rectangle that has an arrow in a box at each end of the rectangle. Windows can have a horizontal scroll bar, a vertical scroll bar, or both. A vertical scroll bar appears on the right side of the associated window. A horizontal scroll bar runs along the bottom of the window. Inside the scroll bar is a rectangle called the **scroll box.** At either end of the scroll bar is an arrow that points towards the portion of a document still hidden from view; clicking the arrow displays more of the document by scrolling it into view. The rest of the scroll bar is called the *gray area.* Figure 5-28 shows the elements of a scroll bar.

**Figure 5-28** The elements of a scroll bar

![](images/_page_182_Picture_3.jpeg)

A scroll bar represents one dimension, top to bottom or right to left, of the entire document. The scroll box represents the relative location, in the whole document, of the portion that can be seen in the window.

If the user clicks a scroll arrow or clicks in the gray area, the document "moves" and the scroll box moves along with it. If the user drags the scroll box and releases the mouse button, the document "moves" along with it. Figure 5-29 illustrates these behaviors.

**Figure 5-29** Using scroll arrows and the scroll box

![](images/_page_182_Picture_7.jpeg)

Window Behaviors **159**

If the document is no larger than the window, the scroll bars are inactive. This means that the rectangles are outlined, but there is no gray area, no scroll box, and the arrows are hollow (their outlines appear). If the document window is inactive, don't show the elements of the scroll bar at all; only the outline of the scroll bar as a whole should appear. Figure 5-30 shows an *active* document window with inactive scroll bars and an *inactive* document window with inactive scroll bars.

**Figure 5-30** Inactive scroll bars in active and inactive document windows

![](images/_page_183_Picture_4.jpeg)

![](images/_page_183_Picture_6.jpeg)

If a document has a fixed size that is smaller than the maximum size of the window, and the user scrolls to the right or bottom edge of the document, your application can display a gray background between the edge of the document and the window frame. This background indicates to the user that the content area has a fixed size that is smaller than the maximum size of the window. Figure 5-31 shows an example of a document with this gray background.

**Figure 5-31** Background between the content and the window frame

![](images/_page_184_Picture_3.jpeg)

![](images/_page_184_Picture_4.jpeg)

Many applications add features like controls to windows in the scroll bar region. Since the scroll bars are used frequently, it's best not to add lots of additional controls to this area of the window. Generally it's best to minimize the complexity of your application's interface and use the established graphical language. It's OK to add one control, like a split bar, which allows users to split a window into panels, to the top of the vertical scroll bar. But if you add more than one control to this area, it's hard for people to distinguish controls, and to click exactly the desired control. Also from an implementation standpoint, it's difficult to design small symbols and pictures that effectively convey the action of the control.

Another addition to the window that's not too intrusive is a status bar at the left side of the horizontal scroll bar. This bar doesn't take up much space, while providing useful information to the user. It also doesn't reduce the working size of the scroll bar by too much.

Window Behaviors **161**

Figure 5-32 shows scroll bars with acceptable additions; the horizontal scroll bar has a page indicator and the vertical scroll bar has a split bar.

**Figure 5-32** Acceptable additions to the scroll bar region

![](images/_page_185_Picture_4.jpeg)

Some applications include a page number inside the scroll box to indicate the position of the document. This allows the user to see the page number change as the document scrolls. It also provides information without adding complexity to the window.

To ensure that the controls that you include in the window are easy to use and understand, it's best to place the majority of your features in the menus as commands. Figure 5-33 shows a window with too many controls in the scroll bars. If you really want to provide additional access to features, consider creating a utility window such as a palette with buttons. For more information on palettes, see "Tear-Off Menus and Palettes" on page 92 in Chapter 4, "Menus."

**Figure 5-33** Too many controls in the scroll bar

![](images/_page_185_Picture_8.jpeg)