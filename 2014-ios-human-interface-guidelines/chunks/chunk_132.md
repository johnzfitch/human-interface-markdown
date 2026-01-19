<!-- Chunk 132 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 459 -->
A system button performs an app-specific action.  
**API Note:** In iOS 7, UIButtonTypeRoundedRect has been redefined as UIButtonTypeSystem. An app that uses a rounded rectangle button in iOS 6 automatically gets the system button appearance when it links against iOS 7.  
To learn more about defining a system button in your code, see "Buttons".  
#### A system button:  
- Has no border or background appearance by default
- Can contain an icon or a text title
- Supports custom decoration, such as a border or background image (to add a custom appearance, use a button of type UIButtonTypeCustom and supply a custom background image)  
Use a system button to initiate an action. When you supply a title for a system button, follow this approach:  
- **Use a verb or verb phrase to describe the action the button performs.** An action-specific title shows users that the button is interactive and tells them what will happen when they tap it.
- **Use title-style capitalization.** Capitalize every word except articles, coordinating conjunctions, and prepositions of four or fewer letters.
- **Avoid creating a title that is too long.** Overly long text gets truncated, which can make it difficult for users to understand it.  
![](images/_page_194_Picture_1.jpeg)  
**If appropriate, add a border or background appearance to a system button in a content region.** Most of the time, you can avoid adding ornamentation to a button by crafting a clear call-to-action title, defining a tint, and providing contextual clues. In some content areas, however, it can be appropriate to focus attention on a button by adding a border or background appearance.  
In Phone, for example, the bordered number keys reinforce the mental model of making a call and the background of the Call button gives users an eye-catching target that's easy to hit.