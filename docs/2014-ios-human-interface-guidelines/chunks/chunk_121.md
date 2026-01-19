<!-- Chunk 121 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 222 -->
A **label** displays static text.  
**API Note:** To learn more about defining labels in your code, see *UILabel Class Reference* .  
#### A label:  
- Displays any amount of static text
- Doesn't allow user interaction except, potentially, to copy the text  
Use a label to name or describe parts of your UI or to provide short messages to the user. A label is best suited for displaying a relatively small amount of text.  
**Take care to make your labels legible.** It's best to support Dynamic Type and use the UIFont method preferredFontForTextStyle to get the text for display in a label. If you choose to use custom fonts, don't sacrifice clarity for fancy lettering or showy colors. (For guidelines about using text in an app, see ["Color](#page-51-0) and [Typography"](#page-51-0) (page 52); to learn more about Dynamic Type, see "Text Styles" in *Text Programming Guide for iOS* .)