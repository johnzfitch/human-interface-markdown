<!-- Chunk 111 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 693 -->
A **split view controller** is a full-screen view controller that manages the presentation of two side-by-side view controllers.  
![](images/_page_170_Picture_3.jpeg)  
**API Note:** Each child view controller of a split view controller isresponsible for managing the display of one pane. The split view controller itself presents these child view controllers and manages transitions between different orientations. To learn more about defining a split view controller in your code, see *UISplitViewController Class Reference* and "Split View Controllers".  
**Important:** Split view controllers are available in iPad apps only.  
#### A split view controller:  
- Displays two panes (the width of the left pane is fixed at 320 points in all orientations; you can customize the width of the right pane)
- Can optionally display the left pane in a popover when the device is in portrait orientation
- Can contain a wide variety of objects and views, such as:
- Table, image, map, text, web, or custom views  
● Navigation bars, toolbars, or tab bars  
**Note:** Even though the left pane is often called the *master pane* and the right pane is often called the *detail pane* , this relationship is not enforced in code.  
Use a split view controller to display persistent information in the left pane and related details or subordinate information in the right pane. In this design pattern, when people select an item in the left pane, the right pane should display the information related to that item. (You're responsible for making this happen in code.)  
**Avoid creating a right pane that is narrower than the left pane.** If the right pane is narrower than the left pane, the split view controller no longer fills the width of the screen and the overall appearance is unbalanced.  
**Avoid displaying a navigation bar in both panes at the same time.** Doing this would make it very difficult for users to discern the relationship between the two panes.  
**In general, indicate the current selection in the left pane in a persistent way.** Even though the content of the right pane can change, it should always remain related to the item selected in the left pane. This viewing experience helps people understand the relationship between the item in the left pane and the contents of the right pane.  
**Give people alternative ways to access the left pane, if appropriate.** By default, only the right pane is displayed in portrait orientation and you provide users with a button (typically located in a navigation bar) to reveal and hide the left pane. The split view controller also supportsthe swipe gesture to perform the reveal/hide action. Unless your app uses the swipe gesture to perform other functions, you should let people swipe to access the left pane.