<!-- Chunk 198 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 777 -->
As much as possible, you should use the system-provided buttons and icons to represent standard tasks in your application. For a complete list of standard buttons and icons, and guidelines on how to use them, see ["System-Provided](#page-134-0) Buttons and Icons" (page 135).  
Of course, not every task your application performsis a standard one. If your app supports custom tasks users need to perform frequently, you need to create custom icons that represent these tasks in your toolbar or navigation bar. Similarly, if your app displays a tab bar that allows users to switch among custom application modes or custom subsets of data, you need to design tab bar icons that represent these modes or subsets.  
Before you create the art for your icon, you need to spend some time thinking about what it should convey. As you consider designs, aim for an icon that is:  
- **Simple and streamlined**. Too many details can make an icon appear sloppy or indecipherable.
- **Not easily mistaken for one of the system-provided icons**. Users should be able to distinguish your custom icon from the standard icons at a glance.
- **Readily understood and widely acceptable**. Strive to create a symbol that most users will interpret correctly and that no users will find offensive.  
**Important:** Be sure to avoid using images that replicate Apple products in your designs. These symbols are copyrighted and product designs can change frequently.  
After you've decided on the appearance of your icon, follow these guidelines as you create it:  
- Use pure white with appropriate alpha transparency.
- Do not include a drop shadow.  
#### **CHAPTER 8**  
Custom Icon and Image Creation Guidelines  
- Use anti-aliasing.
- If you decide to add a bevel, be sure that it is 90° (to help you do this, imagine a light source positioned at the top of the icon).  
For toolbar and navigation bar icons, create an icon in the following sizes:  
- For iPhone and iPod touch:
- About 20 x 20 pixels
- About 40 x 40 pixels (high resolution)
- For iPad:
- About 20 x 20 pixels  
For tab bar icons, create an icon in the following sizes:  
- For iPhone and iPod touch:
- About 30 x 30 pixels
- About 60 x 60 pixels (high resolution)
- For iPad:
- About 30 x 30 pixels  
**Note:** The icon you provide for toolbars, navigation bars, and tab bars is used as a mask to create the icon you see in your application. It is not necessary to create a full-color icon.  
**Don't include separate pressed or selected appearances for your icons**. iOS automatically provides these appearancesfor itemsin navigation bars, toolbars, and tab bars,so you do not need to provide them. Because these visual effects are automatic, you cannot change their appearance.  
<span id="page-149-0"></span>**Give all icons in a bar a similar visual weight**. Aim to balance the overall size, level of detail, and use of solid regions across all icons that can appear in a specific bar. In general, it does not look good to combine in the same bar iconsthat are large and blocky, and completely filled, with iconsthat are small, detailed, and unfilled.