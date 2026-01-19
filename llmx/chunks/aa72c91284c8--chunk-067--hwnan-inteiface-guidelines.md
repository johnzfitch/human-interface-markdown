---
chunk_index: 774
ref: "aa72c91284c8"
id: "aa72c91284c83a74a48dc22956c146ef66d083df8370fc6e54f05b13326f1d34"
slug: "chunk-067--hwnan-inteiface-guidelines"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_067.md"
kind: "markdown"
lines: [20, 34]
token_estimate: 588
content_sha256: "5fd6e342dae0460e4807340ec7667bed1d26bb9d79f1516d9bd4a3dce5aa0ab2"
compacted: false
heading_path: ["Moving a Window","Changing the Size of a Window","Window Zooming","*Hwnan Inteiface Guidelines*"]
symbol: null
address: null
asset_path: null
---

#### *Hwnan Inteiface Guidelines*  
is not available on all Apple computers, application programs must check the ROM and, if the feature is not present, bypass it. Note also that window zooming does not involve the variable magnification you get with a zoom lens).  
Application developers are encouraged to use the zoom window function on systems that make it available. The application should neither modify the shape or interpretation of clicking on the zoom window box nor build additional icons in the title bar.  
![](images/_page_81_Picture_3.jpeg)  
![](images/_page_81_Picture_4.jpeg)  
Figure 40. Window in Standard State  
![](images/_page_82_Picture_1.jpeg)  
(  
(  
Figure 41. Window in User-Selected State  
The application detennines the standard state of the window. This is generally the full screen, or close to it, and should be the size and location best suited to working on the document. As often as they want, users can specify the user-selected state of the window, generally the size and location best suited to organizing the desktop so that documents can be found and selected.  
The application program supplies values for the size and location of the window's standard state as well as the initial values for the size and location of the user-selected state. The standard state should be the most useful size and location for normal operations within the program-usually the full screen. If the application doesn't supply a standard state, the full screen (minus a few border pixels) is assumed.  
The user can't change the standard size and location, but the application can change it within context. For example, a word processor might defme the standard size and location as wide enough to display a document whose width is specified in the Page Setup dialog. If the user invokes Page Setup to specify a wider or narrower document, the application might change the values for the standard size and location to reflect that change.  
Explicit dragging or resizing of the window is handled according to these guidelines, regardless of the presence or absence of the zoom window feature. The effect of dragging or resizing depends on the state of the window and the degree of movement. In the  
Macintosh computer, the user must drag or resize a window at least seven pixels to cause a change in the user-selected state.