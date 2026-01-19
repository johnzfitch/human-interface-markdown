<!-- Chunk 93 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 948 -->
Retina display allows you to show high-resolution versions of your art and icons. If you merely scale up your existing artwork, you miss out on the opportunity to provide the beautiful, captivating images users expect. Instead, you should rework your existing image resources to create large, higher-quality versions that are:  
● **Richer in texture.** For example, in the high-resolution versions of the System Preferences and Contacts icons, the metal and paper textures are clearly visible.  
![](images/_page_115_Picture_2.jpeg)  
![](images/_page_115_Picture_3.jpeg)  
● **More detailed.** For example, in the high-resolution versions of the Safari and Preview icons, you can see details such as the accurate contours of the continents behind the compass and the etching on the magnifying glass.  
![](images/_page_115_Picture_5.jpeg)  
![](images/_page_115_Picture_6.jpeg)  
● **More realistic.** For example, the high-resolution versions of the Keynote and Pages icons combine rich textures and fine details to create realistic portrayals of a podium and an inkwell.  
![](images/_page_115_Picture_8.jpeg)  
![](images/_page_115_Picture_9.jpeg)  
#### <span id="page-116-0"></span>Provide the Correct Resources and Let OS X Do the Work  
Your app icon is displayed in the Finder, Dock, Launchpad, and elsewhere. For OS X to display your icon appropriately, create your app icon in different sizes and resolutions, and follow specific naming conventions. In particular, use the format:  
- icon\_<file\_size>.<filename\_extension> for standard icons
- icon\_<file\_size>@2x.<filename\_extension> for high-resolution icons  
For example, you should supply icon\_512x512.png and icon\_512x512@2x.png. For more details about naming conventions, see "Adopt the @2x Naming Convention" in *High Resolution Guidelines for OS X* .  
<span id="page-116-1"></span>To ensure that your app icon looks great in all the places that users see it, you need to provide resources in the sizes listed in [Table](#page-116-1) 5-1 (page 117).  
**Table 5-1** App icon resource sizes  
| Filename        | Size of canvas (in pixels) |
|-----------------|----------------------------|
| icon_512x512@2x | 1024<br>x<br>1024          |
| icon_512x512    | 512<br>x<br>512            |
| icon_256x256@2x | 512<br>x<br>512            |
| icon_256x256    | 256<br>x<br>256            |
| icon_128x128@2x | 256<br>x<br>256            |
| icon_128x128    | 128<br>x<br>128            |
| icon_32x32@2x   | 64<br>x<br>64              |
| icon_32x32      | 32<br>x<br>32              |
| icon_16x16@2x   | 32<br>x<br>32              |
| icon_16x16      | 16<br>x<br>16              |  
**Note:** PNG with an sRGB color profile is the recommended format for app icons.  
As you create your artwork for high-resolution display, be sure to treat each image as its own resource. Even though the high-resolution version of one icon might use the same canvas size as the standard version of another, you should redraw each image. For example, don't use the 32 x 32 standard-resolution icon for  
icon\_16x16@2x even though they both have a canvas size of 32 x 32 pixels. It's important for an app's icon to look the same on standard- and high-resolution displays, because a user can set up multiple displays with different resolutions and drag the app from one display to the next.  
As the canvas size decreases, you have fewer pixels to draw, which means that smaller sizes should be less detailed. For example, the smaller size Calendar app icon is not as detailed as the larger size, where you can see numbers for the days of the month, highlights in the metal rings, and lines at the bottom of the pile to indicate more pages. Each image is appropriately drawn for the canvas size.  
![](images/_page_117_Picture_3.jpeg)