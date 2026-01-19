<!-- Chunk 116 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 260 -->
An **activity indicator** shows that a task or process is progressing (shown below with text labels).  
![](images/_page_181_Picture_3.jpeg)  
**API Note:** To learn how to define an activity indicator in your code,see *UIActivityIndicatorView Class Reference* .  
#### An activity indicator:  
- Spins while a task is progressing and disappears when the task completes
- Doesn't allow user interaction  
Use an activity indicator in a toolbar or a main view to show that processing is occurring, without suggesting when it will finish.  
**Don't display a stationary activity indicator.** Users associate a stationary activity indicator with a stalled process.  
**Use an activity indicator to reassure users that their task or process hasn't stalled.** Sometimes it's more important to simply reassure users than to suggest when processing will finish.  
**Customize an activity indicator to harmonize with the view it's in.** If appropriate, coordinate the size and color of an activity indicator with the background of the view it's in.