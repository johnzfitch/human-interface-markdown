<!-- Chunk 304 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 1180 -->
<span id="page-354-2"></span>A tabbed window, like the one shown in Figure 16-5 follows the same general guidelines as those outlined in "A Simple [Preferences](#page-351-0) Window" (page 352). However, it illustrates anotherimplementation of many of the same basic guidelines you've seen so far, along with some new guidelines.  
**Figure 16-5** Tabbed window example  
![](images/_page_354_Picture_7.jpeg)  
Layout Guidelines  
Center-equalization is again evident in Figure 16-6. The overall effect of the window is a balance between the visual weight of the controls on one side of the invisible center axis with the weight of the controls on the other side. The controls are also collectively balanced within each group box so that the distance from the farthest control on each side of the group box is the same for both the right and left sides.  
<span id="page-355-0"></span>Also as shown in Figure 16-6, always center a tab view within a window.  
![](images/_page_355_Picture_4.jpeg)  
![](images/_page_355_Picture_5.jpeg)  
Figure 16-7 illustrates a few guidelines about control placement:  
- The colons for stacked labels are right-aligned.
- Stacked controls are left-aligned when appropriate.
- Similar controls have consistent widths. For example, the sizes of the Font pop-up menus and the Size combo boxes are the same in each group box.  
Control widths consistent Control widths consistent Left-align stacked items Right-align labels and label colons  
<span id="page-356-0"></span>**Figure 16-7** Example of alignment of labels and controls in a tabbed window  
Like the simple preferences window example in "A Simple [Preferences](#page-351-0) Window" (page 352), the tabbed window shown in this section uses white space in a consistent way. For example, in Figure 16-8, you can see:  
- Equal margins between the sides of the group boxes and the tab-pane side edges (the window in Figure 16-8 uses a 16-pixel margin in these areas).
- Equal margins between the sides and bottom of the tab pane and the window edges (the window in Figure 16-8 uses a 20-pixel margin in these areas).
- In both group boxes, the same amount of space between the bottom control and the lower edge of the group box, and the same amount of space between the top control and the upper edge of the group box. (The window in Figure 16-8 uses a 16-pixel margin between the bottom controls in each group box and the lower edge of the group box, and a 10-pixel margin between the top controls in each group box and the upper edge of the group box.)  
In addition, the window in Figure 16-8 uses a 12-pixel margin between the top of the tab bar to the bottom of the title bar (see "Tab [Views"](#page-341-0) (page 342) for more information about tab views). Note that this margin would be the same width if the window included a toolbar.  
<span id="page-357-1"></span>Figure 16-8 Example of layout of a tabbed window  
![](images/_page_357_Figure_3.jpeg)  
#### <span id="page-357-2"></span><span id="page-357-0"></span>A Standard Alert  
A standard alert is shown in Figure 16-9.  
Figure 16-9 A standard alert example  
![](images/_page_357_Picture_7.jpeg)  
Although the standard alerts take care of the general layout for you, there are a few details you are responsible for:  
- $\blacksquare$  Make sure that the application icon you use in the alert is 64 x 64 pixels.
- Make sure to include *both* the main message text and the informative text. An alert with only message text is not a complete alert and typically is not very useful to the user.
- Always put the action button in the bottom-right corner of the alert. This is the button that completes the action that the user initiated before the alert was displayed. Remember that the action button is not always the default button as it is in this example (the default button has color  
Layout Guidelines  
and pulses and receives a clickwhen the user presses Return or Enter). In situationswhere clicking the action button can have dangerous consequences (such as data loss) the default button can be Cancel, but when this is the case it should not be located in the action button position.  
Alerts look best when the margin at the bottom edge is the same height as in other windows (for example, in Figure 16-10, this margin is 20 pixels). In addition, you should ensure that there is an equal amount of space in the margins at the sides. The standard alert shown in Figure 16-10 uses a 24-pixel wide margin at the sides of the window.  
<span id="page-358-2"></span>See "The [Elements](#page-240-2) of an Alert" (page 241) for more details on designing alerts.  
**Figure 16-10** Layout dimensions for a standard alert  
![](images/_page_358_Picture_6.jpeg)