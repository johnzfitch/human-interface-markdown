---
chunk_index: 946
ref: "e9bd3857eca3"
id: "e9bd3857eca3cfc2983541c9304e2a41e49b0f1d1f91878e47667003e77a893e"
slug: "full-document--hwnan-inteiface-guidelines"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1799, 1828]
token_estimate: 584
content_sha256: "d512aa183d17710fab6169b605b07f6672f6c5c281e038000894d64303d0968b"
compacted: false
heading_path: ["Windows","The Active Window","Moving a Window","*Hwnan Inteiface Guidelines*"]
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