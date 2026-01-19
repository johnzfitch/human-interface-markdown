---
chunk_index: 2320
ref: "82d6f8171e88"
id: "82d6f8171e88d519a1284f225576c6a4a34d1ffa30b8597c1b27c474c28b8d1b"
slug: "chunk-121--the-default-position-on-a-single-screen"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_121.md"
kind: "markdown"
lines: [4, 13]
token_estimate: 443
content_sha256: "0552ccb9f8936ca970910954618b349710a66720d88a1e96fd3ba7600b5a7b28"
compacted: false
heading_path: ["The Default Position on a Single Screen"]
symbol: null
address: null
asset_path: null
---

#### The Default Position on a Single Screen  
When your application opens a new document window, position it in the upper-left corner of the screen. Open each additional new document window below and to the right of its predecessor. Figure 5-15 shows windows positioned on a single screen.  
**Figure 5-15** Window positions on a single screen  
![](images/_page_170_Picture_6.jpeg)  
Before closing a window, check to see whether the user has changed its size or position. Save window positions, and reopen windows in the size and position in which the user left them. If a user opens, moves, and closes a document window without making any other changes, save the new window position but don't modify the date stamp of the document. If the user does not change the size or position of the window, don't save the position when the user closes the window.  
Before reopening a window, check to make sure that the size and state are reasonable for the user's current monitor or monitors, which may not be the same as the monitor on which the document was last open. For example, a user might start working on a word-processing document on a full-page display at work and then take the document home and work on it on a computer with a 13-inch monitor. In a situation like this, your application should open the document in a window sized appropriately for the smaller monitor and not necessarily in the saved size. See the section "The Zoom Box and Window Behavior," beginning on page 168, for more information on appropriate window size.  
Window Behaviors **147**  
Figure 5-16 shows the standard position of a window on a 19-inch screen and a 13-inch screen.  
**Figure 5-16** The standard window position on two sizes of screens  
![](images/_page_171_Picture_4.jpeg)