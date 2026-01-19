<!-- Chunk 141 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 750 -->
To enhance the user's experience at application launch, you should provide a launch image. A **launch image** looks very similar to the first screen your application displays. iPhone OS displays this image instantly when the user taps your application icon on the Home screen. Assoon asit'sready for use, your application displays its first screen, replacing the launch placeholder image.  
It's important to emphasize that the reason to supply a launch image is to improve user experience; it is *not* an opportunity to provide:  
- An "application entry experience," such as a splash screen
- An About window
- Branding elements, unless they are a static part of your application's first screen  
Because users are likely to switch among applications frequently and quickly, you should make every effort to cut launch time to a minimum, and you should design a launch image that downplays the experience rather than drawing attention to it.  
To do this, you should design an image in PNG format that:  
■ Measures 320 x 480 pixels. Including the status bar area allows you to display the status bar color you've chosen immediately, instead of displaying it after your application has finished starting.  
- Is identical to the first screen of the application, except for:
- ❏ Text. The launch image is static, so any text you display in it will not be localized.
- ❏ User interface elementsthat might change. Avoid including elementsthat might look different when the application finishes launching, so that users don't experience a flash between the launch image and the first application screen.  
Name your launch image file Default.png and place it at the top level of your application bundle. To learn more about the contents of the application bundle, see *iPhone Application Programming Guide*.  
If you think that following these guidelines will result in a very plain, boring launch image, you're right. Remember, the launch image is not meant to provide an opportunity for artistic expression; it is solely intended to enhance the user's perception of your application as quick to launch and immediately ready for use. The following examples show you how plain a launch image can be.  
<span id="page-131-0"></span>The first example is the launch image for the built-in Settings application, shown in Figure 11-3. The Settings launch image displays only the background of the application, because no other content in the application is guaranteed to be static.  
**Figure 11-3** The launch image for the Settings application  
![](images/_page_131_Picture_9.jpeg)  
![](images/_page_131_Picture_10.jpeg)  
Another launch image example comes from the built-in Stocks application, shown in Figure 11-4. Note that the only images included in the launch image are static images, which are always visible in the front view of the Stocks application.  
![](images/_page_132_Figure_2.jpeg)  
<span id="page-132-1"></span>![](images/_page_132_Figure_3.jpeg)  
![](images/_page_132_Figure_4.jpeg)