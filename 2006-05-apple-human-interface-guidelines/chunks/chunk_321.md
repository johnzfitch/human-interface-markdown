<!-- Chunk 321 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 523 -->
<span id="page-256-3"></span>Use a **date picker** to allow the user to select a specific date and time in a window. The date-picker control provides two styles of date and time selection:  
- A combination of a text field and stepper control
- A graphical calendar and clock  
The text field and stepper date picker can be modified to display various combinations of date format (month, day, and year or month and year) and time format (hour, minute, and second or hour and minute). It can also display a text field and stepper for either the date or the time by itself. The user adjusts the date and time byclickingthe arrows of the stepper or byselectingthe field to change (such as the month or minute field) and typing a new value.  
<span id="page-256-1"></span>[Figure](#page-256-1) 14-30 (page 257) shows a text field and stepper date-picker control that allows month, day, and year selection for the date, and hour, minute, and second selection for the time.  
**Figure 14-30** A textual date-picker control  
The graphical style of the date-picker control displays a calendar and clock similar to those displayed in Date & Time System Preferences. You can display either the calendar or the clock in your window or both together. The user selects a month by clicking the left or right arrows in the upper-left corner of the calendar display and selects a day by clicking its date in the month. A specific time is selected by dragging the hands of the clock.  
<span id="page-256-2"></span>[Figure](#page-256-2) 14-31 (page 257) shows a graphical date-picker control (the second hand is not shown in the clock).  
**Figure 14-31** A graphical date picker control  
![](images/_page_256_Picture_13.jpeg)  
**Carbon:** The date picker is not available in Interface Builder. To create one programmatically, use the Control Manager CreateClockControl function.  
**Cocoa:** The date picker is available in Interface Builder in the Text palette.You can change the style from textual tographical in the Attributes pane of the NSDatePickerInspector. A date-picker control is an NSDatePicker.