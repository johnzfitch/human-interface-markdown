<!-- Chunk 147 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 3665 -->
Indicators are controls that show users the status of something. For the most part, users don't interact with indicators.  
**Important:** The controls described in this section are suitable for use in the window body; they should not be used in the window-frame areas. See ["Window-Frame](#page-240-0) Controls" (page 241) for controls designed specifically for use in the toolbar (and bottom bar).  
#### <span id="page-276-1"></span>Progress Indicators  
A **progress indicator** informs users about the status of a lengthy operation.  
**Be sure to locate all types of progress indicators in consistent locations in your windows and dialogs.** For example, the Mail app displays the asynchronous progress indicator in the right end of the To field as it finds and displays email addresses that match what the user types. Choosing a consistent location for a progress indicator allows users to quickly check a familiar place for the status of an operation. (For more information on the importance of providing consistency in your app, see ["Consistency"](#page-32-0) (page 33).)  
There are three types of progress indicators, each of which is suitable for a specific situation:  
- Determinate progress bar
- Indeterminate progress bar
- <span id="page-276-2"></span>● Asynchronous progress indicator  
#### Determinate Progress Bar  
A **determinate progress bar** provides feedback on a process with a known duration.  
![](images/_page_276_Picture_13.jpeg)  
Determinate progress bars are available in Interface Builder. In the Attributes pane of the inspector, select Bar for the style and deselect the Indeterminate checkbox. To create a determinate progress bar using AppKit programming interfaces, use the NSProgressIndicator class with style NSProgressIndicatorBarStyle.  
#### **Appearance and Behavior**  
In a determinate progress bar, the "fill" movesfrom left to right. The fill is provided automatically (you determine the minimum and maximum values that should be represented).  
Users generally expect a determinate progress bar to disappear as soon as the fill completes.  
#### **Determinate Progress Bar Usage**  
Use a determinate progress bar when the full length of an operation can be determined and you want to tell the user how much of the process has been completed. For example, you could use a determinate progress bar to show the progress of a file conversion.  
**Ensure that a determinate progress bar accurately associates progress with time.** A progress bar that becomes 90 percent complete in 5 seconds but takes 5 minutes for the remaining 10 percent, for example, would be annoying and lead users to think that something is wrong.  
**Be sure to allow the fill to complete before dismissing the progress bar.** If you dismiss the progress bar too soon, users are likely to wonder if the process really finished.  
**Allow users to interrupt or stop the process, if appropriate.** If the process being performed can be interrupted, the progress dialog should contain a Cancel button (and support the Esc key). If interrupting the process will result in possible side effects, the button should say Stop instead of Cancel. To learn more about dialogs in general, see ["Dialogs"](#page-214-0) (page 215). To supply a Cancel button, you use a push button (for more information about this control, see "Push [Button"](#page-243-1) (page 244)). To supply a Stop control, you can use the standalone version of the stop progress image (to learn more about this system-provided image, see ["System-Provided](#page-322-0) Images for Use as [Standalone](#page-322-0) Buttons" (page 323)).  
**If appropriate, provide a label for a determinate progress bar in a dialog.** You can do this so that users understand the context in which the processis occurring. Such a labelshould have sentence-style capitalization (for more information on this style, see ["Capitalizing](#page-305-0) Labels and Text" (page 306)).  
#### Indeterminate Progress Bars  
An **indeterminate progress bar** provides feedback on a process of unknown duration.  
![](images/_page_277_Picture_10.jpeg)  
Indeterminate progress bars are available in Interface Builder. In the Attributes pane of the inspector, select Bar for the style and be sure the Indeterminate checkbox is selected. To create an indeterminate progress bar using AppKit programming interfaces, use the NSProgressIndicator class with style NSProgressIndicatorBarStyle.  
#### **Appearance and Behavior**  
An indeterminate progress bar displays a spinning striped fill that indicates an ongoing process. OS X provides this appearance automatically.  
#### **Guidelines**  
Use an indeterminate progress bar when the duration of a process can't be determined.  
**Switch to a determinate progress bar when appropriate.** If an indeterminate process reaches a point where its duration can be determined, switch to a determinate progress bar (for more on determinate progress bars, see ["Determinate](#page-276-2) Progress Bar" (page 277)).  
**In general, use an indeterminate progress bar in a dialog or window that focuses on the process.** For example, you might display an indeterminate progress bar in a dialog that focuses on the opening of the file. This usage helps users understand which process is ongoing.  
**Allow users to interrupt or stop the process, if appropriate.** If the process being performed can be interrupted, the progress dialog should contain a Cancel button (and support the Esc key). If interrupting the process will result in possible side effects, the button should say Stop instead of Cancel. To learn more about dialogs in general, see ["Dialogs"](#page-214-0) (page 215). To supply a Cancel button, you use a push button (for more information about this control, see "Push [Button"](#page-243-1) (page 244)). To supply a Stop control, you can use the standalone version of the stop progress image (to learn more about this system-provided image, see ["System-Provided](#page-322-0) Images for Use as [Standalone](#page-322-0) Buttons" (page 323)).  
**If appropriate, provide a label for an indeterminate progress bar in a dialog.** You can do this so that users know what process is occurring. Such a label should have sentence-style capitalization (for more information on this style, see ["Capitalizing](#page-305-0) Labels and Text" (page 306)). Also, you can end the label with an ellipsis (...) to emphasize the ongoing nature of the processing.  
<span id="page-278-0"></span>**Consider using an asynchronous progress indicator, instead of an indeterminate progress bar, in some cases.** If, for example, you need to provide an indication of an indeterminate process that's associated with a part of a window, such as a control, or if space is limited, you might want to use an asynchronous progress indicator instead. (For more information on asynchronous progress indicators, see ["Asynchronous](#page-278-0) Progress [Indicator"](#page-278-0) (page 279).)  
#### Asynchronous Progress Indicator  
An **asynchronous progress indicator** provides feedback on an ongoing process.  
![](images/_page_278_Picture_10.jpeg)  
Asynchronous progress indicators are available in Interface Builder. In the Attributes pane of the inspector, select Spinning for the style and be sure the Indeterminate checkbox is selected. To create an asynchronous progress indicator using AppKit programming interfaces, use the NSProgressIndicator class with style NSProgressIndicatorSpinningStyle.  
#### **Appearance and Behavior**  
The appearance of the asynchronous progress indicator is provided automatically. The asynchronous progress indicator always spins at the same rate.  
#### **Guidelines**  
Use an asynchronous progressindicator when space is very constrained,such asin a text field or near a control. Because this indicator is small and unobtrusive, it is especially useful for asynchronous events that take place in the background, such as retrieving messages from a server.  
**If the process might change from indeterminate to determinate, start with an indeterminate progress bar.**  
You don't want to start with an asynchronous progress indicator because the determinate progress bar is a different shape and takes up much more space. Similarly, if the process might change from indeterminate to determinate, use an indeterminate progress bar instead of an asynchronous progress indicator, because it is the same shape and size as the determinate progress bar.  
**In general, avoid supplying a label.** Because an asynchronous progress indicator typically appears when the user initiates a process, a label is not usually necessary. If you decide to provide a label that appears with the indicator, create a complete or partial sentence that briefly describes the process that is occurring. You should use sentence-style capitalization (for more information on this style, see ["Capitalizing](#page-305-0) Labels and Text" (page 306)) and you can end the label with an ellipsis (...) to emphasize the ongoing nature of the processing.  
#### <span id="page-279-0"></span>Level Indicators  
A **level indicator** provides graphical information about the level or amount of something. Level indicators can be configured to display different colors to warn users when values are reaching critical levels.  
There are three styles of level indicator:  
- Capacity
- Rating
- Relevancy  
#### Capacity Indicator  
A **capacity indicator** provides graphical information about the current state of something that has a finite capacity (shown here with labels and tick marks).  
![](images/_page_279_Figure_16.jpeg)  
Capacity indicators are available in Interface Builder (you can change its style in the Attributes pane of the inspector). To create one using AppKit programming interfaces, use the NSLevelIndicator class with style NSDiscreteCapacityLevelIndicatorStyle or NSContinuousCapacityLevelIndicatorStyle.  
#### **Appearance and Behavior**  
There are two styles of capacity indicator:  
**Continuous.** The continuous capacity indicator consists of a translucent track that is filled with a colored bar that indicates the current value.  
**Discrete.** The discrete capacity indicator consists of a row of separate, rectangular segments equal in number to the maximum value set for the control.  
The default color of the fill in both styles is green. Depending on app-specific definitions, the fill can change to yellow or red.  
The continuous capacity indicator can display tick marks above or below the indicator control to give context to the level shown by the fill.  
The segments in the discrete capacity indicator are either completely filled or empty; they are never partially filled. If you stretch a discrete capacity indicator, the number of segments remains constant, but the width of each segments increases.  
#### **Capacity Indicator Usage**  
Use a capacity indicator to provide information about the level or amount of something that has well defined minimum and maximum values.  
**Change the fill color to give users more information, if appropriate.** You can configure a capacity indicator to display a different color fill when the current value enters a warning or critical range. Because capacity indicators provide a clear, easily understood picture of a current state, they're especially useful in dialogs and preferences windows that users tend to view briefly.  
If you define a critical value that is less than the warning value, the fill is red below the critical value, yellow between the critical and warning values, and green above the warning value (up to the maximum). This orientation is useful if you need to warn the user when a capacity is approaching the minimum value, such as the end of battery charge.  
**Use a discrete capacity indicator to show relatively coarse-grained values.** The discrete capacity indicator displaysthe current value rounded to the nearest integer and the segments are stretched orshrunk to a uniform width to fit the specified length of the control. Visually, this makes a discrete capacity indicator better for showing coarser-grained values than a continuous capacity indicator.  
**In general, use tick marks with the continuous capacity indicator only.** This is because the number and width of the segments in the discrete capacity indicator provide similar context, making tick marks redundant (and potentially confusing). If you find that you need to display very small segments in a discrete capacity indicator to appropriately represent the scale of values, you might want to use a continuous capacity indicator instead.  
**In general, label at least the first and last tick marks.** Even if you don't label any other tick marks, labeling the beginning and end of the scale provides useful context for the user.  
#### Rating Indicator  
A **rating indicator** shows the rating of something.  
![](images/_page_281_Picture_5.jpeg)  
Rating indicators are available in Interface Builder. Start with a discrete level indicator object and change its style to Rating in the Attributes pane of the inspector. To create one using AppKit programming interfaces, use the NSLevelIndicator class with style NSRatingLevelIndicatorStyle.  
#### **Appearance and Behavior**  
By default, the rating indicator displays stars.  
A rating indicator does not display partial stars. Instead, it rounds the current value to the nearest integer to display only whole stars. The stars in a rating indicator are not expanded or shrunk to fit the specified length of the control and no space is added between them.  
#### **Guidelines**  
Use a rating indicator to provide a graphic representation of the rating of an object. Because a rating indicator conveysthe ranking of one item relative to all other itemsin a category,such asfavorite images or most-visited webpages, it's most useful in a list or table view that contains many items.  
**Allow users to set ranking criteria, if appropriate.** Or, you can make a rating indicator editable so the user can increase or decrease the ranking of an item in a table or list.  
**Supply a custom image to replace the star, if it makes sense.** You can use any image in place of the star, but you should make sure that it makes sense in the context of your app and the task it enables.  
#### Relevance Indicator  
A **relevance indicator** displays the relevance of something.  
![](images/_page_282_Picture_3.jpeg)  
Relevance indicators are especially useful as part of a list or table view. This is because relevance as a quantity is easier for users to understand when it is shown in comparison with the relevance of several items.