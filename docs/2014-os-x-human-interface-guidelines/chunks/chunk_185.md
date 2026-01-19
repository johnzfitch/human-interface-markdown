<!-- Chunk 185 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 667 -->
An app icon is displayed in many places, such as the Finder, Dock, Launchpad, and App Store. To ensure that OS X can display your app icon appropriately in each context, you create the icon in different sizes and resolutions, and follow specific naming conventions.  
As you create artwork for high-resolution displays, be sure to treat each image asits own resource. Even though the high-resolution version of one icon might use the same canvas size as the standard version of another, you should redraw each image. For example, don't use the 32 x 32 standard-resolution icon for the icon\_16x16@2x resource even though they both have a canvas size of 32 x 32 pixels. It's best when an app's icon looksthe same on both standard- and high-resolution displays, because a user can set up multiple displays with different resolutions and drag windows from one display to the next.  
As the canvas size decreases, you have fewer pixels to draw, which means that smaller sizes should be less detailed. In the Keynote app icon shown here, for example, the smaller size is not as detailed as the larger size, where you can read the list items, discern separate pages on the podium, and and see the texture of the metal stand. Each image is appropriately drawn for the canvas size.  
![](images/_page_319_Picture_1.jpeg)  
To name an app icon, use this format:  
- icon\_<file\_size>.<filename\_extension> for standard icons
- icon\_<file\_size>@2x.<filename\_extension> for high-resolution icons  
For example, to supply the 512 x 512 version of an app icon, name the files icon\_512x512.png and icon\_512x512@2x.png. For more details about naming conventions,see Adopt the @2x Naming Convention in *High Resolution Guidelines for OS X* .  
<span id="page-319-0"></span>To ensure that your app icon looks great in all the places that users see it, you need to provide resources in the sizes listed in Table 71-1.  
**Table 71-1** App icon resource sizes  
| Filename        | Canvas size (in pixels) |
|-----------------|-------------------------|
| icon_512x512@2x | 1024<br>x<br>1024       |
| icon_512x512    | 512<br>x<br>512         |
| icon_256x256@2x | 512<br>x<br>512         |
| icon_256x256    | 256<br>x<br>256         |
| icon_128x128@2x | 256<br>x<br>256         |
| icon_128x128    | 128<br>x<br>128         |
| icon_32x32@2x   | 64<br>x<br>64           |  
| Filename      | Canvas size (in pixels) |
|---------------|-------------------------|
| icon_32x32    | 32<br>x<br>32           |
| icon_16x16@2x | 32<br>x<br>32           |
| icon_16x16    | 16<br>x<br>16           |  
**Note:** PNG with an sRGB color profile is the recommended format for app icons.