<!-- Chunk 404 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 516 -->
<span id="page-309-0"></span>A **rating indicator** displays a number of stars that corresponds to the rating of something. For example, Figure 15-65 shows the rating a user assigned an item in iTunes.  
**Figure 15-65** A rating indicator shows the user-assigned rating for an item  
![](images/_page_309_Picture_10.jpeg)  
<span id="page-309-1"></span>Figure 15-66 shows rating indicators displaying different values.  
**Figure 15-66** Rating indicators showing different ratings  
#### **Rating Indicator Usage**  
Use a rating indicator to provide a graphic representation of the rating of an object. Because a rating indicator conveysthe ranking of one item relative to all other itemsin a category,such asfavorite images or most-visited webpages, it's most useful in a list or table view that contains many items.  
You might want to allow the user to set ranking criteria (perhaps in a preferences window) that you use to determine what rating should be displayed for each item as it appears. Or, you can make a rating indicator editable so the user can increase or decrease the ranking of an item in a table or list.  
#### **Rating Indicator Contents and Labeling**  
By default, the rating indicator displaysstars, but you can supply a custom image to replace the stars. Although this section assumes that the rating indicator displays stars, the information applies equally to an image you supply.  
A rating indicator does not display partial stars. Instead, it rounds the current value to the nearest integer to display only whole stars. The stars in a rating indicator are not expanded or shrunk to fit the specified length of the control and no space is added between them.  
#### <span id="page-310-1"></span>**Rating Indicator Implementation**  
Rating indicators are available in Interface Builder. Start with a discrete level indicator object and change its style to Rating in the Attributes pane of the inspector. To create one using Application Kit programming interfaces, use the NSLevelIndicator class with style NSRatingLevelIndicatorStyle.