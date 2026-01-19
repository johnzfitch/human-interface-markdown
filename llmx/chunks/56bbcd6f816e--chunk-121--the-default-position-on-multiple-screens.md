---
chunk_index: 2321
ref: "56bbcd6f816e"
id: "56bbcd6f816eaae5f69c100ccc77aa7bc06da067a6bc66de8e699cfa7d3fe1a9"
slug: "chunk-121--the-default-position-on-multiple-screens"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_121.md"
kind: "markdown"
lines: [14, 24]
token_estimate: 475
content_sha256: "35bdefd7e3dd0f7096ef8dea22eeeb027063df670e44a9f0a16d8e2241ee95d5"
compacted: false
heading_path: ["The Default Position on a Single Screen","The Default Position on Multiple Screens"]
symbol: null
address: null
asset_path: null
---

#### The Default Position on Multiple Screens  
On computer systems with more than one monitor attached, display the first new window in the upper-left corner of the screen that contains the menu bar. If the user doesn't move that first window, display each additional window below and to the right of its predecessor. If the user moves the window, display each additional window on the screen that contains the largest portion of the frontmost window. If there is sufficient room on the screen, display the subsequent windows to the lower right of the frontmost window. If there isn't enough room on the screen, display subsequent windows starting in the upper-left corner on the screen (and then continue to display additional windows in relationship to this new position). For example, if the user creates a new window, drags it to a second screen, and then creates a second window, display this window and any subsequent windows on the second screen.  
Figure 5-17 shows the position in which to open a new window when the user has dragged its predecessor from the screen with the menu bar to a second screen.  
**Figure 5-17** The standard window position on multiple screens  
![](images/_page_172_Picture_4.jpeg)  
When you open several windows on multiple screens, continue to place the windows on the screen where the user is working, each new one below and to the right of its predecessor. The *initial position* of a window, however, must always be contained on a single screen. It would be awkward to have a window appear initially on screens of different display depths and resolutions. Of course, the user can choose to place a window in such a position.  
Window Behaviors **149**  
Figure 5-18 shows a window incorrectly displayed across two screens.  
**Figure 5-18** A window displayed across two screens  
![](images/_page_173_Picture_4.jpeg)  
![](images/_page_173_Picture_5.jpeg)