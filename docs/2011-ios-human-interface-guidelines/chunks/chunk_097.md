<!-- Chunk 97 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 1653 -->
Local and push notifications allow you to tell people about something when your application isn't running in the foreground.  
![](images/_page_92_Picture_2.jpeg)  
For example, you might want to let people know that:  
- A message has arrived
- An event is about to occur
- New data is available for download
- The status of something has changed  
**Local notifications** are scheduled by an application and delivered by iOS on the same device, regardless of whether the app is currently running in the foreground. For example, a calendar or to-do app can schedule a local notification to alert people of an upcoming meeting or due date.  
**Push notifications** are sent by an app's remote server to the Apple Push Notification service, which pushes the notification to all devices that have the app installed. For example, a game that a user can play against remote opponents can update all players with the latest move.  
If your application is not running in the foreground when a local or push notification arrives, you can get the user's attention by:  
- Updating a **badge**—a small red oval that appears over the upper-right corner of your application's icon on the Home screen
- Displaying an alert  
You can also play a sound when a badge updates or an alert appears.  
If your app is running in the foreground, you can still receive local and push notifications, but you pass the information to your users in an app-specific way. In Settings, people can allow or disallow badging, sounds, and alerts for push notifications from selected applications or from all applications. There is no similar mechanism for disabling local notifications, because thisissomething people should be able to specify within each app.  
Different notification techniques might be appropriate in different situations, so you should be prepared to use either type.  
**Use a badge when it helps the userto know the number buttheir viewing ofthe items is nottime-critical**. A badge is a good way to tell people how many items are waiting for their attention,such as unread messages, assigned tasks, or updates to a shared document. Because people don't see badges unless they visit the Home screen, you probably don't want to use them to deliver time-sensitive information.  
You do not have any control over the appearance of the badge or its position: It's always a small red oval as shown here.  
![](images/_page_93_Picture_2.jpeg)  
A badge contains only numbers, not letters or punctuation.  
**Use an alert when you need to deliverimportantinformation users wantto know or act upon right away**. An alert is a good way to tell people about an upcoming event or a status change. Alerts interrupt the user's workflow, so it's best to use them sparingly.  
![](images/_page_93_Picture_5.jpeg)  
Follow these guidelines to create local and push notifications that users appreciate.  
**Keep badge contents up to date**. It's especially important to update the badge assoon as users have attended to the new information, so that they don't think additional information has arrived.  
**Provide a custom message for an alert**. Your custom message is displayed in the center of the alert, below your app name (which is automatically displayed at the top of the alert). A local or push notification alert message should:  
- Focus on the information, not user actions. Avoid telling people which button to tap or describing the results of tapping a specific button.
- Be short enough to display on one or two lines. If the message is too long, it might force the notification alert to scroll.
- Use sentence-style capitalization and appropriate ending punctuation. When possible, use a complete sentence.  
**Optionally, provide a custom title for the action button**. An alert can contain one or two buttons. In a two-button alert, the Close button is on the left and the action button (titled View by default) is on the right. If you specify one button, the alert displays an OK button.  
Tapping the action button dismisses the alert and launches your application simultaneously. Tapping either the Close button or the OK button dismisses the alert without opening your app.  
If you want to use a custom title for the action button, be sure to create a title that clearly describes the action that occurs when your app launches. For example, a game might use the title Play to indicate that tapping the button opens the application to a place where the user can take their turn. Make sure the title:  
- Uses title-style capitalization
- Is short enough to fit in the button without truncation (be sure to test the length of localized titles, too)  
#### **CHAPTER 6**  
iOS Technology Usage Guidelines  
**Note:** Your custom button title can also be displayed in the "slide to view" message people see when a notification arrives while the device islocked. When this happens, the custom title is automatically converted to lowercase and replaces the word "view" in the message.  
**Optionally, provide a launch image**. In addition to displaying your existing launch images, you can supply a different launch image to display when people start your app in response to a notification. For example, a game might specify a launch image that's similar to a screen within the game, instead of an image that's similar to the opening menu screen. If you don't supply this launch image, iOS displays either the previous snapshot or one of your other launch images. (To learn how to create a launch image, see ["Launch](#page-149-0) [Images"](#page-149-0) (page 150).)  
**If appropriate, play a sound to accompany the updating of a badge or the displaying of an alert**. A sound can get people's attention when they're not looking at the device screen. It's best when sounds are reserved for notifications that users consider important. For example, a calendar app might play a sound with an alert that reminds people about an imminent event. Or, a collaborative task management app might play a sound with a badge update to signal that a remote colleague has completed an assignment.  
You can supply a custom sound, or you can use a built-in alert sound. If you create a custom sound, be sure it isshort, distinctive, and professionally produced. (To learn about the technical requirementsfor thissound, see "Preparing Custom Alert Sounds"in *Local and PushNotification ProgrammingGuide*.) Note that you cannot programmatically force the device to vibrate when a notification is delivered, because the user has control over whether alerts are accompanied by vibration.  
#### **CHAPTER 6**  
iOS Technology Usage Guidelines