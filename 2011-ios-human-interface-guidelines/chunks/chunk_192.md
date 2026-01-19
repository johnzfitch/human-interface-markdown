<!-- Chunk 192 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 1110 -->
An **application icon** is an icon users put on their Home screens and tap to start an application. This is a place where branding and strong visual design should come together into a compact, instantly recognizable, attractive package. Every application needs an application icon.  
**Note:** If your app is a game, its app icon is also used in Game Center.  
Try to balance eye appeal and clarity of meaning in your icon so that it'srich and beautiful and clearly conveys the essence of your application's purpose. Also, it's a good idea to investigate how your choice of image and color might be interpreted by people from different cultures.  
**Create different sizes of your application icon for different devices**. If you're creating a universal application, you need to supply application icons in all three sizes.  
For iPhone and iPod touch both of these sizes are required:  
- 57 x 57 pixels
- 114 x 114 pixels (high resolution)  
For iPad, this size is required:  
● 72 x 72 pixels  
Custom Icon and Image Creation Guidelines  
When iOS displays your application icon on the Home screen of a device, it automatically adds the following visual effects:  
- Rounded corners
- Drop shadow
- Reflective shine (unless you prevent the shine effect)  
For example, a simple 57 x 57 pixel iPhone application icon might look like this:  
![](images/_page_142_Picture_7.jpeg)  
When it's displayed on an iPhone Home screen, iOS adds rounded corners, a drop shadow, and a reflected shine. So the same application icon would look like this:  
![](images/_page_142_Picture_9.jpeg)  
**Note:** You can prevent iOS from adding the shine to your application icon. To do this, you need to add the UIPrerenderedIcon key to your application's Info.plist file (to learn about thisfile,see "The Information Property List" in *iOS Application Programming Guide*).  
The presence (or absence) of the added shine does not change the dimensions of your application icon.  
**Ensure your icon is eligible for the visual enhancements iOS provides**. You should produce an image that:  
- Has 90° corners
- Does not have any shine or gloss (unless you've chosen to prevent the addition of the reflective shine)
- Does not use alpha transparency  
**Give your application icon a discernible background**. Icons with visible backgroundslook best on the Home screen primarily because of the rounded corners iOS adds. This is because uniformly rounded corners ensure that all the icons on a user's Home screen have a consistent appearance that invites tapping. If you create an icon with a background that disappears when it's viewed on the Home screen, users don'tsee the rounded corners. Such icons often don't look tappable and tend to interfere with the orderly symmetry of the Home screen that users appreciate.  
**Be sure your image completely fills the required area**. If your image boundaries are smaller than the recommended sizes, or you use transparency to create "see-through" areas within them, your icon can appear to float on a black background with rounded corners.  
For example, an application might supply an icon on a transparent background, like the blue star on the far left. When iOS displays this icon on a Home screen, it looks like the image in the middle (if no shine is added) or it looks like the image on the right (if shine is added).  
#### **CHAPTER 8**  
Custom Icon and Image Creation Guidelines  
![](images/_page_143_Picture_2.jpeg)  
![](images/_page_143_Picture_3.jpeg)  
![](images/_page_143_Picture_4.jpeg)  
An icon that appears to float on a visible black background looks especially unattractive on a Home screen that displays a custom picture.  
**Create a 512 x 512 pixel version of your application icon for display in the App Store**. Although it's important that this version be instantly recognizable as your application icon, it can be subtly richer and more detailed. There are no visual effects added to this version of your application icon.  
If you're developing an application for ad-hoc distribution (that is, to be distributed in-house only, not through the App Store), you must also provide a 512 x 512 pixel version of your application icon. This icon identifies your application in iTunes.  
iOS might also use this large image in other ways. In an iPad application, for example, iOS uses the 512 x 512 pixel image to generate the large document icon, if a custom document icon is not supplied.