<!-- Chunk 69 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 402 -->
In-App Purchase allows users to purchase digital products within your app. For example, users could:  
- Upgrade a basic version of an app to include premium features
- Renew a subscription for new monthly content
- Purchase virtual property, such as a new weapon in a fighting game
- Buy and download new books  
With In-App Purchase, users can complete transactions in only a few clicks because their payment information is tracked and stored by the App Store. Your app can implement In-App Purchase to take advantage of the App Store's searcher payment processing. Use the Store Kit framework to embed a store directly in your app.  
Store Kit prompts usersto authorize a purchase and then notifies your app so that you can provide the purchased items to the users. Store Kit does not provide functionality for presenting your store to the users, you must design this yourself. Note that all products you sell via In-App Purchase must be registered in the App Store. See the *In-App Purchase Programming Guide* for more information.  
As you design the purchasing experience, follow these guidelines.  
**Elegantly integrate the purchasing interface with your app.** When presenting productsfor usersto purchase and handling their transactions, create a seamless experience for your users. When you make In-App Purchase a thoughtfully designed aspect of your app, and not a clumsy addition, you may entice usersto purchase more.  
**Don't alter the default confirmation dialog.** When users choose a product to purchase, Store Kit presents a confirmation dialog that helps them avoid accidental purchases.