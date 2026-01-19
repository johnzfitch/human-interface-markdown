<!-- Chunk 133 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 533 -->
A **text field** accepts a single line of user input (shown here with a purpose description and placeholder text).  
![](images/_page_194_Picture_6.jpeg)  
**API Note:** To learn more about defining a text field and customizing it to display images and buttons, see "Text Fields".  
#### A text field:  
- Is a fixed-height field with rounded corners
- Automatically displays a keyboard when users tap within it
- Can include system provided buttons, such as the Bookmarks button  
● Can display text that uses multiple styles (to learn more about this, see UITextView)  
Use a text field to get a small amount of information from the user.  
**Customize a text field if it helps users understand how they should use it.** For example, you can display custom images in the left or right sides of the text field, or you can add a system-provided button, such as the Bookmarks button. In general, you should use the left end of a text field to indicate its purpose and the right end to indicate the presence of additional features, such as bookmarks.  
**Display the Clear button in the right end of a text field when appropriate.** When this element is present, tapping it clears the contents of the text field, regardless of any other image you might display over it.  
**Display a hint in the text field if it helps users understand its purpose.** A text field can display placeholder text—such as Name (or Address)—when there is no other text in the field.  
**Specify a keyboard type that's appropriate for the type of content you expect users to enter.** For example, you might want to make it easy for usersto enter a URL, a PIN, or a phone number. iOS providesseveral different keyboard types, each designed to facilitate a different type of input. To learn about the keyboard types that are available, see UIKeyboardType in *UITextInputTraits Protocol Reference* . To learn more about managing the keyboard in your app, read "Managing the Keyboard" in *iOS App Programming Guide* . Note that you have no control over the keyboard'sinput method and layout, because these attributes are determined by the user's language settings.