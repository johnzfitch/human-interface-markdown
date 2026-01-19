<!-- Chunk 48 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 907 -->
Safari on iOS provides a preeminent mobile web-viewing experience on iOS-based devices. People appreciate the crisp text and sharp images and the ability to adjust their view by rotating the device or pinching and tapping the screen.  
Standards-based websites display well on iOS-based devices. In particular, websites that detect the device and do not use plug-ins look great on both iPhone and iPad with little, if any, modification.  
In addition, the most successful websites typically:  
- Set the viewport appropriately for the device, if the page width needs to match the device width
- Avoid CSS fixed positioning, so that content does not move offscreen when users zoom or pan the page
- Enable a touch-based UI that does not rely on pointer-based interactions  
Sometimes, other modifications can be appropriate. For example, web apps always set the viewport width appropriately and often hide the UI of Safari on iOS. To learn more about how to make these modifications, see "Configuring the Viewport" and "Configuring Web Applications" in *Safari Web Content Guide*.  
Websites adapt the desktop web experience to Safari on iOS in other ways, too:  
Case Studies: Transitioning to iOS  
**Using custom CSS to provide adaptableUI**. Different UI elements can be suitable for different environments. For example, the Apple website includes a page that displays movie trailers users can watch. When viewed in Safari on the desktop, users can click the numbers or the previous and next controls to see additional trailers:  
![](images/_page_41_Picture_3.jpeg)  
When viewed on iPhone, the next, previous, and number controls are replaced by prominent, easy-to-use buttons with symbols that echo the style of built-in controls (such as the detail disclosure indicator and the page indicator):  
![](images/_page_41_Picture_5.jpeg)  
**Accommodating the keyboard in Safari on iOS**. When a keyboard and the form assistant are visible, Safari on iPhone displays your webpage in the area below the URL text field and above the keyboard and form assistant.  
![](images/_page_41_Figure_7.jpeg)  
Case Studies: Transitioning to iOS  
When a keyboard and the form assistant are not displayed, there is an additional 216 pixels of vertical space available (in portrait orientation) for the display of your webpage. In landscape orientation, two of the values differ: The keyboard height is 162 pixels, and the form assistant height is 32 pixels.  
**Accommodating the pop-up menu control in Safari on iOS**. In Safari on the desktop, a pop-up menu that contains a large number of items displays as it does in a Mac OS X application; that is, the menu opens to display all items, extending past the window boundaries, if necessary. In Safari on iOS, a pop-up menu is displayed using native elements, which provides a much better user experience. For example, on iPhone, the pop-up menu appears in a **picker**, a list of choices from which the user can pick, as shown below.  
![](images/_page_42_Picture_4.jpeg)  
On iPad, the pop-up menu displays in a popover, as shown below.  
![](images/_page_43_Picture_2.jpeg)  
**Using lists to display data in iPhone web apps**. iOS users are accustomed to lists in native apps, so when they see lists in web apps, they're more likely to think that the web content is an application. On iPhone, lists appear edge to edge or inside rounded rectangles. Each style is defined by its own metrics.  
#### **Edge-to-edge list**  
![](images/_page_44_Picture_3.jpeg)  
#### **Rounded rectangle list**  
![](images/_page_44_Figure_5.jpeg)  
#### **CHAPTER 4**  
Case Studies: Transitioning to iOS