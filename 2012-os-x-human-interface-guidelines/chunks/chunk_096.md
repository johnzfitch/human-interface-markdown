<!-- Chunk 96 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 804 -->
If your app includes a sidebar (or source list), you need to design icons to display in it. For example, the Mail app contains several icons that represent the user's mailboxes, RSS feeds, and reminders.  
![](images/_page_124_Picture_3.jpeg)  
Sidebar icons are small and streamlined, but they provide more internal detail and a more realistic outline than the icons that go inside of toolbar controls. To achieve this look, try imagining an X-ray of the object you have in mind, then use transparency to capture the details.  
As with the icons that can be used inside toolbar controls, the system applies various effects to sidebar icons. To help you understand how these effects can change the appearance of a sidebar icon, consider the Finder Home icon, shown here in its unprocessed state:  
![](images/_page_124_Picture_6.jpeg)  
After the system applies the inactive appearance to the Home icon, it looks like this:  
![](images/_page_125_Picture_2.jpeg)  
Follow these guidelines as you design your sidebar icons:  
- Use black combined with transparency (that is, alpha values) to suggest details.
- Make the outline sharp and clear.
- Use a straight-on perspective.
- PDF format is recommended.
- Create your icons in three sizes: 16x16, 18x18, and 32x32 pixels (if using PDF).  
**Note:** When you're designing a sidebar icon, it's recommended that you use black, which makes it easier to discern details and outlines. However, you can use any color to create your icons, because the system ignores the color and pays attention only to the alpha values that you add.  
If you create yoursidebar iconsin PDF format, OS X will automatically scale your icon for high-resolution display. You do not need to provide high-resolution versions. However, if you use PNG format for your icons, you will need to supply the following resources: 16x16, 16x16@2x, 18x18, 18x18@2x, 32x32, and 32x32@2x. PNG format is only recommended for designsthat are very intricate and require effectslike shading, textures, and highlights.  
Be sure to invert yoursidebar icon to make sure it looks good and still makessense when the values are flipped. You need to check this because a sidebar icon'sselected appearance isthe inverse of its unselected appearance. For example, the Trash icon in the Mail sidebar has the following appearance when it is unselected:  
![](images/_page_125_Picture_12.jpeg)  
But when it is selected, the Trash icon is inverted:  
![](images/_page_125_Picture_14.jpeg)  
If necessary, provide an alternate design for the selected appearance of your sidebar icon. For example, the Desktop icon in the Finder sidebar is represented by two separate images to ensure that the icon conveys the same message in both selection states. Specifically, the unselected version of the Desktop icon shows a row of white Dock icons along the bottom edge:  
![](images/_page_126_Picture_2.jpeg)  
If this icon were inverted, the Dock icons would become hollow black squares with white outlines, and they would no longer convey the same meaning. So the Desktop icon also includes a version that's designed to preserve the appearance of the Dock icons when the colors are inverted:  
![](images/_page_126_Picture_4.jpeg)