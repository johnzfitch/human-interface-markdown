<!-- Chunk 125 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 283 -->
A **progress view** shows the progress of a task or process that has a known duration (shown here with the Mail toolbar).  
![](images/_page_188_Picture_3.jpeg)  
**API Note:** To learn more about defining a progress view in your code, see *UIProgressView Class Reference* .  
#### A progress view:  
- Consists of a track that fills from left to right as the task or process proceeds
- Doesn't allow user interaction  
iOS defines two styles of progress view:  
- **Default.** The default style includes an unfilled track appearance so that it can stand alone in a content area.
- **Bar.** The bar style doesn't include the unfilled track appearance because it's intended to display with a bar, such as a navigation bar or a toolbar.  
Use a progress view to give feedback on a task that has a well-defined duration, especially when it's important to indicate approximately how long the task will take.  
**If appropriate, coordinate the appearance of a progress view with the style of your app.** By customizing a progress view, you can specify, for example, a custom tint or image for both the track and the fill of a progress view.