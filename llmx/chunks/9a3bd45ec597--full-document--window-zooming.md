---
chunk_index: 1936
ref: "9a3bd45ec597"
id: "9a3bd45ec597e5486a17d2db916310c4054e9623941c9aef62fd013676747d5e"
slug: "full-document--window-zooming"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [1182, 1205]
token_estimate: 704
content_sha256: "954f49df0762c131c52bfa22db4da3373f4231abe5630163e2982508c80dedf9"
compacted: false
heading_path: ["Window zooming"]
symbol: null
address: null
asset_path: null
---

# Window zooming

The more open documents on a desktop, the more difficult it is for the user to locate, select, and resize the one to be worked on. Some Apple computers have a feature in ROM that allows users—with <sup>a</sup> single mouse click in the window's zoom box—to drag and size the active window to a size and location they previously selected, and then to return the window to full size with another click. Figures 3-5 and 3-6 show <sup>a</sup> window in the standard state and in the user-selected state.

If this feature is present, the zoom box ispresent at the right end of the window's title bar (Figure 3-5). Because window zooming is not available on all Apple computers, application programs must check the ROM and, if the feature is not present, bypass it. (Window zooming does not involve the variable magnification you get with <sup>a</sup> zoom lens.)

Application developers are encouraged to use the zoom window function on systems that make it available.

![](images/_page_60_Picture_0.jpeg)

Figure 3-5 Window in standard state

![](images/_page_60_Picture_2.jpeg)

Figure 3-6 Iwindow In user-selected state

The application supplies the values for the size and location of the standard state of the window as well as the initial values for the size and location of the user-selected state. The standard state is generally the full screen, or close to it, and should be the size and location best suited to working on the document. As often as they want, users can specify the user-selected state of the window, generally the size and location best suited to organizing the desktop so that documents can be found and selected.

The user can't change the standard size and location, but the application can change itwithin context. For example, a word processor might define the standard size and location as wide enough to display a document whose width is specified in the Page Setup dialog box. If the user invokes Page Setup to specify a wider or narrower document, the application might change the values for the standard size and location to reflect that change.

Explicit dragging or resizing of the window is handled according to these guidelines, regardless of the presence or absence of the zoom window feature. The effect of dragging or resizing depends on the state of the window and the degree of movement. In the Macintosh computer, the user must drag or resize a window at least seven pixels to cause a change in the user-selected state.

Windows open into the user-selected state if possible. The application must make sure that the user-selected state fits on the current screen: if the window was previously on an alternate or large screen, and is then opened on a single or smaller screen, the application changes its size and location so the entire window is visible.