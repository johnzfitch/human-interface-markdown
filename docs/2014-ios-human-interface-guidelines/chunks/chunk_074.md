<!-- Chunk 74 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 1986 -->
Notification Center gives users a single, convenient place in which to view notifications from their apps. Users appreciate the unobtrusive interface of Notification Center and they value the ability to customize the way each app can present its notifications.  
![](images/_page_108_Picture_2.jpeg)  
Notification Center uses a sectioned list to display recent notification items from the apps that users are interested in. In addition to notifications, users can also choose to see information from built-in apps, such as Weather, Calendar, Reminders, and Stocks.  
iOS apps can use local or push notifications to let people know when interesting things happen, such as:  
- A message has arrived
- An event is about to occur  
- New data is available for download
- The status of something has changed  
A **local notification** is scheduled by an app and delivered by iOS on the same device, regardless of whether the app is currently running in the foreground. For example, a calendar or to-do app can schedule a local notification to alert people of an upcoming meeting or due date.  
A **push notification** is sent by an app's remote server to the Apple Push Notification service, which pushes the notification to all devices that have the app installed. For example, a game that a user can play against remote opponents can update all players with the latest move.  
You can still receive local and push notifications when your app is running in the foreground, but you pass the information to your users in an app-specific way.  
iOS appsthatsupport local or push notifications can participate in Notification Center in various ways, depending on the user's preferences. To ensure that users can customize their notification experience, you should support as many as possible of the following notification styles:  
- Banner
- Alert
- Badge
- Sound  
A **banner** is a small translucent view that appears onscreen and then disappears after a few seconds. In addition to your notification message, iOS displays the small version of your app icon in a banner, so that people can see at a glance which app is notifying them (to learn more about the small app icon, see "App [Icon"](#page-208-0) (page 209)).  
![](images/_page_109_Picture_12.jpeg)  
An **alert** is a standard alert view that appears onscreen and requires user interaction to dismiss. You supply the notification message and, optionally, a title for the action button in the alert. You have no control over the background appearance of the alert or the buttons.  
![](images/_page_110_Picture_2.jpeg)  
A **badge** is a small red oval that displays the number of pending notification items (a badge appears over the upper-right corner of an app's icon). You have no control over the size or color of the badge.  
![](images/_page_110_Picture_4.jpeg)  
A custom or system-provided **sound** can accompany any of the other three notification delivery styles.  
**Note:** An app that uses push notifications instead of local notifications can provide only the notification stylesthat correspond to the push categoriesfor which the app isregistered. For example, if a push-notification app registers for alerts only, users can receive only alerts from this app. An app that uses local notifications can provide all notification styles.  
As you design the content that your notifications can deliver, be sure to observe the following guidelines.  
**Keep badge contents up to date.** It's especially important to update the badge assoon as users have attended to the new information, so that they don't think additional notifications have arrived. Note that setting the badge contents to zero also removes the related notification items from Notification Center.  
**Important:** Don't use a badge for purposes other than notifications. Remember that users can turn off badging for your app, so you can't be sure that they will see the content in a badge.  
**Don't send multiple notifications for the same event.** Users can attend to notification items when they choose; the items don't disappear until users handle them in some way. If you send multiple notifications for the same event, you fill up the Notification Center list and users are likely to turn off notifications from your app.  
**Provide a custom message that does not include your app name.** Your custom message is displayed in alerts and banners, and in Notification Center list items. You should not include your app's name in your custom message because iOS automatically displays the name with your message.  
To be useful, a local or push notification message should:  
- Focus on the information, not user actions. Avoid telling people which alert button to tap or how to open your app.
- Be short enough to display on one or two lines. Long messages are difficult for users to read quickly, and they can force alerts to scroll.
- Use sentence-style capitalization and appropriate ending punctuation. When possible, use a complete sentence.  
**Note:** In general, a Notification Center item can display more of a notification message than a banner can. If necessary, iOS truncates your message so that it fits well in each notification delivery style; for best results, you shouldn't truncate your message.  
**Optionally, provide a custom title for the action button in an alert.** An alert can contain one or two buttons. In a two-button alert, the Close button is on the left and the action button (titled View by default) is on the right. If you specify only one button, the alert displays an OK button.  
Tapping the action button dismisses the alert and launches your app simultaneously. Tapping either the Close button or the OK button dismisses the alert without opening your app.  
If you want to use a custom title for the action button, be sure to create a title that clearly describes the action that occurs when your app launches. For example, a game might use the title Play to indicate that tapping the button opens the app to a place where the user can take their turn. Make sure the title:  
- Uses title-style capitalization
- Is short enough to fit in the button without truncation (be sure to test the length of localized titles, too)  
**Note:** Your custom button title can also be displayed in the "slide to view" message people see when a notification arrives while the device is locked. When this happens, your custom title is automatically converted to lowercase and replaces the word "view" in the message.  
**Provide a sound that users can choose to hear when a notification arrives.** A sound can get people's attention when they're not looking at the device screen. For example, a calendar app might play a sound with an alert that reminds people about an imminent event. Or, a collaborative task management app might play a sound with a badge update to signal that a remote colleague has completed an assignment.  
You can supply a custom sound, or you can use a built-in alert sound. If you create a custom sound, be sure it's short, distinctive, and professionally produced. (To learn about the technical requirements for this sound, see "Preparing Custom Alert Sounds" in *Local and Push Notification Programming Guide* .) Note that you can't programmatically cause the device to vibrate when a notification is delivered, because the user has control over whether alerts are accompanied by vibration.  
**Optionally, provide a launch image.** In addition to displaying your existing launch images, you can supply a different launch image to display when people start your app in response to a notification. For example, a game mightspecify a launch image that'ssimilar to a screen within the game, instead of an image that'ssimilar to the opening menu screen. If you don't supply this launch image, iOS displays either the previous snapshot or one of your other launch images. (To learn how to create a launch image, see ["Launch](#page-214-0) Images" (page 215).)