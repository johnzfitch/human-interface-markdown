<!-- Chunk 46 | Source: 2008-11 iPhone Human Interface Guidelines.pdf | Est. Tokens: 707 -->
You choose the background of an action sheet to coordinate with the look of your application, and you can specify the number of buttons and their contents.  
Unlike an alert, an action sheet should not need to display a textual message. This is because an action sheet appears as the result of a user action, such as tapping a Delete or Send button, so there should be no need to explain its arrival.  
Action sheets can have a two different background appearances. You need to ensure that the background of the action sheets in your application coordinates with the appearance of your application's toolbars or navigation bars. If your application uses black navigation bars and toolbars, for example, the action sheet background should be translucent black. By default, iPhone OS displays action sheets with a blue background, which coordinates with the blue toolbars and navigation bars. All action sheets in your application should have the same background color, and that color should coordinate with the color of the navigation bars and toolbars.  
Be sure to display the Cancel button at the bottom of an action sheet. This encourages the user to read through all the alternatives before reaching the Cancel option.  
<span id="page-73-0"></span>Figure 7-3 shows an action sheet with the default background appearance and a Cancel button in the recommended location.  
**Figure 7-3** A typical action sheet  
![](images/_page_73_Picture_5.jpeg)  
If you need to provide a button that performs a potentially destructive action, such as deleting all the items in a user'sshopping list, you should use the red button color. It'simportant to display such destructive buttons at the top of the action sheet for two reasons:  
- The closer to the top of the action sheet a button is, the more visible it is.
- Sometimes users mistakenly tap the bottom of the device screen when they're aiming for the Home button. By placing a destructive button away from the bottom of an action sheet, users are less likely to cause undesirable results if they mistakenly tap the screen instead of the Home button.  
Figure 7-4 shows an action sheet with the translucent black background appearance and both a Cancel and a destructive button in their recommended positions.  
<span id="page-74-0"></span>**Figure 7-4** A button that performs a destructive action should be red and located at the top of the action sheet  
![](images/_page_74_Picture_3.jpeg)  
<span id="page-74-1"></span>You can display several buttonsin an action sheet, aslong as you make sure each button is easily distinguished from the others. Figure 7-5 shows an action sheet with a background that matches the blue toolbar and that provides three alternatives in addition to Cancel.  
**Figure 7-5** An action sheet with four buttons  
![](images/_page_74_Picture_6.jpeg)