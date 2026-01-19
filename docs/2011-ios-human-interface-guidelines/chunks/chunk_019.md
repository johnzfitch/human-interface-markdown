<!-- Chunk 19 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 372 -->
Only one application is visible in the foreground at a time. When people switch from one app to another, the previous app quits and its user interface goes away.  
Prior to iOS 4, this meant that the quitting app was immediately removed from memory. In iOS 4 and later, the quitting app transitions to the background, where it may or may not continue running. This feature, called **multitasking**, allows apps to remain in the background until they are launched again or until they are terminated.  
**Note:** Multitasking is available on certain devices running iOS 4 and later.  
Most apps enter a suspended state when they transition to the background. Suspended apps are displayed in the multitasking UI, which provides an effective way to find recently used apps. The multitasking UI appears at the bottom of the screen, below the UI of the currently running app or the Home screen (shown here below the iPhone Settings app).  
![](images/_page_15_Picture_2.jpeg)  
When people restart a suspended app, it can instantly resume running from the point where it quit, without having to reload its user interface.  
Some applications might need to continue running in the background while users run another app in the foreground. For example, users might want an app that plays audio to continue playing while they're using a different app to check their calendar or handle email.  
To learn how to handle multitasking correctly and gracefully, see ["Multitasking"](#page-70-1) (page 71).