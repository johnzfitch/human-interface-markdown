<!-- Chunk 130 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 275 -->
A **stepper** increases or decreases a value by a constant amount.  
![](images/_page_191_Picture_17.jpeg)  
**API Note:** To learn more about defining a stepper in your code, see "Steppers".  
#### A stepper:  
- Is a two-segment control in which one segment displays a plus symbol and the other segment displays a minus symbol by default
- Supports custom images
- Doesn't display the value that the user changes  
Use a stepper when users might need to make small adjustments to a value.  
**Avoid using a stepper when users are likely to make large changes to a value.** It makes sense to use a stepper to set the number of copies in the Printer Options action sheet, because users rarely change this value by very much. On the other hand, it wouldn't make sense to use a stepper to help users choose a page range, because even a reasonable page range would require a lot of taps.  
<span id="page-192-0"></span>**Make it obvious which value the stepper affects.** A stepper doesn't display any values, so you need to make sure that users know which value they're changing when they use a stepper.