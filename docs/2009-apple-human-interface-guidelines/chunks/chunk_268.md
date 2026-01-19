<!-- Chunk 268 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 2318 -->
A **level indicator** provides graphical information about the level or amount of something. Level indicators can be configured to display different colors to warn users when values are reaching critical levels.  
There are three styles of level indicator:  
- Capacity
- Rating
- Relevancy  
#### <span id="page-315-3"></span><span id="page-315-2"></span>Capacity Indicators  
<span id="page-315-1"></span>A **capacity indicator**, asits name suggests, provides graphical information about the currentstate ofsomething that has a finite capacity, such as storage space or battery charge. There are two styles of capacity indicator, continuous and discrete. A **continuous capacity indicator** is a translucent track that is filled with a colored bar that indicates the current value. For example, Figure 15-61 shows a continuous capacity indicator that represents how much space has been used (and how much space is left) in the user's mail account.  
**Figure 15-61** A continuous capacity indicator shows a fine-grained representation of current capacity  
![](images/_page_315_Figure_13.jpeg)  
<span id="page-316-1"></span>A **discrete capacity indicator** is a row of separate, rectangular segments equal in number to the maximum value set for the control. Figure 15-62 shows a discrete capacity indicator that represents the battery charge in a Bluetooth mouse.  
<span id="page-316-0"></span>**Figure 15-62** A discrete capacity indicator shows a medium-grained representation of current capacity  
![](images/_page_316_Picture_4.jpeg)  
#### **Capacity Indicator Usage**  
Use a capacity indicator to provide information about the level or amount ofsomething that has well defined minimum and maximum values. You can configure a capacity indicator to display a different color fill when the current value enters a warning or critical range that you define (for more on this, see "Capacity Indicator Contents and Labeling"). Because capacity indicators provide a clear, easily understood picture of a current state, they're especially useful in dialogs and preferences windows that users tend to view briefly.  
Note that the discrete capacity indicator displays the current value rounded to the nearest integer, and the segments are stretched or shrunk to a uniform width to fit the specified length of the control. This means that the segments in the discrete capacity indicator are either completely filled or empty, never partially filled. This makes a discrete capacity indicator better for showing coarser-grained values than a continuous capacity indicator.  
#### **Capacity Indicator Contents and Labeling**  
The default color of the fill in both capacity indicator styles is green. If you define a value for a warning level, the fill color changes to yellow when it reaches that value. If you define a value for a critical level, the fill color changes to red when it reaches that value.  
You can specify which end of the indicator is critical (red) by setting appropriate values. If you define a critical value that is greater than the warning value, the fill is green at values less than the warning level, yellow between the warning and critical levels, and red above the critical level. This orientation is useful if you need to display a warning when a capacity is approaching the maximum value, such as the limit of storage space.  
If you define a critical value that is less than the warning value, the fill is red below the critical value, yellow between the critical and warning values, and green above the warning value (up to the maximum). This orientation is useful if you need to warn the user when a capacity is approaching the minimum value, such as the end of battery charge.  
<span id="page-317-0"></span>For example, Figure 15-63 shows different states of a continuous capacity indicator. Below it, Figure 15-64 shows different states of a discrete capacity indicator.  
**Figure 15-63** A continuous capacity indicator displaying values in three different ranges  
![](images/_page_317_Figure_5.jpeg)  
<span id="page-317-1"></span>**Figure 15-64** A discrete capacity indicator displaying values in three different ranges  
![](images/_page_317_Picture_7.jpeg)  
Both continuous and discrete capacity indicators allow the display of tick marks above or below the indicator control to give context to the level shown by the fill. However, only the continuous capacity indicator should display the tick marks because the number and width of the segments in the discrete capacity indicator provide similar context, making tick marksredundant. If you find that you need to display very smallsegments in a discrete capacity indicator to appropriately represent the scale of values, you might want to use a continuous capacity indicator instead.  
You should label at least the first and last tick marks to define the scale of the control and provide context for the user.  
#### **Capacity Indicator Specifications**  
**Control sizes**: Both styles of capacity indicators are available in regular size only (the bar or segment has a height of 16 pixels), but you determine the horizontal width of the control. Note that as you stretch a discrete level indicator, the number ofsegmentsremains constant, but the width of each segmentstretches accordingly.  
**Label spacing and fonts**: If you want to provide labels for tick marks in a continuous capacity indicator, use the label font (see ["Fonts"](#page-128-1) (page 129) for more information about this font). These labels should be placed 3 pixels below the lower edge of the tick marks.  
#### **Capacity Indicator Implementation**  
Continuous and discrete capacity indicators are available in Interface Builder. You can change the style from discrete to continuousin the Attributes pane of the inspector. To create one using Application Kit programming interfaces, use the NSLevelIndicator class with style NSDiscreteCapacityLevelIndicatorStyle or NSContinuousCapacityLevelIndicatorStyle.  
#### <span id="page-318-2"></span>Rating Indicators  
<span id="page-318-0"></span>A **rating indicator** displays a number of stars that corresponds to the rating of something. For example, Figure 15-65 shows the rating a user assigned an item in iTunes.  
**Figure 15-65** A rating indicator shows the user-assigned rating for an item  
![](images/_page_318_Picture_10.jpeg)  
Figure 15-66 shows rating indicators displaying different values.  
<span id="page-318-1"></span>**Figure 15-66** Rating indicators showing different ratings  
#### **Rating Indicator Usage**  
Use a rating indicator to provide a graphic representation of the rating of an object. Because a rating indicator conveysthe ranking of one item relative to all other itemsin a category,such asfavorite images or most-visited webpages, it's most useful in a list or table view that contains many items.  
You might want to allow the user to set ranking criteria (perhaps in a preferences window) that you use to determine what rating should be displayed for each item as it appears. Or, you can make a rating indicator editable so the user can increase or decrease the ranking of an item in a table or list.  
#### **Rating Indicator Contents and Labeling**  
By default, the rating indicator displaysstars, but you can supply a custom image to replace the stars. Although this section assumes that the rating indicator displays stars, the information applies equally to an image you supply.  
A rating indicator does not display partial stars. Instead, it rounds the current value to the nearest integer to display only whole stars. The stars in a rating indicator are not expanded or shrunk to fit the specified length of the control and no space is added between them.  
#### <span id="page-319-1"></span>**Rating Indicator Implementation**  
Rating indicators are available in Interface Builder. Start with a discrete level indicator object and change its style to Rating in the Attributes pane of the inspector. To create one using Application Kit programming interfaces, use the NSLevelIndicator class with style NSRatingLevelIndicatorStyle.  
#### Relevance Indicators  
<span id="page-319-2"></span><span id="page-319-0"></span>A **relevance indicator** is a style of level indicator that displays the relevance of items, such as search results. For example, Preview uses relevance indicators to show users the relevance of search results, as shown in Figure 15-67.  
**Figure 15-67** A relevance indicator shows the relevance of each item in a list  
![](images/_page_319_Picture_10.jpeg)  
Some of the states a relevance indicator can display are shown in Figure 15-68.  
<span id="page-320-2"></span>**Figure 15-68** Relevance indicator states  
![](images/_page_320_Figure_3.jpeg)  
Relevance indicators are especially useful as part of a list or table view. Thisis because relevance as a quantity is easier for users to understand when it is shown in comparison with the relevance of several items.  
Relevance indicators are available in Interface Builder. Start with a discrete level indicator and change its style to Relevancy in the Attributes pane of the inspector. To create one using Application Kit programming interfaces, use the NSLevelIndicator class with style NSRelevancyLevelIndicatorStyle.