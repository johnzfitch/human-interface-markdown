<!-- Chunk 199 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 691 -->
To enhance the user's experience at application launch, you must provide at least one launch image. A **launch image** looks very similar to the first screen your application displays. iOS displays this image instantly when the user starts your application and until the app is fully ready to use. As soon as your app is ready for use, your app displays its first screen, replacing the launch placeholder image.  
Custom Icon and Image Creation Guidelines  
#### **Supply a launch image to improve user experience.**  
Avoid using it as an opportunity to provide:  
- An "application entry experience," such as a splash screen
- An About window
- Branding elements, unless they are a static part of your application's first screen  
Because users are likely to switch among applications frequently, you should make every effort to cut launch time to a minimum, and you should design a launch image that downplays the experience rather than drawing attention to it.  
**Generally, design a launch image that is identical to the first screen of the application**.  
Exceptions:  
**Text**. The launch image is static, so any text you display in it will not be localized.  
**UI elements that might change**. Avoid including elements that might look different when the application finishes launching, so that users don't experience a flash between the launch image and the first application screen.  
**For iPhone and iPod touch launch images, include the status bar region.** Create launch images of these sizes:  
- 320 x 480 pixels
- 640 x 960 pixels (high resolution)  
**For iPad launch images, do not include the status bar region**. Create launch images of these sizes:  
- 768 x 1004 pixels (portrait)
- 1024 x 748 pixels (landscape)  
Note that most iPad applications should supply a launch image for each orientation.  
If you think that following these guidelines will result in a plain, boring launch image, you're right. Remember, the launch image is not meant to provide an opportunity for artistic expression; it is solely intended to enhance the user's perception of your app as quick to launch and immediately ready for use. The following examples show you how plain a launch image can be.  
The iPhone Settings launch image (shown next to the first application screen) displays only the background of the application, because no other content in the application is guaranteed to be static.  
![](images/_page_151_Picture_2.jpeg)  
![](images/_page_151_Picture_3.jpeg)  
In the launch image for iPhone Stocks (shown next to the first application screen), only static images are included because these images are always visible in the first application view of the Stocks app.  
![](images/_page_151_Figure_5.jpeg)  
![](images/_page_151_Figure_6.jpeg)