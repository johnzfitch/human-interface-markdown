<!-- Chunk 297 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1089 -->
As described in ["Bottom](#page-211-0) Bars" (page 212), a bottom bar is a part of the window frame that extends below the content in the window body. Controls in a bottom bar are frequently used, but not as frequently used as controls in a toolbar. In addition, bottom-bar controls are closely related to the content in the view directly above them.  
To create a bottom bar using Interface Builder, drag a Window object from the Library (do not use a Textured Window object and do not change the window appearance to textured). From the Content Border pop-up menu in the Window Size inspector, choose:  
- Large Bottom Border, if you plan to use regular-size controls in the bottom bar
- Small Bottom Border, if you plan to use small controls in the bottom bar  
When you do this, Interface Builder creates a dark horizontal line that separates the bottom bar from the window's content area and gives you the appropriate, light-colored gradient in the bottom bar. You can see examples of this appearance in Mac OS X applications, such as the Finder and iCal.  
The layout guidelinesfor bottom barsfocus on visual balance and consistentspacing. Note that the guidelines for both regular-size and small controls recommend fewer pixels above the control than below it. This is because precisely centering controlsin a bottom bar makesthem too close to the bottom edge and decreases the sense of visual balance.  
<span id="page-364-1"></span>If you want to use regular-size controls in a bottom bar, use the following layout guidelines (illustrated in Figure 16-25):  
**Figure 16-25** Layout specifications for a bottom bar with regular-size controls  
![](images/_page_364_Picture_11.jpeg)  
- Leave a 4-pixel space between the dark separating line and the tops of the controls. (Note that this measurement does not include either the dark line or the top edge of the controls.)
- Leave a consistent amount of space between individual controls or sets of controls. (The bottom bar in Figure 16-25 uses 8 pixels between controls.)
- Leave a margin between the left edge of the bottom bar and the leftmost control. It works well to leave a margin that measures the same as the space you leave between controls (the bottom bar in Figure 16-25 uses 8 pixels in this area).  
- Place the baseline of the text 19 pixels below the dark separating line. (Note that this measurement includes the text baseline, but does not include the dark separating line.) Be sure to use small system font for the text.
- Another way to measure this is to turn on layout rectangles in Interface Builder (choose Layout > Show Layout Rectangles), select the text label, and press Option as you move the pointer over the label. The measurement displayed between the bottom edge of the label's layout rectangle and the bottom edge of the bottom bar should be 6 pixels.
- If the window contains a source list and there are controls that relate to the content view controlled by the source list, left-align those controls with the splitter of the source list.  
<span id="page-365-0"></span>If you want to use small controls in a bottom bar, use the following layout guidelines (illustrated in Figure 16-26):  
**Figure 16-26** Layout specifications for a bottom bar with small controls  
![](images/_page_365_Figure_7.jpeg)  
- Leave a 2-pixel space between the dark separating line and the top of the controls. (Note that this measurement does not include either the dark line or the top edge of the controls.)
- Place the leftmost control 8 pixels from the left edge of the bottom bar.
- Leave 8 pixels between controls.
- Place the baseline of the text 14 pixels below the dark separating line. (Note that this measurement includes the text baseline, but does not include the dark separating line.) Be sure to use small system font for the text.  
Another way to measure this is to turn on layout rectangles in Interface Builder (choose Layout > Show Layout Rectangles), select the text label, and press Option as you move the pointer over the label. The measurement displayed between the bottom edge of the label's layout rectangle and the bottom edge of the bottom bar should be 1 pixel.  
● If the window contains a source list and there are controls that relate to the content view controlled by the source list, left-align those controls with the splitter of the source list.