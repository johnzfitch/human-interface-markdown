<!-- Chunk 142 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 1381 -->
Every app needs a beautiful, memorable app icon that attracts people in the App Store and stands out on their Home screen. iOS can use versions of the app icon in Game Center, search results, Settings, and to represent app-created documents.  
![](images/_page_208_Picture_2.jpeg)  
**Note:** An app uses the same app icon in all versions of iOS that it supports. If you decide to redesign the app icon for the iOS 7 version of your app, the new icon should replace the old one even if the app displays different UI in different versions of iOS.  
**For the best results, enlist the help of a professional graphic designer.** An experienced graphic designer can help you develop an overall visual style for your app and apply that style to all the icons and images in it. **Use universal imagery that people will easily recognize.** In general, avoid focusing on a secondary or obscure aspect of an element. For example, the Mail app icon uses an envelope, not a rural mailbox, a mail carrier's bag, or a post office symbol.  
**Embrace simplicity.** In particular, avoid cramming lots of different imagesinto your icon. Find a single element that capturesthe essence of your app and expressthat element in a simple, unique shape. Add details cautiously. If an icon's content or shape is overly complex, the details can become confusing and may appear muddy at smaller sizes.  
![](images/_page_209_Picture_3.jpeg)  
**Tip:** To test the appearance of your app icon at small sizes, move it into a folder on the Home screen. Even better, move several app icons into a folder and see if your app icon looks good and remains distinctive.  
**Create an abstract interpretation of your app's main idea.** It rarely works well to use a photo or screenshot in an app icon because photographic details can be very hard to see at small sizes. Typically, it's better to interpret reality in an artistic way, because doing so lets you emphasize the aspects of the subject that you want users to notice.  
**If you want to portray real substances, do it accurately.** Icons that depict real objects should accurately replicate the characteristics ofsubstancessuch asfabric, glass, paper, and metal, and convey the object's weight and feel.  
**Make sure the app icon looks good on a variety of backgrounds.** Don't just test your icon on a light or dark background because you can't predict which wallpaper people will choose.  
**Avoid transparency.** An app icon should be opaque. If the icon's boundaries are smaller than the recommended sizes—or you use transparency to create "see-through" areas—the resulting icon can appear to float on a black background, which tends to look especially unattractive on the beautiful wallpapers that users choose.  
**Don't use iOS interface elements in your artwork.** You don't want users to confuse your icons or images with the iOS UI.  
**Don't use replicas of Apple hardware products in your artwork.** The symbols that represent Apple products are copyrighted and can't be reproduced in your icons or images. In general, it's a good idea to avoid replicas of any specific devices in your artwork, because these designs change frequently and icons that are based on them can quickly look dated.  
**Don't reuse iOS app icons in your interface.** It can be confusing to users to see the same icon used to mean slightly different things in multiple locations throughout the system.  
With the exception of the App Store icon—which must be named iTunesArtwork—you can name an app icon anything you want. As long as you use the CFBundleIcons key to declare the names and you add the @2x suffix to the names of all high-resolution icons, iOS chooses an icon based on whether itssize is appropriate for the intended usage. To learn more about icon naming, see "App Icons" in *iOS App Programming Guide* .  
**Create different sizes of the app icon for different devices.** If you're creating a universal app, you need to supply app icons in all four sizes.  
For iPhone and iPod touch, both of these sizes are required:  
- 120 x 120 pixels
- 60 x 60 pixels (standard resolution)  
For iPad, both of these sizes are required:  
- 152 x 152
- 76 x 76 pixels (standard resolution)  
When iOS displays an app icon on the Home screen of a device, it automatically applies a mask that rounds the corners. Make sure your icon has 90° corners so it looks good after the mask is applied. For example:  
A 120 x 120 pixel icon before the mask is applied A 120 x 120 pixel icon after the mask is applied  
![](images/_page_210_Picture_11.jpeg)  
![](images/_page_210_Picture_12.jpeg)  
**Create a large version of your app icon for display in the App Store.** Although it's important that this version be instantly recognizable as your app icon, it can be subtly richer and more detailed. There are no visual effects added to this version of your app icon.  
For the App Store, create a large version of your app icon in two sizes so that it looks good on all devices:  
- 1024 x 1024 pixels
- 512 x 512 pixels (standard resolution)  
Be sure to name this version of your app icon iTunesArtwork@2x and iTunesArtwork, respectively.  
**Note:** iOS might also use the large image in other ways. In an iPad app, for example, iOS uses the large image to generate the large document icon.  
If you're developing an app for ad-hoc distribution (that is, to be distributed in-house only, not through the App Store), you must also provide the large versions of your app icon. This icon identifies your app in iTunes.