<!-- Chunk 114 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 452 -->
A **text view** accepts and displays multiple lines of text.  
![](images/_page_178_Figure_3.jpeg)  
**API Note:** To learn more about defining a text view in your code, see "Text Views".  
#### A text view:  
- Is a rectangle of any height
- Supports scrolling when the content is too large to fit inside its bounds
- Supports custom fonts, colors, and alignments (by default, a text view displays left-aligned system font in black)
- Can support editing, in which case a keyboard appears when the user taps inside the text view (the keyboard's input method and layout are determined by the user's language settings)  
**Always make sure the text is easy to read.** Although you can use attributed stringsto combine multiple fonts, colors, and alignments in creative ways, it's essential to maintain the readability of the text. It's a good idea to support Dynamic Type and use the UIFont method preferredFontForTextStyle to get the text for display in a text view. For some guidelines on supporting Dynamic Type, see "Text Should Always Be [Legible"](#page-52-0) (page 53); for programmatic information, see "Text Styles" in *Text Programming Guide for iOS* .  
**Specify different keyboard types to accommodate different types of content you expect users to enter.** For example, you might want to make it easy for usersto enter a URL, a PIN, or a phone number. Note, however, that you have no control over the keyboard's input method and layout, which are determined by the user's language settings.  
iOS provides several keyboard types, each designed to facilitate a different type of input. To learn about the keyboard typesthat are available,see the documentation for UIKeyboardType. To learn more about managing the keyboard in your app, read "Managing the Keyboard" in *iOS App Programming Guide* .