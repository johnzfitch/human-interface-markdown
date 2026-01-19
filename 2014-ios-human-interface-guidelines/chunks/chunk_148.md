<!-- Chunk 148 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 1461 -->
iOS defines lots of standard bar-button icons, such as Refresh, Share, Add, and Favorites. As much as possible, you should use these buttons and icons to represent standard tasks in your app. (To learn more about the standard buttons and icons you can use, see "Toolbar and [Navigation](#page-147-0) Bar Buttons" (page 148) and ["Tab](#page-151-0) Bar [Icons"](#page-151-0) (page 152).)  
If your app includes tasks or modes that can't be represented by a standard icon—or if the standard icons don't coordinate with your app's style—you can design your own bar button icons. At a high level, you should aim for an icon design that is:  
- **Simple and streamlined.** Too many details can make an icon appear sloppy or indecipherable.
- **Not easily mistaken for one of the system-provided icons.** Users should be able to distinguish your custom icon from the standard icons at a glance.
- **Readily understood and widely acceptable.** Strive to create a symbol that most users will interpret correctly and that no users will find offensive.  
**Important:** Be sure to avoid using images that replicate Apple products in your designs. These symbols are copyrighted and product designs can change frequently.  
Whether you use only custom icons or a mix of custom and standard, all icons in your app should look like they belong to the same family in terms of perceived size, level of detail, and visual weight.  
For example, take a look at the family of iOS bar icons and notice how the similarities in size, detail, and weight produce a sense of harmonious unity:  
![](images/_page_217_Picture_9.jpeg)  
To create a coherent family of icons, consistency is key: As much as possible, each icon should use the same perspective and the same stroke weight. To ensure that all icons have a consistent perceived size, you may have to create some icons at different actual sizes. For example, the set of system provided icons shown here all have the same perceived size, even though the Favorites and Voicemail icons are actually a bit larger than the other three icons.  
![](images/_page_218_Picture_2.jpeg)  
![](images/_page_218_Picture_3.jpeg)  
![](images/_page_218_Picture_4.jpeg)  
![](images/_page_218_Picture_5.jpeg)  
![](images/_page_218_Picture_6.jpeg)  
If you're designing a custom tab bar icon, you should provide two versions—one for the unselected appearance and one for the selected appearance. The selected appearance is often a filled-in version of the unselected appearance, but some designs call for variations on this approach.  
![](images/_page_218_Picture_8.jpeg)  
![](images/_page_218_Picture_9.jpeg)  
![](images/_page_218_Picture_10.jpeg)  
![](images/_page_218_Picture_11.jpeg)  
To create a filled-in version of an icon that has interior details (such as the Radio icon) invert the details so they retain their prominence in the selected version. The Keypad icon also has interior details, but the selected version would be confusing and hard to recognize if its background was filled in and the circles became white outlines.  
Sometimes, a design needs a slight alteration to look good when it's selected. For example, because the Timer and Podcasts icons include open areas, the selected versions condense the strokes a bit to fit into a circular enclosure.  
![](images/_page_218_Picture_13.jpeg)  
![](images/_page_218_Picture_14.jpeg)  
![](images/_page_218_Picture_15.jpeg)  
![](images/_page_218_Picture_16.jpeg)  
![](images/_page_218_Picture_17.jpeg)  
![](images/_page_218_Picture_18.jpeg)  
![](images/_page_218_Picture_19.jpeg)  
![](images/_page_218_Picture_20.jpeg)  
![](images/_page_218_Picture_21.jpeg)  
If an icon becomes less recognizable when it's filled in, a good alternative is to use a heavier stroke to draw the selected version. For example, the selected versions of the Voicemail and Reading List icons are drawn with a 4-pixel stroke, instead of the 2-pixel stroke that was used to draw the unselected versions.  
![](images/_page_218_Picture_23.jpeg)  
![](images/_page_218_Picture_24.jpeg)  
![](images/_page_218_Picture_25.jpeg)  
![](images/_page_218_Picture_26.jpeg)  
Sometimes, an icon's shape has details that don't look good in a stroked outline. When this is the case—as it is for the Music and Artists icons—you can use the filled-in appearance for both versions of the icon. It's easy for usersto distinguish the selected and unselected appearances of such icons because the selected appearance is darker and gets the tint.  
A custom icon that you create for a toolbar, navigation bar, or tab bar is also known as a **template** image, because iOS usesit as a mask to produce the icon you see when your app runs. If you create a full-color template image, iOS ignores the color.  
To design a custom bar icon, follow these guidelines:  
- Use pure white with appropriate alpha transparency.
- Not include a drop shadow.
- Use antialiasing.  
If you want to create a bar icon that looks like it's related to the iOS 7 icon family, use a very thin stroke to draw it. Specifically, a 2-pixel stroke (high resolution) works well for detailed icons and a 3-pixel stroke works well for less detailed icons.  
Regardless of the icon's visual style, create a toolbar or navigation bar icon in the following sizes:  
- About 44 x 44 pixels
- About 22 x 22 pixels (standard resolution)  
Regardless of the icon's visual style, create a tab bar icon in the following sizes:  
- About 50 x 50 pixels (96 x 64 pixels maximum)
- About 25 x 25 pixels (48 x 32 pixels maximum) for standard resolution  
Don't include text in a custom tab bar icon. Instead, use the tab bar item APIs to set the title for each tab (for example, initWithTitle:image:tag:). If you need to adjust the automatic layout of the title, you can use the title adjustment APIs, such as setTitlePositionAdjustment:.