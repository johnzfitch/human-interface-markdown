<!-- Chunk 93 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 2004 -->
#### Take Advantage of High-Resolution Display  
Retina display allows you to show high-resolution versions of your art and icons. If you merely scale up your existing artwork, you miss out on the opportunity to provide the beautiful, captivating images users expect. Instead, you should rework your existing image resources to create large, higher-quality versions that are:  
● **Richer in texture.** For example, in the high-resolution versions of the System Preferences and Contacts icons, the metal and paper textures are clearly visible.  
![](images/_page_115_Picture_8.jpeg)  
![](images/_page_115_Picture_9.jpeg)  
● **More detailed.** For example, in the high-resolution versions of the Safari and Preview icons, you can see details such as the accurate contours of the continents behind the compass and the etching on the magnifying glass.  
![](images/_page_116_Picture_2.jpeg)  
![](images/_page_116_Picture_3.jpeg)  
● **More realistic.** For example, the high-resolution versions of the Keynote and Pages icons combine rich textures and fine details to create realistic portrayals of a podium and an inkwell.  
![](images/_page_116_Picture_5.jpeg)  
![](images/_page_116_Picture_6.jpeg)  
#### <span id="page-116-0"></span>Provide the Correct Resources and Let OS X Do the Work  
Your app icon is displayed in the Finder, Dock, Launchpad, and elsewhere. For OS X to display your icon appropriately, create your app icon in different sizes and resolutions, and follow specific naming conventions. In particular, use the format:  
- icon\_<file\_size>.<filename\_extension> for standard icons
- icon\_<file\_size>@2x.<filename\_extension> for high-resolution icons  
For example, you should supply icon\_512x512.png and icon\_512x512@2x.png. For more details about naming conventions, see "Adopt the @2x Naming Convention" in *High Resolution Guidelines for OS X* .  
To ensure that your app icon looks great in all the places that users see it, you need to provide resources in the sizes listed in [Table](#page-117-0) 5-1 (page 118).  
<span id="page-117-0"></span>**Table 5-1** App icon resource sizes  
| Filename        | Size of canvas (in pixels) |
|-----------------|----------------------------|
| icon_512x512@2x | 1024x1024                  |
| icon_512x512    | 512x512                    |
| icon_256x256@2x | 512x512                    |
| icon_256x256    | 256x256                    |
| icon_128x128@2x | 256x256                    |
| icon_128x128    | 128x128                    |
| icon_32x32@2x   | 64x64                      |
| icon_32x32      | 32x32                      |
| icon_16x16@2x   | 32x32                      |
| icon_16x16      | 16x16                      |  
**Note:** PNG with an sRGB color profile is the recommended format for app icons.  
As you create your artwork for high-resolution display, be sure to treat each image as its own resource. Even though the high-resolution version of one icon might use the same canvas size as the standard version of another, make sure to redraw each image. For example, do not use the 32x32 standard-resolution icon as the 16x16@2x icon, even though they both have a canvas size of 32x32 pixels. App icons should look the same on standard- and high-resolution displays, because a user can set up multiple displays with different resolutions and drag the app from one display to the next.  
As the canvas size decreases, you have fewer pixels to draw, which means that smaller sizes should be less detailed. For instance, the smaller size Calendar app icon is not as detailed as the larger size, where you can see numbers for the days of the month, highlights in the metal rings, and lines at the bottom of the pile to indicate more pages. Each image is appropriately drawn for the canvas size.  
![](images/_page_118_Picture_2.jpeg)  
#### <span id="page-118-0"></span>Create High-Resolution Artwork from Existing Assets  
If you have an existing set of app icon resources, the following techniques can help you get great results as you create high-resolution versions of your artwork.  
**Scale up your original artwork and then redraw.** Using the nearest-neighbor scaling algorithm, scale your original artwork to 200%. This works well if the original artwork was not created with vector shapes and does not include layer effects. The result is a large, pixelated image on top of which you can draw matching high-resolution art. This is a good way to begin because it allows you to preserve the original layout of your design.  
If the original artwork was created with vector shapes or includes layer effects, you can use the default scaling algorithm instead of the nearest-neighbor algorithm.  
**Add detail and depth.** Don't hesitate to draw very small elements, because the high-resolution version of your artwork allows much more room for fine details. For example, a 1-pixel dot in your original image becomes a 4-pixel dot (that is, 2x2 pixels) in the larger version.  
**Consider softening scaled-up elements.** If, for example, you have a sharp, 1-pixel dividing line in your original artwork, it might have the boldness you want when it isscaled to a 2-pixel line. But forsome lines and elements, you might want to soften the scaled results by feathering or even leaving the element at the smaller size.  
**Consider adding blur for better results in effects such as engravings and drop shadows.** For example, text engraving istypically done by shifting a duplicate image of the text by 1 pixel. Scaled up, thisshift would result in an engraving width of 2 pixels, which is likely to look very sharp and unrealistic at a higher resolution. To improve this, you can leave the shift as-is (that is, at 1 pixel), but add a 1-pixel blur to soften the engraving. This still results in a 2-pixel-wide engraving effect, but the outer pixel now looks more like it is only half a pixel wide, which results in a better sense of dimensionality.  
#### <span id="page-119-0"></span>Create High-Resolution Artwork from Scratch  
If you do not have an existing set of icon resources, the following tips can help you create standard- and high-resolution versions of your app icon.  
**Start with a large master art file and scale it down to the smaller sizes.** It's especially useful to create your master image in a dimension that is a multiple of the icon sizes you need. For example, to create icons in the recommended sizes listed in [Table](#page-117-0) 5-1 (page 118), first create a 1024x1024 pixel version of your master file.  
**Use an appropriate grid size.** As you create the master image, using a grid ensures that you get sharp lines on important pieces of the design, like the outline. As you scale down, you'll be able to keep each smaller icon version crisp, and reduce the amount of retouching and sharpening you need to do.  
In your image-editing app, set up an 8-pixel grid, which means each block in the grid measures 8x8 pixels and represents 1 pixel in the 128x128 pixel icon. As you create your master file, "snap" the image to the grid and keep it within the boundaries to minimize the half pixels and blurry details that can result when you scale it down.  
**Redraw art as you scale down.** If you're not satisfied with the results when you scale down art to the 32x32 pixel and 16x16 pixel sizes, redraw the image at these sizes instead. If you decide to do this, setting up the proper grid can still help reduce extra work. For example, using a 32-pixel grid works well for creating the 32x32 pixel size, and a 64-pixel grid works well for creating the 16x16 pixel size.  
#### <span id="page-120-0"></span>Redesign Your iOS Artwork for OS X  
If you are creating an OS X version of an iOS app, design an icon that users recognize. Do not simply reuse your iOS app icon. In particular, your icon should not appear in a rounded rectangle. App Store, Calendar, and Contacts use icons for OS X and iOS that are recognizable, yet distinct from one another.  
![](images/_page_120_Picture_3.jpeg)