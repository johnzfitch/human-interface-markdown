<!-- Chunk 72 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 599 -->
An **application icon** is an icon users put on their Home screens and tap to start an application. This is a place where branding and strong visual design should come together into an compact, instantly recognizable, attractive package.  
Users can display as many application icons on their Home screens as they want, so you should design an icon that is:  
- Attractive, so users want to keep it on their Home screens
- Distinctive, so users can easily find it among all other icons  
When a user decides to display your icon on the Home screen, iPhone OS automatically adds some visual effects so that it coordinates with the built-in icons. Specifically, iPhone OS adds:  
- Rounded corners
- <span id="page-110-2"></span>■ Drop shadow
- Reflective shine  
For example, Figure 11-1 shows a simple icon as it might be provided by an application.  
**Figure 11-1** A simple application icon before it is displayed on a Home screen  
![](images/_page_110_Picture_15.jpeg)  
Figure 11-2 shows the same icon as it is displayed on a Home screen by iPhone OS.  
<span id="page-111-1"></span>**Figure 11-2** A simple application icon displayed on a Home screen  
![](images/_page_111_Picture_3.jpeg)  
To ensure that your icon can take advantage of these visual enhancements, provide an image in PNG format that:  
- Measures 57 x 57 pixels, with 90 degree corners (if the image measures other than this size, iPhone OS scales it)
- Does not have any shine or gloss  
Name your icon file Icon.png and place it at the top level of your application bundle. To learn more about the contents of the application bundle, see *iPhone Application Programming Guide*.  
**Note:** If you choose, you can prevent iPhone OS from adding the shine to your icon. To do this, you need to add the UIPrerenderedIcon key to your application's Info.plist file (read *iPhone Application Programming Guide* to learn about this file).  
Your icon should still measure 57 x 57 pixels, regardless of whether you take advantage of the added shine.  
As with other user interface elements in iPhone OS, icons that use bold shapes and lines and pleasing color combinations work best. It's advisable to spend some time simplifying your icon design so it clearly conveys the essence of your application. Also, it's a good idea to investigate how your choice of image and color might be interpreted by people from different cultures.