<!-- Chunk 64 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 291 -->
![](images/_page_70_Picture_2.jpeg)  
Gatekeeper helps protect users from malware. In OS X v10.8, users can choose between three settings. Users can set Gatekeeper to download and install:  
- All apps
- Only apps from the Mac App Store
- Apps from the Mac App Store and apps signed with a Developer ID (this is the default setting)  
With the default setting, if an app is unsigned, Gatekeeper blocks the app from installing and warns users that the app did not come from an identified developer. Users can choose to override Gatekeeper or change the settings.  
To ensure the best possible experience for your users, you should:  
**Vend your app from the Mac App Store.** By offering your app in the Mac App Store, users automatically know that your app has been reviewed by Apple and has not been tampered with.  
<span id="page-70-1"></span>**Sign your app with a valid Developer ID.** If you choose to distribute your app outside of the Mac App Store, sign your app with a Developer ID. Thisidentifies you as an Apple developer and ensuresthat your app launches on Macs with Gatekeeper enabled. See "Distributing Outside the Mac App Store" for more information.