<!-- Chunk 115 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 225 -->
A **web view** is a region that can display rich HTML content (shown here between the navigation bar and toolbar in Mail on iPhone).  
![](images/_page_179_Picture_3.jpeg)  
**API Note:** To learn more about defining a web view in your code, see "Web Views".  
#### A web view:  
- Displays web content
- Performs some automatic processing on web content, such as converting a phone number to a phone link  
If you have a webpage or web app, you might decide to use a web view to implement a simple iOS app that provides a wrapper for your webpage or web app. If you plan to use a web view to access web content that you control, be sure to read *Safari Web Content Guide* .  
**Avoid using a web view to create an app that looks and behaves like a mini web browser.** People expect to use Safari on iOS to browse web content, so replicating this broad functionality within your app is not recommended.