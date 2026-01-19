<!-- Chunk 272 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 626 -->
A **date picker** allows users to select a specific date and time in a window. The date-picker control provides two styles of date and time selection:  
- A combination of a text field and stepper control
- A graphical calendar and clock  
The Date & Time preferences pane uses both types of date picker, as shown in Figure 15-42.  
<span id="page-304-0"></span>**Figure 15-42** Textual and graphical date pickers in a preferences pane  
![](images/_page_304_Figure_3.jpeg)  
#### Date Picker Usage  
<span id="page-304-1"></span>Use a date pickerto provide time and date settingfunctionalityin awindow. The text field and stepper date picker is useful when space is constrained and you expect users to be making specific date and time selections. This style of date picker can be modified to display various combinations of date format (month, day, and year or month and year) and time format (hour, minute, and second, or hour and minute). It can also display a text field and stepper for either the date or the time by itself. The user adjusts the date and time by clicking the arrows of the stepper or by selecting the field to change (such as the month or minute field) and typing a new value. For example, Figure 15-43 shows a text field and stepper date-picker control that allows month, day, and year selection for the date, and hour, minute, and second selection for the time.  
**Figure 15-43** A textual date-picker control  
The graphical style of the date-picker control displays a calendar and a clock. Use this style when you want to give users the option of browsing through days in a calendar or when the look of a clock face is appropriate for the style of your application. You can display either the calendar or the clock in your window or both together. The user selects a month by clicking the left or right arrows in the upper-left corner of the calendar displayand selects a daybyclickingits date in the month. A specific time is selected by dragging the hands of the clock. Figure 15-44 shows a date-picker control that displays both a calendar and a clock.  
<span id="page-305-1"></span>**Figure 15-44** A graphical date-picker control  
![](images/_page_305_Picture_3.jpeg)  
#### Date Picker Implementation  
<span id="page-305-0"></span>The date-picker control is available in Interface Builder. You can change the style from textual to graphical in the Attributes pane of the inspector. To create one using Application Kit programming interfaces, use the NSDatePicker class.