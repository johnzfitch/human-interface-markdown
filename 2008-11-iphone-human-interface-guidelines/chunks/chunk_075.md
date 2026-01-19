<!-- Chunk 75 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 670 -->
When possible, you should use the system-provided buttons and icons in navigation bars, toolbars, and tab bars. iPhone OS provides a wide range ofstandard buttons and iconsthat users associate with standard tasks and modes supported in the built-in applications. If your application supports standard functions, such as refreshing a content-area view or deleting an item, or displays different subsets of data, such as contacts or bookmarks, be sure to use the appropriate system-provided button or icon to represent it. For a complete list of standard buttons and icons, and guidelines on how to use them, see ["System-Provided](#page-104-0) Buttons and [Icons"](#page-104-0) (page 105).  
Of course, not every task your application performs is a standard one. If your application supports custom tasks users need to perform frequently, you need to create custom icons that represent these tasks in your toolbar or navigation bar. Similarly, if your application displays a tab bar that allows users to switch among custom application modes or custom subsets of data, you need to design tab bar icons that clearly describe these modes or subsets. This section gives you some guidance on how to design icons that work well in navigation bars, toolbars, and tab bars.  
Before you create the art for your icon, you need to spend some time thinking about what it should convey. As you consider designs, aim for an icon that is:  
- Simple and streamlined. Too many details can make an icon appear sloppy or indecipherable.
- Not easily mistaken for one of the system-provided icons. Usersshould be able to distinguish your custom icon from the standard icons at a glance.
- Readily understood and widely acceptable. Strive to create a symbol that most users will interpret correctly and that no users will find offensive.  
After you've decided on the appearance of your icon, follow these guidelines as you create it:  
- Use the PNG format.
- Use white with appropriate alpha and no shadow.
- Use anti-aliasing.
- For toolbar and navigation bar icons, create an icon that measures about 20 x 20 pixels.  
For tab bar icons, create an icon that measures about 30 x 30 pixels.  
**Note:** The icon you provide for toolbars, navigation bars, and tab bars is used as a mask to create the icon you see in your application. It is not necessary to create a full-color icon.  
iPhone OS automatically provides the pressed or selected appearance for items in navigation bars, toolbars, and tab bars,so you only need to provide a single version of an icon. Because these visual effects are automatic, you cannot change their appearance.  
#### **CHAPTER 11**  
Creating Custom Icons and Images