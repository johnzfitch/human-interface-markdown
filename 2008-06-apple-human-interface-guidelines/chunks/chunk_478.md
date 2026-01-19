<!-- Chunk 478 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 814 -->
As described in ["Bottom](#page-206-0) Bars" (page 207), a bottom bar is a part of the window frame that extends below the content in the window body. Controls in a bottom bar are frequently used, but not as frequently used as controls in a toolbar. In addition, bottom-bar controls are closely related to the content in the view directly above them.  
To create a bottom bar, leave a strip of window frame below the content view in the window body. To do this using Interface Builder, select a Textured Window object from the Library. You need to use this object, not the Window object, because it displays the window-frame surface from top to bottom.  
Place the appropriate content view in the new window and size the content view so that its bottom edge does not reach the bottom edge of the window. (Note that windows do not expose any window-frame surface at the sides of the content view in Mac OS X v10.5 and later; see "Window [Appearance"](#page-187-0) (page 188) for more information.) The strip of window frame visible below the content view should be:  
- 32 pixels high, if you plan to use regular size controls
- 22 pixels high, if you plan to use small size controls  
The layout guidelinesfor bottom barsfocus on visual balance and consistentspacing. Note that the guidelines for both regular-size and small controls recommend fewer pixels above the control than below it. This is because precisely centering controlsin a bottom bar makesthem too close to the bottom edge and decreases the sense of visual balance.  
<span id="page-352-1"></span>If you want to use regular-size controls in a bottom bar, use the following layout guidelines (illustrated in Figure 16-23):  
**Figure 16-23** Layout specifications for a bottom bar with regular-size controls  
![](images/_page_352_Picture_11.jpeg)  
- All controls should be 3 pixels from the top edge of the bottom bar.
- Leave a consistent amount of space between individual controls or sets of controls. (The bottom bar in Figure 16-23 uses 8 pixels between controls.)
- Leave a margin between the left edge of the bottom bar and the leftmost control. It works well to leave a margin that measures the same as the space you leave between controls (the bottom bar in Figure 16-23 uses 8 pixels in this area).
- The text baseline should be 18 pixels below the top edge of the bottom bar.
- If the window contains a source list and there are controls that relate to the content view controlled by the source list, left-align those controls with the splitter of the source list.  
If you want to use small controls in a bottom bar, use the following layout guidelines (illustrated in Figure 16-24):  
<span id="page-353-0"></span>**Figure 16-24** Layout specifications for a bottom bar with small controls  
![](images/_page_353_Figure_4.jpeg)  
- All controls should be 1 pixel from the top edge of the bottom bar.
- Place the leftmost control 8 pixels from the left edge of the bottom bar.
- Leave 8 pixels between controls.
- The text baseline should be 13 pixels below the top edge of the bottom bar.
- If the window contains a source list and there are controls that relate to the content view controlled by the source list, left-align those controls with the splitter of the source list.