<!-- Chunk 72 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 562 -->
In-App Purchase lets people buy digital products within your app, in a store that you design.  
![](images/_page_104_Picture_2.jpeg)  
For example, users might:  
- Upgrade a basic version of an app to a premium version
- Renew a subscription for new monthly content
- Purchase virtual items, such as a new level or weapon in a game
- Buy and download new books  
You use the Store Kit framework to embed a store in your app and support In-App Purchase. When a user makes a purchase, Store Kit connects to the App Store to securely process the payment and then notifies your app so that it can provide the purchased item.  
**Important:** In-App Purchase only collects payment—you provide additional functionality,such as presenting your store to users, unlocking built-in features, and downloading content from your own servers. Also, all products you sell through In-App Purchase must be registered in the App Store.  
To learn about the technical requirements of adding a store to your app, see *In-App Purchase Programming Guide* . For more information on the business requirements of using In-App Purchase, visit the App [Store](http://developer.apple.com/appstore/) [Resource](http://developer.apple.com/appstore/) Center. You should also read your licensing agreement for definitive information about what you may sell and how you are required to provide those products in your app.  
The following guidelines can help you design a purchasing experience that users appreciate.  
**Elegantly integrate the store experience into your app.** When presenting products and handling user transactions, create an experience that feels at home in your app. You don't want users to think that they've entered a different app when they visit your store.  
**Use simple, succinct titles and descriptions.** It's best when people can scan a set of items and quickly find the ones they're interested in. When you use plain, direct language and titles that don't truncate or wrap, it's easier for people to understand the items you're offering.  
**Don't alter the default confirmation alert.** When users buy a product, Store Kit presents a confirmation alert (shown above). You shouldn't modify this alert because it helps users avoid accidental purchases.