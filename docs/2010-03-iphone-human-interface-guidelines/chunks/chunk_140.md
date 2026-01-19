<!-- Chunk 140 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 318 -->
Every application should supply a small icon that iPhone OS can display when the application name matches a term in a Spotlight search.  
Applications that supply settings should also supply this icon to identify them in the built-in Settings application.  
Your small icon should clearly identify your application so that users can easily recognize it in a list of search results. To do this, create a streamlined, attractive icon that:  
- Uses the PNG format.
- Measures about 29 x 29 pixels.  
Name your icon file Icon-Small.png and place it at the top level of your application bundle. To learn more about the contents of the application bundle,see "The Application Bundle" in *iPhone Application Programming Guide*.  
**Note:** If you do not provide an icon named Icon-Small.png, and your application bundle does not contain a previous version of a small icon named Icon-Settings.png, iPhone OS shrinks your application icon for display in search results and in Settings.  
If your application bundle already contains a small icon named Icon-Settings.png, and does not contain an icon named Icon-Small.png, iPhone OS displays the settings icon in the search results. However, you should update the application bundle so that it contains only the Icon-Small.png file.