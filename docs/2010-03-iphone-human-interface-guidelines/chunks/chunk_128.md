<!-- Chunk 128 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 592 -->
A search bar is a field that acceptstext from users, which your application can use asinput for a search. When the user taps a search bar, a keyboard appears; when the user is finished typing search terms, the input is handled in an application-specific way. (For guidelines on handling search in your application,see ["Providing](#page-50-0) Search and [Displaying](#page-50-0) Search Results" (page 51).)  
By default, a search bar displays the search icon on the left side. In addition, a search bar can display a few optional elements:  
- Placeholder text. This text might state the function of the control (for example, "Search") or remind users in what context they are searching (for example, "YouTube" or "Google").
- The Bookmarks button. This button can provide a shortcut to information users want to easily find again. For example, the Bookmarks button in the Maps search mode gives access to bookmarked locations, recent searches, and contacts.
- The Clear button. Most search bars include a Clear button that allows users to erase the contents of the search bar with one tap.
- A descriptive title, called a prompt, that appears above the search bar. For example, a prompt can be a short phrase that provides introductory or application-specific context for the search bar.  
<span id="page-116-0"></span>Figure 9-10 shows a search bar that includes customized placeholder text, a Bookmarks button, and the default search icon.  
![](images/_page_116_Picture_7.jpeg)  
![](images/_page_116_Picture_8.jpeg)  
By default, the Bookmarks and Clear buttons interact in the following ways:  
- When the search bar contains any non-placeholder text, the Clear button is visible so users can erase the text. If there is no user-supplied or non-placeholder text in the search bar, the Clear button is hidden because there is no need to erase the contents of the search bar.
- The Bookmarks button is visible only when there is no user-supplied or non-placeholder text in the search bar. Thisis because the Clear button is visible when there istext in the search bar that users might want to erase.  
You can customize a search bar by specifying one of the standard-color background styles, such as:  
■ Blue (the default gradient that coordinates with the default appearance of toolbars and navigation bars). The default background style is shown in Figure 9-10.