<!-- Chunk 124 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 333 -->
A **picker** displays a set of values from which a user picks one.  
![](images/_page_187_Picture_3.jpeg)  
**API Note:** To learn more about defining a picker in your code, see *UIPickerView Class Reference* .  
#### A picker:  
- Is a generic version of the date picker (for more information about the date picker, see "Date [Picker"](#page-182-1) (page 183))
- Displays one or more wheels, each of which contains a list of values
- Uses dark text to display the current value in the middle of the view
- Can't be resized (the size of a picker is the same size as the iPhone keyboard)  
Use a picker to make it easy for people to choose from a set of values.  
**In general, use a picker when users are familiar with the entire set of values.** Because many of the values are hidden when the wheel is stationary, it's best when users can predict what the values are. If you need to provide a large set of choices that aren't well known to your users, a picker might not be the appropriate control.  
**As much as possible, display a picker inline with the content.** It's best when users can avoid navigating to a different view to use a picker.  
**Consider using a table view, instead of a picker, if you need to display a very large number of values.** This is because the greater height of a table view makes scrolling faster.