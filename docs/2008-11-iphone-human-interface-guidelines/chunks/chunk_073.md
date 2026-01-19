<!-- Chunk 73 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 368 -->
A **settings icon** is an icon that identifies your application's available settingsin the built-in Settings application. If your iPhone application must offersettings users can adjust, you provide a settings bundle in your application bundle that lists them (see *iPhone Application Programming Guide* for more information on these bundles). In some circumstances, iPhone OS makes some settings available, even though the application itself does not provide custom settings.  
If you define custom settings, you need to supply an icon that clearly identifies your application in the built-in Settings application. This allows users easily to find your application'ssettings among the settings of all other applications they have installed.  
Therefore, you should create a streamlined, attractive icon that:  
- Uses the PNG format.
- Measures about 29 x 29 pixels  
Name your settings icon file Icon-Settings.png and place it at the top level of your application bundle. To learn more about the contents of the application bundle, see *iPhone Application Programming Guide*.  
Creating Custom Icons and Images  
**Note:** When iPhone OS needs to provide settings for an application without a settings bundle, and there is no icon named Icon-Settings.png in the application bundle, iPhone OS shrinks the application icon for display in the Settings application. (See ["Application](#page-110-1) Icons" (page 111) for more information about designing an application icon.)