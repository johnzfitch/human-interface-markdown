<!-- Chunk 149 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 929 -->
If your app uses Newsstand Kit to publish subscription-based periodical content, you need to provide icons for display in the App Store and on people's devices.  
![](images/_page_220_Picture_2.jpeg)  
All Newsstand apps need to supply a Newsstand cover icon that represents the default cover art in the App Store. The long edge of thisicon should measure at least 1024 pixels(512 pixelsforstandard-resolution devices). Note that this icon is separate from the app icon that all iOS apps must provide.  
**Important:** The aspect ratio of all Newsstand icons should be between 1:2 and 2:1.  
All Newsstand icons must be flat and have 90° corners.  
Don't add perspective to any of your Newsstand icons.  
A default Newsstand cover icon should be a generalized facsimile of the cover of a typical issue, which focuses on the parts of the cover that are fairly consistent from issue to issue. For example:  
- Avoid adding to the default cover icon elements that users would never see on an actual cover, such as a message to "tap here for the latest issue".
- Avoid using artwork or headlinesthat are seasonal or topical,such asimagesrelated to holidays or headlines that refer to current events.  
In particular, don't reuse the cover of a previous issue for your default Newsstand cover icon, because users might confuse your app with a specific issue. For example, default magazine and newspaper icons could look something like this:  
![](images/_page_221_Picture_8.jpeg)  
![](images/_page_221_Figure_9.jpeg)  
In addition to the default Newsstand cover icon, you also need to supply a separate icon that accurately represents each new issue so it can appear on the Newsstand shelf and in the multitasking UI on an iOS device. Unlike the default cover icon, each per-issue icon should display details about the contents of a specific issue.  
It's recommended that you create a single large icon for each issue, and allow iOS to scale it for display in both places.  
Specifically, you should create a per-issue icon whose long edge measures at least 1024 pixels (512 pixels for standard-resolution devices). To display the current issue'sicon on the Newsstand shelf and in the multitasking UI, iOS scales your large icon to the following sizes:  
<span id="page-222-0"></span>**Table 43-1** Maximum scaled sizes for per-issue icons  
| Device                         | Scaled size (Newsstand shelf)                                                            | Scaled long-edge size (multitasking<br>UI)                       |
|--------------------------------|------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| iPhone<br>and<br>iPod<br>touch | 180<br>x<br>160<br>pixels<br>(90<br>x<br>80<br>pixels<br>for<br>standard<br>resolution)  | 120<br>pixels<br>(60<br>pixels<br>for<br>standard<br>resolution) |
| iPad                           | 252<br>pixels<br>for<br>long<br>edge<br>(126<br>pixels<br>for<br>standard<br>resolution) | 152<br>pixels<br>(76<br>pixels<br>for<br>standard<br>resolution) |  
For additional information about setting up a Newsstand app, see *iTunes Connect Developer Guide* .  
**Important:** iOS 7 doesn't add any visual enhancements—such as the appearance of a stapled edge or multiple pages—to a Newsstand icon.  
If your app needs to support earlier versions of iOS, you can add the binding type and binding edge keys to the Info.plist file to define how Newsstand icons should appear on devices running iOS 6.1 and earlier. For more information about these keys and their values, see "Contents of the UINewsstandIcon Dictionary" in *Information Property List Key Reference* .