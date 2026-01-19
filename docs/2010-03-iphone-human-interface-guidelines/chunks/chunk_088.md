<!-- Chunk 88 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 911 -->
<span id="page-68-2"></span>A navigation bar can display just the title of the current view, centered along its width, as shown in Figure 6-4. The initial view in a productivity application should include a navigation bar that displays only the title of the first view because the user hasn't yet navigated to another location.  
**Figure 6-4** A navigation bar displays the title of the current view  
![](images/_page_68_Picture_10.jpeg)  
<span id="page-68-3"></span>As soon as the user navigates to another view, the navigation bar should change its title to the title of the new location, and should provide a back button labeled with the title of the previous location. For example, Figure 6-5 shows the navigation bar in Date & Time settings, which is in General settings.  
**Figure 6-5** A navigation bar can contain a navigational control  
![](images/_page_68_Picture_13.jpeg)  
Navigation Bars, Tab Bars, Toolbars, and the Status Bar  
The standard back button gives users a reliable way to return to the previous screen, so it's important to avoid altering the button's behavior. In particular, you should avoid creating a multi-segment back button, such as the one shown in Figure 6-6.  
<span id="page-69-0"></span>**Figure 6-6** A multi-segment back button is not recommended  
![](images/_page_69_Picture_4.jpeg)  
Using a multi-segment back button causes several problems:  
- The extended width of a multi-segment back button does not leave room for the title of the current screen.
- There is no way to indicate the selected state of an individual segment.
- The more segments there are, the smaller the hit region for each one, which makes it difficult for users to tap a specific one.
- Choosing which levels to display as users navigate deeper in the hierarchy is problematic.  
If you think users might get lost without a multi-segment back button that displays a type of breadcrumb path, it probably means that users must go too deeply into the information hierarchy to find what they need. To address this, you should flatten your information hierarchy.  
<span id="page-69-1"></span>In addition to a back button, a navigation bar can also contain a second button to the right of the title. If you do not need to display a back button (because your application does not support hierarchical navigation), you can opt instead to display a button that affects the contents of the view, such as an Edit button, to the left of the title. Figure 6-7 shows an example of this.  
**Figure 6-7** A navigation bar can contain controls that manage the content in the view  
![](images/_page_69_Picture_13.jpeg)  
To learn how to implement a navigation bar in your application, see "Navigation Controllers".  
As you can see in the illustrations above, buttons in a navigation bar include a bezel around them. In iPhone OS, this style is called the bordered style. All controls in a navigation bar should use the bordered style. In fact, if you place a plain (borderless) control in a navigation bar, it will automatically convert to the bordered style.  
You can design your own iconsfor use in navigation-bar buttons, or you can take advantage of the predefined buttons iPhone OS provides. See "Standard Buttons for Use in Toolbars and [Navigation](#page-123-0) Bars" (page 124) for more information on the buttons available to you.  
Although you can specify a font for all text displayed in a navigation bar, it's recommended that you use the system font for maximum readability. When you use the appropriate UIKit programming interfaces to create your navigation bar, the system font is used automatically to display the title.