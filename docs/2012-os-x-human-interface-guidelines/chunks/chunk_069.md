<!-- Chunk 69 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 417 -->
In-App Purchase allows users to purchase digital products within your app. For example, users could:  
- Upgrade a basic version of an app to include premium features
- Renew a subscription for new monthly content
- Purchase virtual property, such as a new weapon in a fighting game
- Buy and download new books  
With In-App Purchase, users can complete transactions in only a few clicks because their payment information is tracked and stored by the App Store. Your app can implement In-App Purchase to take advantage of the App Store's searcher payment processing. Use the Store Kit framework to embed a store directly in your app.  
Store Kit prompts usersto authorize a purchase and then notifies your app so that you can provide the purchased items to the users. Store Kit does not provide functionality for presenting your store to the users, you must design this yourself. Note that all products you sell via In-App Purchase must be registered in the App Store. See the *In-App Purchase Programming Guide* for more information.  
As you design the purchasing experience in your app, consider the following guidelines.  
**Elegantly integrate your purchasing interface with your app.** When presenting productsfor usersto purchase and handling their transactions, create a seamless experience for your users. To entice users to purchase more, try to make In-App Purchase a thoughtfully designed aspect of your app and not a clumsy addition.  
**Do not alter the default confirmation dialog.** When users choose to purchase a product, Store Kit presents a confirmation dialog. You should not try to override this dialog. It helps users avoid an accidental purchase.