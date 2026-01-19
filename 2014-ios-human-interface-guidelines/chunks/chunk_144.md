<!-- Chunk 144 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 331 -->
Every app should supply a small icon that iOS can display when the app name matches a term in a Spotlight search. Apps that supply settings should also supply a small icon to identify them in the built-in Settings app. These icons should clearly identify your app so that people can recognize it in a list of search results or in Settings. For example, the icons of the built-in apps are easy to discern in Settings, even though the icons are small:  
![](images/_page_212_Picture_2.jpeg)  
You can name these small icons anything you want as long as you use the CFBundleIcons key to declare the names and you add the @2x suffix to the names of all high-resolution icons. You can use custom names because iOS chooses an icon based on whether its size is appropriate for the intended usage. To learn more about icon naming, see "App Icons" in *iOS App Programming Guide* .  
For all devices, supply separate icons for Spotlight search results and Settings. If you don't provide these icons, iOS might shrink your app icon for display in these locations.  
For Spotlight search results on iPhone, iPod touch, and iPad create an icon in the following two sizes:  
- 80 x 80 pixels
- 40 x 40 pixels (standard resolution)  
For Settings on iPhone, iPod touch, and iPad create an icon in the following two sizes:  
● 58 x 58 pixels