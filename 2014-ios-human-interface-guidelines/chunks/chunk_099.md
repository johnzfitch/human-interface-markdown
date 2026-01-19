<!-- Chunk 99 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 688 -->
A **search bar** accepts text from users, which can be used as input for a search (shown here with placeholder text).  
![](images/_page_152_Picture_4.jpeg)  
**API Note:** To learn how to define a search bar in your code, see "Search Bars".  
A search bar can display optional elements, such as these:  
● **Placeholder text.** This text might state the function of the control (for example, "Search" as shown above) or remind users in what context they are searching (for example, "Google").  
● **The Bookmarks button.** This button can provide a shortcut to information users want to easily find again. For example, the Bookmarks button in the Mapssearch mode gives accessto bookmarked locations, recent searches, and contacts.  
![](images/_page_153_Picture_2.jpeg)  
The Bookmarks button is visible only when there is no user-supplied or nonplaceholder text in the search bar. When the search bar contains such text, the Clear button appears so that users can erase the text.  
● **The Clear button.** Most search bars include a Clear button that lets users erase the contents of the search bar with one tap.  
![](images/_page_153_Picture_5.jpeg)  
When the search bar contains any nonplaceholder text, the Clear button is visible so users can erase the text. If there is no user-supplied or nonplaceholder text in the search bar, the Clear button is hidden.  
● **The results list icon.** This icon indicates the presence of search results. When users tap the results list icon, an app can display the results of their most recent search.  
![](images/_page_153_Picture_8.jpeg)  
● **A prompt.** A descriptive title, called a *prompt*, can be placed above the search bar. A prompt is a short, complete sentence that provides introductory or app-specific context for the search bar.  
![](images/_page_153_Picture_10.jpeg)  
Use a search bar to enable search in your app. Don't use a text field to enable search because it doesn't have the standard search bar appearance that users expect.  
In iOS 7 and later, using UISearchDisplayController makes it easy to put a search bar in a navigation bar. Note that when a search display controller's view controller is contained within a navigation controller—as isthe case in Mail—the search bar automatically transitionsinto the navigation bar when usersinitiate a search.  
**Choose a search bar style that complements the importance of search in your app.** If search is a primary function in your app, you may want to use the prominent style; if users don't need to search very often, you may want to use the minimal style.  
The prominent search bar style (shown in Mail) The minimal search bar style (shown in Music)  
![](images/_page_154_Picture_2.jpeg)  
![](images/_page_154_Picture_3.jpeg)