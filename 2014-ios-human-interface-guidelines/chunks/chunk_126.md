<!-- Chunk 126 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 328 -->
A **refresh control** performs a user-initiated content refresh—typically in a table (shown here above the mailbox list).  
![](images/_page_189_Picture_3.jpeg)  
**API Note:** To learn more about defining a refresh control in your code, see *UIRefreshControl Class Reference* .  
#### A refresh control:  
- Looks similar to an activity indicator
- Can display a title
- Is hidden by default until the user initiates a refresh action by dragging down from the top edge of a table  
Use a refresh control to give users a consistent way to tell a table or other view to update its contents immediately, without waiting for the next automatic update.  
**Don't stop performing automatic content updates just because you provide a refresh control.** Even though users appreciate being able to request that an update be performed *now*, they still appreciate content that refreshes itself automatically. If you rely on users to initiate all refreshes, users who are unaware of the refresh control are likely to wonder why your app displays stale data. In general, you want to give users the option to refresh contents immediately; you don't want to make users responsible for every update.  
**Supply a short title only if it adds value.** In particular, don't use the title to describe how to use the refresh control.