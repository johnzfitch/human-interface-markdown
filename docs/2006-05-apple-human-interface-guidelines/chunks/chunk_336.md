<!-- Chunk 336 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 364 -->
The rating indicator displays a number of stars that corresponds to the rating of something. A rating indicator should be part of a list or table view because it conveys the relative rankings of different members in a category, such as favorite images or most-visited webpages.  
By default, the rating indicator displays stars, but you can supply a custom image to replace the stars. Although this section assumes that the ratingindicator displays stars, the information applies equally to an image you supply.  
The rating indicator does not display partial stars. Instead, it rounds the current value to the nearest integer to display only whole stars. The stars in the rating indicator are not expanded or shrunk to fit the specified length of the control and no space is added between them.  
<span id="page-264-1"></span>You can make the rating indicator editable to allow a user to increase or decrease the ranking of a table or list member.  
[Figure](#page-264-1) 14-42 (page 265) shows rating indicators displaying different values.  
**Figure 14-42** A rating indicator showing different ratings  
![](images/_page_264_Figure_13.jpeg)  
**Carbon:** The rating indicator is not available in Carbon.  
<span id="page-265-3"></span>**Cocoa:** The rating indicator is available in Interface Builder in the Controls palette. Start with a discrete level indicator and change its style to ratingin the Attributes pane of the NSLevelIndicator Inspector.