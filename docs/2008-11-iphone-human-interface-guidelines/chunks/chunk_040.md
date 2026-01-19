<!-- Chunk 40 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 857 -->
A navigation bar appears at the upper edge of an application screen, just below the status bar. A navigation bar usually displays the title of the current view and can contain controls that act on the view's contents, in addition to navigational controls when appropriate. Navigation bars are especially useful in productivity applications(described in "Productivity [Applications"](#page-18-0) (page 19)), because these applicationstypically arrange information in a hierarchy.  
Navigation bars have two purposes:  
- To enable navigation among different views in an application
- To provide controls that manage the items in a view  
Figure 6-3 shows examples of both these uses.  
<span id="page-62-0"></span>**Figure 6-3** Navigation bars can contain navigational controls and controls to manage content  
![](images/_page_62_Figure_3.jpeg)  
![](images/_page_62_Figure_4.jpeg)  
<span id="page-62-1"></span>A navigation bar can display just the title of the current view, centered along its width, as shown in Figure 6-4. The initial view in a productivity application should include a navigation bar that displays only the title of the first view because the user hasn't yet navigated to another location.  
**Figure 6-4** A navigation bar displays the title of the current view  
![](images/_page_62_Picture_7.jpeg)  
<span id="page-62-2"></span>As soon as the user navigates to another view, the navigation bar should change the title to the title of the new location, and should provide a back button labeled with the title of the previous location. For example, Figure 6-5 showsthe navigation bar in Date & Time settings, which is one of the settings categoriesin General settings.  
**Figure 6-5** A navigation bar can contain a navigational control  
![](images/_page_62_Picture_10.jpeg)  
Optionally, you can choose to display a second button to the right of the title. Also, if you do not need to display a back button (because your application does not support hierarchical navigation), you can opt instead to display a button that affects the contents of the view, such as an Edit button, to the left of the title. Figure 6-6 shows an example of this.  
#### **CHAPTER 6**  
Navigation Bars, Tab Bars, Toolbars, and the Status Bar  
<span id="page-63-1"></span>**Figure 6-6** A navigation bar can contain controls that manage the content in the view  
![](images/_page_63_Picture_3.jpeg)  
To learn how to implement a navigation bar for multiple views, see Using Navigation Controllers.  
As you can see in the illustrations above, controls in a navigation bar include a bezel around them. In iPhone OS, this style is called the bordered style. All controls in a navigation bar should use the bordered style. In fact, if you place a plain (borderless) control in a navigation bar, it will automatically convert to the bordered style.  
You can design your own iconsfor use in navigation-bar buttons, or you can take advantage of the predefined buttons iPhone OS provides. See "Standard Buttons for Use in Toolbars and [Navigation](#page-105-0) Bars" (page 106) for more information on the buttons available to you.  
Although you can specify a font for all text displayed in a navigation bar, it's recommended that you use the system font for maximum readability. When you use the appropriate UIKit programming interfaces to create your navigation bar, the system font is used automatically to display the title.