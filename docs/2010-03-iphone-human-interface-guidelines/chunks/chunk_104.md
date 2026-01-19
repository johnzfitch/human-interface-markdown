<!-- Chunk 104 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 714 -->
You choose the background of an action sheet to coordinate with the look of your application, and you can specify the number of buttons and their contents.  
Unlike an alert, an action sheet should not need to display a textual message. This is because an action sheet appears as the result of a user action, such as tapping a Delete or Send button, so there should be no need to explain its arrival.  
Action sheets can have two different background appearances. You need to ensure that the background of the action sheets in your application coordinates with the appearance of your application's toolbars or navigation bars. If your application uses black navigation bars and toolbars, for example, the action sheet background should be translucent black. By default, iPhone OS displays action sheets with a standard blue background, which coordinates with the standard blue toolbars and navigation bars. All action sheetsin your application should have the same background color, and that color should coordinate with the color of the navigation bars and toolbars.  
Be sure to display the Cancel button at the bottom of an action sheet. This encourages the user to read through all the alternatives before reaching the Cancel option.  
<span id="page-83-1"></span>Figure 7-2 shows an action sheet with the default background appearance and a Cancel button in the recommended location.  
![](images/_page_83_Picture_8.jpeg)  
**Figure 7-2** A typical action sheet  
If you need to provide a button that performs a potentially destructive action, such as deleting all the items in a user'sshopping list, you should use the red button color. It'simportant to display such destructive buttons at the top of the action sheet for two reasons:  
■ The closer to the top of the action sheet a button is, the more visible it is.  
■ Sometimes users mistakenly tap the bottom of the device screen when they're aiming for the Home button. By placing a destructive button away from the bottom of an action sheet, users are less likely to cause undesirable results if they mistakenly tap the screen instead of the Home button.  
<span id="page-84-0"></span>Figure 7-3 shows an action sheet with the translucent black background appearance and both a Cancel and a destructive button in their recommended positions.  
**Figure 7-3** A button that performs a destructive action should be red and located at the top of the action sheet  
![](images/_page_84_Picture_5.jpeg)  
You can display several buttonsin an action sheet, aslong as you make sure each button is easily distinguished from the others. Figure 7-4 shows an action sheet with a background that matches the standard blue toolbar and that provides three alternatives in addition to Cancel.  
<span id="page-85-1"></span>**Figure 7-4** An action sheet with four buttons  
![](images/_page_85_Picture_3.jpeg)