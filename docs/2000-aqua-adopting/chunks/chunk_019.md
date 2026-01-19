<!-- Chunk 19 | Source: 2000 Adopting the Aqua Interface.pdf | Est. Tokens: 314 -->
Mac OS X bevel buttons use the same bevel height for all sizes of button. The Carbon Control Manager provides three different bevel height settings; Carbon programmers should specify the small bevel height when creating a bevel button in order to provide the largest area in which to draw icons. You should keep a border of 6 pixels around the icon; if your icon is too large, the button may appear dark or grayed-out because the icon obscures the button's highlighting. The minimum size for a bevel button is 20 x 20 pixels. [Figure 1-16](#page-18-0) shows examples of bevel buttons.  
When you use a Carbon Control Manager function to specify a bevel button with an icon and a label, the Human Interface Toolkit automatically places the text label below the icon. Bevel buttons used in the Finder toolbar have 32 x 32 pixel icons and 10 point labels, as illustrated by the Home button in [Figure 1-16](#page-18-0).  
<span id="page-18-0"></span>**Figure 1-16** Bevel button dimensions  
![](images/_page_18_Picture_4.jpeg)  
![](images/_page_18_Picture_5.jpeg)  
![](images/_page_18_Picture_6.jpeg)  
![](images/_page_18_Picture_7.jpeg)  
![](images/_page_18_Picture_8.jpeg)  
One bevel height but can be any size button. Keep a 6 pixel space around icons.