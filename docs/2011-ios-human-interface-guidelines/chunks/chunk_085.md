<!-- Chunk 85 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 2063 -->
In iOS 4.0 and later, you can allow advertisements to display within your application and you can receive revenue when users see or interact with them. It's essential that you plan when and how to integrate ads with your UI so that people are motivated to view them without being distracted from your application.  
You host an ad served by the iAd Network in a specific view in your UI. Initially, this view contains the ad's banner, which functions as the entrance into the full iAd experience. When people tap the banner, the ad performs a preprogrammed action, such as playing a movie, displaying interactive content, or launching Safari to open a webpage. The action can display content that covers your UI or it might cause your application to transition to the background.  
There are two types of banners that you can display in your application: standard banners and full screen banners. Both types of banners serve the same purpose (to usher users into the ad), but they differ in their appearance and functionality.  
A **standard banner** takes up a small area of the screen and is often visible for as long as the screen is visible. You choose the app screens that should display a standard banner and make room for the banner view in the layout.  
All iOS apps running in iOS 4.0 and later can display standard banners. You use a view provided by the ADBannerView class to contain a standard banner in your app.  
A **full screen banner** occupies most or all of the screen and is usually visible at specific times during the application flow or in specific locations. You choose whether to display the banner modally or as a separate page within scrollable content.  
Full screen banners are available only in iPad apps running in iOS 4.3 and later. You use a view provided by the ADInterstitialAd class to contain a full screen banner in your app.  
Both banner types appear inside the iAd frame, which displays the iAd mark in the lower-right corner. The iAd frame has been designed to look best when it is anchored to the bottom edge of your app screens.  
The dimensions of the standard banner view you place in the app UI vary, according to the device and the orientation.  
<span id="page-74-0"></span>**Table 6-1** Standard banner view dimensions  
| Device | Portrait        | Landscape        |
|--------|-----------------|------------------|
| iPad   | 768 x 66 points | 1024 x 66 points |
| iPhone | 320 x 50 points | 480 x 32 points  |  
<span id="page-74-1"></span>The overall dimensions of a full screen banner view can also vary with changes in device orientation, but the height can vary further with the presence or absence of iOS bars (such as toolbars and tab bars) in your app's UI. The width of a full screen banner is always the full width of the iPad screen.  
**Table 6-2** Full screen banner view dimensions  
| iPad orientation | Height range              | Width       |
|------------------|---------------------------|-------------|
| Portrait         | 911 points to 1024 points | 768 points  |
| Landscape        | 655 points to 768 points  | 1024 points |  
To ensure seamless integration with banner ads and to provide the best user experience, follow these guidelines:  
**Place a standard banner view at or nearthe bottom ofthe screen**. This placement differsslightly, depending on whether there is a bar on the bottom of the screen and if so, the kind of bar.  
If there are no bars at the bottom of the screen, put the standard banner view at the bottom edge of the screen (iPod touch shown).  
![](images/_page_74_Figure_11.jpeg)  
If there are no bars at all, again put the standard banner view at the bottom edge of the screen (iPod touch shown).  
![](images/_page_75_Picture_3.jpeg)  
If there is a toolbar or tab bar, put the standard banner view directly above the toolbar or tab bar (iPod touch shown).  
![](images/_page_75_Picture_5.jpeg)  
**Present a full screen banner modally when there are interludes in the user experience**. If there are natural breaks or context changes in the flow of your iPad app, the modal presentation style can be appropriate. When you present a full screen banner modally (by using presentFromViewController:), the user must either enter the ad or dismiss it. For this reason, it's a good idea to use the modal presentation style when users are expecting a change in experience, such as after they complete a task.  
Be sure to reveal and close a modal full screen banner view in a way that makes sense in your app. For example, a game might use fade-in and fade-out animations to reveal and close the banner.  
As you can see below, a modally presented full screen banner completely covers the app UI and includes the iAd close button in the upper-left corner.  
![](images/_page_76_Picture_4.jpeg)  
**Present a full screen banner nonmodally when there are transitions between app views**. If users experience your app by making frequent screen transitions, such as paging through a magazine or flicking through a gallery, the nonmodal presentation style can be appropriate. When you present a full screen banner nonmodally (by using presentInView:), you can preserve the bars in your UI so that users can use app controlsto move past or return to the ad. As with all banners, a fullscreen banner launchesthe iAd experience when a user taps it, but your app can respond to other gestures within the banner area (such as drag or swipe) if appropriate.  
Be sure to use appropriate animations to reveal and hide a nonmodal full screen banner view. For example, a magazine reader app would probably present a banner using the same page-turn animation it uses to reveal other content pages.  
The nonmodally presented full screen banner shown below is displayed between a navigation bar and a toolbar. However, it's up to you to choose which bars should be present.  
![](images/_page_77_Picture_2.jpeg)  
**Ensure that all banners appear when and where it makes sense in your application**. People are more likely to enter the iAd experience when they don't feel like they're interrupting their workflow to do so. This is especially important for immersive applications such as games: You don't want to place banner views where they will conflict with playing a game.  
**Avoid displaying banners on screens that users are likely to see only briefly**. If your app includes screens that users move through quickly as they drill down or navigate to the content they care about, it's best to avoid displaying banners on these screens. Users are more likely to tap a banner when it stays onscreen for more than a second or two.  
**As much as possible, display banner ads in both orientations**. It's best when users don't have to change the orientation of the device to switch between using your app and viewing an ad. Also, supporting both orientations allows you to accept a wider range of advertisements. To learn how to make sure a banner view responds to orientation changes, see *iAd Programming Guide*.  
**Don't allow a standard banner to scroll off the screen**. If your app displays scrolling content in the screen, make sure the standard banner view remains anchored in its position.  
**While people view or interact with ads, pause activities that require their attention or interaction**. When people choose to view an ad, they don't want to feel that they're missing events in your application, and they don't want your app to interrupt the ad experience. A good rule of thumb isto pause the same activities you would pause when your app transitions to the background.  
**Don't stop an ad, exceptin rare circumstances**. In general, your application continuesrunning and receiving events while users view and interact with ads, so it's possible that an event will occur that urgently requires their immediate attention. However, there are very few scenarios that warrant the dismissal of an in-progress ad. One possibility is with an application that provides Voice over Internet Protocol (VoIP) service. In such an application, it probably makes sense to cancel a running ad when an incoming call arrives.  
**Note:** Canceling an ad might adversely impact the kinds of advertisements your application can receive and the revenue you can collect.