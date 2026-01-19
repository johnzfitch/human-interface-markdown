<!-- Chunk 137 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 871 -->
![](images/_page_200_Picture_4.jpeg)  
**API Note:** To learn how to define an action sheet in your code, see "Action Sheets".  
#### An action sheet:  
- Appears as the result of a user action
- Displays two or more buttons  
#### Use an action sheet to:  
- **Provide alternative ways to complete a task.** An action sheet lets you to provide a range of choices that make sense in the context of the current task, without giving these choices a permanent place in the UI.
- **Get confirmation before completing a potentially dangerous task.** An action sheet prompts users to think about the potentially dangerous effects of the step they're about to take and gives them some alternatives.  
**On iPhone, include a Cancel button so that users can easily and safely abandon the task.** Place the Cancel button at the bottom of the action sheet to encourage usersto read through all the alternatives before making a choice.  
**On iPad, base the way the action sheet is displayed on the way the user initiates the task.** Specifically:  
| If the task is<br>initiated from | Display the action sheet                                                                                | Include a Cancel button?                                                                                      |
|----------------------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Outside<br>of<br>a<br>popover    | Without<br>animation—thatis,the<br>action<br>sheet<br>and<br>the<br>popover<br>appear<br>simultaneously | No,<br>because<br>users<br>can<br>tap<br>outside<br>the<br>popover<br>to<br>dismiss<br>the<br>action<br>sheet |  
| If the task is<br>initiated from | Display the action sheet                                                                                                  | Include a Cancel button?                                                                                                                |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Inside<br>a<br>popover           | With<br>animation—that<br>is,<br>the<br>action<br>sheet<br>slides<br>up<br>on<br>top<br>of<br>the<br>popover's<br>content | Yes,<br>because<br>users<br>need<br>to<br>be<br>able<br>to<br>dismiss<br>the<br>action<br>sheet<br>without<br>closing<br>the<br>popover |  
**On all devices, use red for the button that performs a potentially destructive action.** Display a red button at the top of the action sheet, because the closer to the top of the action sheet a button is, the more eye-catching it is. And on iPhone, the farther a destructive button is from the bottom of an action sheet, the less likely users are to tap it when they're aiming for the Home button.  
![](images/_page_201_Picture_3.jpeg)  
**Avoid making users scroll an action sheet.** If you include too many buttons in an action sheet, users must scroll to see all their choices. This is a disconcerting experience for users, because they must spend extra time to distinguish the choices. Also, it can be very difficult for usersto scroll without inadvertently tapping a button.