<!-- Chunk 139 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 936 -->
An **application icon** is an icon users put on their Home screens and tap to start an application. This is a place where branding and strong visual design should come together into a compact, instantly recognizable, attractive package.  
Users choose which application icons they want to display on their Home screens, so you should design an icon that is:  
- Attractive, so users feel compelled to keep it on their Home screens
- Distinctive, so users can easily find it among all other icons  
Try to balance eye appeal and clarity of meaning in your icon so that it's rich and beautiful, but still conveys the essence of your application's purpose. Also, it's a good idea to investigate how your choice of image and color might be interpreted by people from different cultures.  
When a user decides to display your application icon on the Home screen, iPhone OS automatically adds some visual effects so that it coordinates with the built-in icons. Specifically, iPhone OS adds:  
- Rounded corners
- Drop shadow
- Reflective shine  
For example, Figure 11-1 shows a simple icon as it might be provided by an application.  
<span id="page-129-0"></span>**Figure 11-1** A simple application icon before it is displayed on a Home screen  
![](images/_page_129_Picture_3.jpeg)  
<span id="page-129-1"></span>Figure 11-2 shows the same icon as it is displayed on a Home screen by iPhone OS.  
**Figure 11-2** A simple application icon displayed on a Home screen  
![](images/_page_129_Picture_6.jpeg)  
Application icons that include a discernible background look best on the Home screen. This is primarily because of the rounded corners iPhone OS adds: uniformly rounded corners ensure that all the icons on a user's Home screen have a consistent appearance that invites tapping. If you create an icon with a black background that disappears when it's viewed on the Home screen, users don'tsee the rounded corners. Such icons often don't look tappable and tend to interfere with the orderly symmetry of the Home screen that users appreciate.  
To ensure that your icon can take advantage of the visual enhancements iPhone OS provides, produce an image in PNG format that:  
- Measures 57 x 57 pixels, with 90 degree corners (if the image measures other than this size, iPhone OS scales it)
- Does not have any shine or gloss
- Does not use alpha transparency  
Name your icon file Icon.png and place it at the top level of your application bundle. To learn more about the contents of the application bundle, see "The Application Bundle" in *iPhone Application Programming Guide*.  
**Note:** If you choose, you can prevent iPhone OS from adding the shine to your icon. To do this, you need to add the UIPrerenderedIcon key to your application's Info.plist file (read "The Information Property List" in *iPhone Application Programming Guide* to learn about this file).  
Your icon should still measure 57 x 57 pixels, regardless of whether you take advantage of the added shine.  
When you submit your application, you must include a 512 x 512 pixel version of your application icon for display in the App Store. Although it'simportant that this version be instantly recognizable as your application icon, it should be subtly richer and more detailed. In other words, you should not simply scale up your application icon to create an icon for the App Store.  
You must also provide a 512 x 512 pixel version of your application icon if you're developing an application for ad-hoc distribution (that is, to be distributed in-house only, not through the App Store). In the ad-hoc case, name the icon file iTunesArtwork (no file extension) and place it at the top level of your application bundle. This icon identifies your application in iTunes.