<!-- Chunk 123 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 485 -->
A **page control** indicatesthe number of open views and which one is currently visible (shown here in Weather).  
![](images/_page_185_Picture_13.jpeg)  
**API Note:** To learn more about defining a page control in your code, see "Page Controls".  
#### A page control:  
- Displays an indicator dot for each open view in an app (from left to right, the dots represent the order in which the views were opened)
- By default, uses an opaque dot to represent the currently visible view and translucent dots to represent all other open views
- Doesn't allow users to visit views nonsequentially
- Doesn't shrink or squeeze together dots as more views are opened (if you try to display more dots than will fit in the view, the dots are clipped)
- Doesn't enable navigation between views by default; you must implement view-to-view navigation and update the page control's state appropriately  
Use a page control when it's more important to show users how many views are open than it is to help them choose a specific view. A page control is designed for apps in which each view is a peer of every other view.  
**Don't use a page control to display views in a hierarchy or other complex arrangement.** A page control doesn't show how views are related to each other and it doesn't indicate which view corresponds to each dot, so it can't help users navigate to a specific view.  
**Avoid displaying too many dots.** More than about 10 dots are hard for users to count at a glance and more than about 20 open views are time consuming to visit in sequence. If users can open more than about 20 peer views in your app, consider displaying the views in a different arrangement that provides more information about the views and enables nonsequential navigation.  
**Vertically center a page control between an open view's bottom edge and the screen's bottom edge.** In this position, a page control is always visible without getting in users' way.