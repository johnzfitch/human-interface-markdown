<!-- Chunk 130 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 1419 -->
A **level indicator** provides graphical information about the level or amount of something. Level indicators can be configured to display different colors to warn users when values are reaching critical levels.  
**Important:** The controls described in this section are suitable for use in the window body; they should not be used in the window-frame areas. See Some [Controls](#page-176-1) Can Be Used on the Window Frame (page 177) for controls designed specifically for use in the toolbar (and bottom bar).  
There are three styles of level indicator:  
- Capacity
- <span id="page-208-1"></span>● Rating
- Relevancy  
#### Capacity Indicator  
A **capacity indicator** provides graphical information about the current state of something that has a finite capacity (shown here with labels and tick marks).  
![](images/_page_208_Figure_13.jpeg)  
**API Note:** To define a capacity indicator in your code, use the NSLevelIndicator class with style NSDiscreteCapacityLevelIndicatorStyle or NSContinuousCapacityLevelIndicatorStyle.  
There are two styles of capacity indicator:  
**Continuous.** The continuous capacity indicator consists of a translucent track that is filled with a colored bar that indicates the current value.  
**Discrete.** The discrete capacity indicator consists of a row of separate, rectangular segments equal in number to the maximum value set for the control.  
The default color of the fill in both styles is green. Depending on app-specific definitions, the fill can change to yellow or red.  
The continuous capacity indicator can display tick marks above or below the indicator control to give context to the level shown by the fill.  
The segments in the discrete capacity indicator are either completely filled or empty; they are never partially filled. If you stretch a discrete capacity indicator, the number of segments remains constant, but the width of each segments increases.  
Use a capacity indicator to provide information about the level or amount of something that has well defined minimum and maximum values.  
**Change the fill color to give users more information, if appropriate.** You can configure a capacity indicator to display a different color fill when the current value enters a warning or critical range. Because capacity indicators provide a clear, easily understood picture of a current state, they're especially useful in dialogs and preferences windows that users tend to view briefly.  
If you define a critical value that is less than the warning value, the fill is red below the critical value, yellow between the critical and warning values, and green above the warning value (up to the maximum). This orientation is useful if you need to warn the user when a capacity is approaching the minimum value, such as the end of battery charge.  
**Use a discrete capacity indicator to show relatively coarse-grained values.** The discrete capacity indicator displaysthe current value rounded to the nearest integer and the segments are stretched orshrunk to a uniform width to fit the specified length of the control. Visually, this makes a discrete capacity indicator better for showing coarser-grained values than a continuous capacity indicator.  
**In general, use tick marks with the continuous capacity indicator only.** This is because the number and width of the segments in the discrete capacity indicator provide similar context, making tick marks redundant (and potentially confusing). If you find that you need to display very small segments in a discrete capacity indicator to appropriately represent the scale of values, you might want to use a continuous capacity indicator instead.  
**In general, label at least the first and last tick marks.** Even if you don't label any other tick marks, labeling the beginning and end of the scale provides useful context for the user.  
#### <span id="page-210-0"></span>Rating Indicator  
A **rating indicator** shows the rating of something.  
![](images/_page_210_Picture_5.jpeg)  
**API Note:** To define a rating indicator in your code, use the NSLevelIndicator class with style NSRatingLevelIndicatorStyle.  
By default, the rating indicator displays stars.  
A rating indicator does not display partial stars. Instead, it rounds the current value to the nearest integer to display only whole stars. The stars in a rating indicator are not expanded or shrunk to fit the specified length of the control and no space is added between them.  
Use a rating indicator to provide a graphic representation of the rating of an object. Because a rating indicator conveysthe ranking of one item relative to all other itemsin a category,such asfavorite images or most-visited webpages, it's most useful in a list or table view that contains many items.  
**Allow users to set ranking criteria, if appropriate.** Or, you can make a rating indicator editable so the user can increase or decrease the ranking of an item in a table or list.  
<span id="page-210-1"></span>**Supply a custom image to replace the star, if it makes sense.** You can use any image in place of the star, but you should make sure that it makes sense in the context of your app and the task it enables.  
#### Relevance Indicator  
A **relevance indicator** displays the relevance of something.  
![](images/_page_210_Picture_14.jpeg)  
**API Note:** To define a relevancy indicator in your code, use the NSLevelIndicator class with style NSRelevancyLevelIndicatorStyle.  
Relevance indicators are especially useful as part of a list or table view. This is because relevance as a quantity is easier for users to understand when it is shown in comparison with the relevance of several items.