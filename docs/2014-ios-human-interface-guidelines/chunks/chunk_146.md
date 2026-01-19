<!-- Chunk 146 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 659 -->
A launch image is a simple placeholder image that iOS displays when your app starts up. The launch image gives users the impression that your app is fast and responsive because it appears instantly and is quickly replaced by the first screen of your app.  
**Note:** You must provide at least one launch image. Typically, an iPhone app includes at least one launch image in portrait orientation; an iPad app includes at least one launch image in portrait orientation and at least one launch image in landscape orientation.  
Because iOS lets you supply different launch images for different uses, you give each image a name that specifies how it should be used. The format of the launch image filename includes modifiers you use to specify the device, resolution, and orientation of the image. To learn how to name launch images appropriately, see "App Launch (Default) Images" in *iOS App Programming Guide* .  
**Supply a plain launch image that improves the user experience.** In particular, the launch image isn't an opportunity to provide:  
- An "app entry experience," such as a splash screen
- An About window
- Branding elements, unless they are a static part of your app's first screen  
Because users are likely to switch among apps frequently, you should make every effort to cut launch time to a minimum, and you should design a launch image that downplaysthe experience rather than drawing attention to it.  
#### **Design a launch image that is identical to the first screen of the app,** except for:  
- **Text.** The launch image is static, so any text you display in it won't be localized.
- **UI elements that might change.** If you include elements that might look different when the app finishes launching, users can experience an unpleasant flash between the launch image and the first app screen.  
If you think that following these guidelines will result in a plain, boring launch image, you're right. Remember, the launch image doesn't provide you with an opportunity for artistic expression. It'ssolely intended to enhance the user's perception of your app as quick to launch and immediately ready for use. For example, Settings and Weather each supply a launch image that is little more than a static background image.  
![](images/_page_215_Picture_2.jpeg)  
**Create launch images in different sizes for different devices.** Launch images for all devices must include the status bar region. Create launch images in the following sizes:  
For iPhone 5 and iPod touch (5th generation):  
● 640 x 1136 pixels  
For other iPhone and iPod touch devices:  
- 640 x 960 pixels
- 320 x 480 pixels (standard resolution)