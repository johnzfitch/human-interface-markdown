<!-- Chunk 95 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 1542 -->
Toolbar items give users easy access to frequently used commands (to learn more about the concepts behind toolbar design, see ["Designing](#page-177-0) a Toolbar" (page 178)). To represent these commands in a toolbar, you need small, unambiguous icons that users can easily distinguish and remember.  
To accommodate different app styles and usages, OS X provides two styles of toolbar items: toolbar controls and freestanding icons that behave as buttons. Don't mix styles of toolbar items—use one or the other in your app. To learn more about the toolbar controlsthat can contain icons,see ["Window-Frame](#page-237-0) Controls" (page 238). To learn more about freestanding icons, see "Icon [Button"](#page-244-0) (page 245).  
In general, main and document windows achieve a subtle appearance by using streamlined icons within toolbar buttons controls. For example, the Mail toolbar uses several small icons in toolbar buttons and segmented controls.  
![](images/_page_120_Picture_6.jpeg)  
Freestanding icons are occasionally used in the toolbar of a main or document window, such as the Keynote toolbar shown here.  
![](images/_page_120_Picture_8.jpeg)  
Freestanding icons tend to be more common in the toolbars of preferences windows, where they are often used as pane switchers. For example, the Safari preferences window displays several icons that give users access to different preferences categories.  
![](images/_page_120_Picture_10.jpeg)  
The best toolbar icons use familiar visual metaphors that are directly related to the app commands they represent. When a toolbar icon depicts an identifiable, real-world object or recognizable UI element, it gives first-time users a clue to its function and helps experienced users remember it.  
**Identify parts of the user's mental model that lend themselves to visual representation.** Users often form a mental model of your app'stask based on real-world actions. (To learn more about the mental model concept, see ["Mental](#page-26-2) Model" (page 27).) For example, the iTunes toolbar shown below displays rewind, play, and fast-forward controls that use symbols similar to those users see and touch on physical devices.  
![](images/_page_121_Picture_3.jpeg)  
**Make toolbar icons distinct, yet harmonious.** When each icon is easily distinguishable from the others, users learn to associate it with its purpose and locate it quickly. Variations in shape and image help to differentiate one toolbar icon from another. At the same time, an app's toolbar icons should harmonize as much as possible in their perspective, size, and visual weight. This holds true whether the icon is freestanding or in a toolbar control.  
**For icons to put inside toolbar controls, create streamlined template images.** These images should convey meaning through outline and contour, and they should include very little internal detail.  
It's best to make your icon as solid as possible (that is, with very little transparency or alpha values) so that it will look good when the system applies effects, such as the inactive appearance. An icon that uses too much transparency can look disabled when the system applies either the active or inactive appearance to it. To help you create a solid icon, start by imagining the shadow your object would cast. If the contours of the shadow clearly show what the object is, you don't need to add any transparency.  
To help you understand how the system-applied effects can change the appearance of an icon, consider the Send icon in Mail, shown here in its unprocessed state:  
![](images/_page_121_Picture_8.jpeg)  
When the Send icon is in a toolbar button and the system applies the active, enabled appearance to it, it looks like this:  
![](images/_page_121_Picture_10.jpeg)  
As you design an icon to put inside a toolbar control, such as a button or segmented control, follow these guidelines:  
- Create icons that measure no more than 19x19 pixels.
- Make the outline sharp and clear.
- Use a straight-on perspective.
- Use black (add transparency only as necessary to suggest dimensionality).
- Use anti-aliasing.
- Use the PDF format.
- Make sure the image is visually centered in the control (note that visually centered might not be the same as mathematically centered).  
**Note:** When you're designing an icon for a toolbar control, it's recommended that you use black, which makes it easier to discern details and outlines. However, you can use any color to create your icons, because the system ignores the color and pays attention only to the alpha values you add.  
When you create an icon to put inside a toolbar control in PDF format, OS X will automatically scale your icon for high-resolution display. You don't need to provide a high-resolution version.  
You might be able to use a system-provided icon or image to represent a common task or a standard interface element in your toolbar controls, such as the connect via Bluetooth icon (that is, ). OS X provides many icons that can be used inside toolbar controls and a few icons that can be used as icon buttons in a toolbar. For more information about the images that are available and what they mean, see ["System-Provided](#page-318-0) Icons" (page 319).  
**For freestanding icons in a toolbar, create inviting images that are easy to identify.** Because freestanding toolbar icons don't need to fit within a toolbar control, you have a little more room to express them. As you design a freestanding icon for your toolbar, follow these guidelines:  
- Use a straight-on perspective.
- Make the outline sharp and clear.
- Use anti-aliasing.
- Use color judiciously to add meaning.
- Create icons for standard- and high-resolution displays. You need to supply two resources: 32x32 and 32x32@2x. See [Table](#page-116-1) 5-1 (page 117) for the corresponding canvas sizes.
- Use the PNG format.  
Although you use the straight-on perspective for the freestanding toolbar icons you design, if you use a recognizable icon from elsewhere in the interface in your toolbar, you should not change its appearance or perspective. That is, don't redesign a toolbar version of a well-known interface element.