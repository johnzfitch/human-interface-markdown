<!-- Chunk 134 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 647 -->
A **search field** accepts text from users, which can be used as input for a search (shown here in a toolbar).  
![](images/_page_214_Picture_5.jpeg)  
**Important:** A search field can be used in the window-frame area or in the window body. To learn more about controlsthat are designed specifically for use in window-frame areas,see Some [Controls](#page-176-1) Can Be Used on the [Window](#page-176-1) Frame (page 177).  
**API Note:** To define a search field in your code, use the NSSearchField class.  
#### A search:  
- Looks like a text field with rounded ends
- Can be configured to begin searching while the user isstill entering text, or to wait until the user isfinished
- Displays the magnifying icon in its left end by default
- Can also contain an icon the user clicks to cancel the search or clear the field  
Use a search field to enable search functionality within your app.  
**Decide when to start the search.** You can begin searching as soon as the user starts typing, or wait until the user presses Return or Enter. If searching occurs while the user is still typing, the behavior is more like a find in which results are filtered as the entered text becomes more specific. This behavior is especially useful when the search field is in a scope bar that focuses on a window's contents. If search should occur after the user finishes typing, you might want to enable a search term completion menu so that users can choose from commonly searched terms.  
**In general, avoid using a menu to display search history.** For privacy reasons, users might not appreciate having their search history displayed. You might instead use the menu to allow users to choose different types of searches or define the context or scope of a search. Note that a scope bar is well-suited to enabling this type of searching. For more information, see [Searching](#page-130-0) In a Window (page 131).  
**Avoid supplying an introductory label.** Users are familiar with the distinctive appearance of a search field, so there is no need to label it. The exception to this is when you place a search field in a toolbar; in this case, you need to supply the label "Search" to be displayed when users customize the toolbar to show icons and text or text only.  
**Display placeholder text, if it helps users understand how search works in your app.** A search field can display a placeholder text in its left end. For example, the search field in the Safari toolbar can display one of three common search engines (users can choose the search engine they want to use in the search field menu).