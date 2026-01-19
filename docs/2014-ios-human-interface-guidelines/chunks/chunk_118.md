<!-- Chunk 118 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 484 -->
A **date picker** displays components of date and time, such as hours, minutes, days, and years.  
![](images/_page_182_Picture_12.jpeg)  
**API Note:** To learn how to define a date picker in your code, see "Date Pickers".  
#### A date picker:  
● Displays up to four independent wheels, each of which displays values in a single category, such as month or hour  
- Uses dark text to display the current value in the middle of the view
- Can't be resized (the size of a date picker is the same size as the iPhone keyboard)
- Has four modes, each of which displays wheels containing a set of different values:
- **Date and time.** The date and time mode (the default mode) displays wheels for the calendar date, hour, and minute values, and an optional wheel for the AM/PM designation.
- **Time.** The time mode displays wheels for the hour and minute values, and an optional wheel for the AM/PM designation.
- **Date.** The date mode displays wheels for the month, day, and year values.
- **Countdown timer.** The countdown timer mode displays wheels for the hour and minute. You can specify the total duration of a countdown, up to a maximum of 23 hours and 59 minutes.  
Use a date picker to let users pick—instead of type—a date or time value that consists of multiple parts, such as the day, month, and year.  
**As much as possible, display a date picker inline with the content.** It's best when users can avoid navigating to a different view to use a date picker. On iPad, a date picker can appear within a popover or inline with content.  
**If it makes sense in your app, change the interval in the minutes wheel.** By default, a minutes wheel displays 60 values (0 to 59). If you need to display a coarser granularity of choices, you can set a minutes wheel to display a larger minute interval, as long as the interval divides evenly into 60. For example, you might want to display the quarter-hour intervals 0, 15, 30, and 45.