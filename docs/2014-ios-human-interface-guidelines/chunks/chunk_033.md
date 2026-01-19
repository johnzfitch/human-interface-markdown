<!-- Chunk 33 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 860 -->
Above all, text must be legible. If users can't read the words in your app, it doesn't matter how beautiful the typography is. When you adopt Dynamic Type in an iOS 7 app, you get:  
- Automatic adjustments to letter spacing and line height for every font size
- The ability to specify different text styles for semantically distinct blocks of text, such as Body, Footnote, or Headline
- Text that responds appropriately to changes the user makes to text-size settings (including accessibility text sizes)  
**Note:** If you use a custom font, you can still scale type according to the system setting for text size. Your app is responsible for responding appropriately when the user changes the setting.  
Adopting Dynamic Type requires some work on your part. To learn how to use text styles and ensure that your app gets notified when the user changes the text size setting, see "Text Styles" in *Text Programming Guide for iOS* .  
#### **Prioritize content when responding to text-size changes.**  
Not all content is equally important to users. When users choose a larger text size, they want to make the content they care about easier to read; they don't always want every word on the screen to be larger.  
For example, when users choose a large accessibility textsize, Mail displaysthe subject and body of the message in the large size but leaves the less important text—such as the date and the sender—in a smaller size.  
![](images/_page_53_Picture_6.jpeg)  
**When appropriate, adjust the layout when the user chooses a different text size.** For example, you might want to change a one-column layout of body text to a two-column layout when the user chooses a small text size. If you decide to adjust the layout for different text sizes, you might choose to do so for subsets of sizes—such as small, medium, and large—rather than change the layout for every possible size.  
**Make sure all styles of a custom font are legible at different sizes.** One way to do this is to emulate some of the ways iOS displays font styles at different text sizes. For example:  
● Text should never be smaller than 11 points, even when the user chooses the extra-small text size. For comparison, the body style uses a font size of 17 points at the large size, which is the default text-size setting.  
- In general, font size and leading values differ by one point per text-size setting. Exceptions to this are the two caption styles, which use the same fontsize, leading, and tracking at the extra-small,small, and medium settings.
- At the smallest three text sizes, tracking values are relatively large; at the largest three text sizes, tracking values are relatively tight.
- The headline and body styles use the same font size. To distinguish it from the body style, the headline style uses a heavier weight.
- Text in a navigation controller uses the same font size that body style text uses for the large setting (specifically, 17 points).
- Text always uses either regular or medium weight; it doesn't use light or bold.  
**In general, use a single font throughout your app.** Mixing several different fonts can make your app seem fragmented and sloppy. Instead, use one font and just a few styles and sizes. Use the UIFont text styles API to define different areas of text according to semantic usage, such as body or headline.  
Recommended Not Recommended  
![](images/_page_54_Picture_9.jpeg)  
![](images/_page_54_Picture_10.jpeg)