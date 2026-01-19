<!-- Chunk 127 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 288 -->
A **date picker** displays components of date and time, such as hours, minutes, days, and years.  
![](images/_page_203_Picture_9.jpeg)  
**API Note:** To define a date picker in your code, use the NSDatePicker class.  
The date-picker control provides two main styles:  
- **Textual**. This style consists of a text field or text field combined with a stepper control.
- **Graphical**. This style consists of a graphical representation of a calendar or a clock.  
Using the textual style, users can enter date and time information in the text field or use the stepper. Using the graphical style, users can move the clock hands or choose specific days, months, or years in the calendar.  
Use a date picker to provide time and date setting functionality in a window.  
**Choose the date-picker style that suits your app.** The text field and stepper date picker is useful when space is constrained and you expect users to be making specific date and time selections. A graphical date picker can be useful when you want to give users the option of browsing through days in a calendar or when the look of a clock face is appropriate for the UI of your app.