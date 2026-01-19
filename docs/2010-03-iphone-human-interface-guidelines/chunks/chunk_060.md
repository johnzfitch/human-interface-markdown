<!-- Chunk 60 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 454 -->
iPhone applications stop when users open a different application or use a device feature, such as the phone. In particular, note that users don't tap an application close button or select Quit from a menu. iPhone applications should:  
- Be prepared to receive an exit or terminate notification at any time. Therefore, save user data as soon as possible and as often as reasonable.
- Save the currentstate when stopping, at the finest level of detail possible. For example, if your application displays scrolling data, save the current scroll position.  
iPhone applications should never quit programmatically because doing so looks like a crash to the user. There may be times, however, when external circumstances prevent your application from functioning as intended. The best way to handle this is to display an attractive screen that describes the problem and suggests how users can correct it. This helps users in two ways:  
- It provides feedback that reassures users that there's nothing wrong with your application
- It puts users in control, letting them decide whether they want to take corrective action and continue using your application or press the Home button and open a different application  
If certain circumstances prevent only some of your application'sfeaturesfrom working, you can display either a screen or an alert when users activate the feature. Although an alert doesn't allow much flexibility in design, it can be a good choice if you can:  
- Describe the situation very succinctly
- Supply a button that performs a corrective action
- Display the alert *only* when users try to access the feature that isn't functioning  
As with all alerts, the less users see them, the more effective they are. See "Using [Alerts"](#page-79-0) (page 80) for more information about creating alerts.