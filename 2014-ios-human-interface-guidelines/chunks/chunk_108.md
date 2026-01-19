<!-- Chunk 108 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 359 -->
A **page view controller** uses one of two styles to manage transitions through multipage content—scrolling or page-curl. Here's how a page curl looks in iOS 7 Simulator:  
![](images/_page_163_Picture_8.jpeg)  
**API Note:** To learn more about defining a page view controller in your code, see "Page View Controllers".  
#### A page view controller:  
- Has no default appearance for the scrolling style For the page curl style, a page view controller can add the appearance of the inside of a book spine between pairs of pages
- Animates the transition from one page to another, according to the specified style For the scrolling style, the current page scrolls to the next page; for the page curl style, the current page appears to turn like a page in a book or a notepad.  
Use a page view controller to present content that users access in a linear fashion (such as the text of a story) or content that naturally breaks into chunks (such as a calendar).  
**If necessary, create a custom way to let users access content in a nonlinear way.** A page view controller lets users move from one page to the next or previous page; it doesn't give users a way to jump among nonadjoining pages. If you want to use a page view controller to present content that users might access in a nonlinear fashion—such as a dictionary or a book's table of contents—you must implement a custom way to let users move to different areas of the content.