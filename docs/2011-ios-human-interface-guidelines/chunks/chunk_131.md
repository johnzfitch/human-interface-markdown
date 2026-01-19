<!-- Chunk 131 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 1934 -->
The infrequency with which alerts appear helps users take them seriously. Be sure to minimize the number of alerts your app displays and ensure that each one offers critical information and useful choices.  
#### **Avoid creating unnecessary alerts**.  
These alerts are usually unnecessary if they:  
- Merely increase the visibility of some information, especially information that is related to the standard functioning of your application.
- Instead, you should design an eye-catching way to display the information that harmonizes with your app's style.
- Update users on tasks that are progressing normally.  
Instead, consider using a progress view or an activity indicator to provide progress-related feedback to users(these methods of feedback are described in ["Progress](#page-128-1) View" (page 129) and "Activity [Indicator"](#page-123-1) (page 124)).  
● Ask for confirmation of user-initiated actions.  
To get confirmation for an action the user initiated, even a potentially risky action such as deleting a contact, you should use an action sheet.  
● Inform users of errors or problems about which they can do nothing.  
Although it might be necessary to use an alert to tell users about a critical problem they can't fix, it's better to integrate such information into the UI, if possible. For example, instead of telling users every time a server connection fails, display the time of the last successful connection.  
You can specify the text of the required title and optional message, the number of buttons, and the button contents in an alert. You can't customize the width or the background appearance of the alert view itself, or the alignment of the text (it's center-aligned).  
As you read the alert-text design guidelines, it's useful to know the following definitions:  
- **Title-style capitalization** meansthat every word is capitalized, except articles, coordinating conjunctions, and prepositions of four or fewer letters when they aren't the first word.
- **Sentence-style capitalization** means that the first word is capitalized, and the rest of the words are lowercase unless they are proper nouns or proper adjectives.  
**Write alert text that succinctly describes the situation and explains what people can do about it**. Ideally, the text you write gives people enough context to understand why the alert has appeared and to decide which button to tap.  
**Keep the title short enough to display on a single line, if possible**. A long alert title is difficult for people to read quickly, and it might get truncated or force the alert message to scroll.  
![](images/_page_116_Picture_13.jpeg)  
**Avoid single-word titles that don't provide any useful information**, such as "Error" or "Warning."  
**When possible, use a sentence fragment**. A short, informative statement is often easier to understand than a complete sentence.  
**Don't hesitate to be negative**. People understand that most alerts tell them about problems or warn them about dangerous situations. It's better to be negative and direct than it is to be positive but oblique.  
**Avoid using "you," "your," "me," and "my" as much as possible**. Sometimes, text that identifies people directly can be ambiguous and can even be interpreted as an insult.  
**Use capitalization and punctuation appropriately**.  
Use title-style capitalization and no ending punctuation when the title is a sentence fragment or it consists of a single sentence that is not a question.  
If the title consists of a single sentence that is a question, use sentence-style capitalization and an ending question mark. In general, consider using a question for an alert title if it allows you to avoid adding a message.  
If the title consists of two or more sentences, use sentence-style capitalization and appropriate ending punctuation for each sentence. A two-sentence alert title should seldom be necessary, although you might consider it if it allows you to avoid adding a message.  
**If you provide an optional alert message, create a short, complete sentence**. Use sentence-style capitalization and appropriate ending punctuation.  
![](images/_page_117_Picture_6.jpeg)  
**Avoid creating an alert message that is too long**. If possible, keep the message short enough to display on one or two lines. If the message is too long it will scroll, which is not a good user experience.  
![](images/_page_117_Picture_8.jpeg)  
**Avoid lengthening your alert text with descriptions of which button to tap**, such as "Tap View to see the information." Ideally, the combination of unambiguous alert text and logical button labels gives people enough information to understand the situation and their choices. However, if you must provide detailed guidance, follow these guidelines:  
- Be sure to use the word "tap" (not "touch" or "click" or "choose") to describe the selection action.
- Don't enclose a button title in quotation marks, but do preserve its capitalization.  
**Be sure to testthe appearance of your alertin both orientations**. Because the height of an alert is constrained in landscape, it might look different from the way it looks in portrait. It's recommended that you optimize the length of the alert text so that it looks good (and avoids scrolling) in both orientations.  
**Generally, use a two-button alert**. A two-button alert is often the most useful, because it is easiest for people to choose between two alternatives. It is rarely a good idea to display an alert with a single button because such an alert is merely informative; it does not give people any control over the situation. An alert that contains three or more buttons is significantly more complex than a two-button alert and should be avoided if possible. In fact, if you find that you need to offer people more than two choices, you should consider using an action sheet instead (to learn how to use an action sheet, see ["Action](#page-118-0) Sheet" (page 119)).  
**Use alert button colors appropriately**. Alert buttons are colored either dark or light. In an alert with two buttons, the button on the left is always dark-colored and the button on the right is always light-colored. In a one-button alert, the button is always light-colored.  
- In a two-button alert that proposes a potentially risky action, the button that cancels the action should be on the right (and light-colored).
- In a two-button alert that proposes a benign action that people are likely to want, the button that cancels the action should be on the left (and dark-colored).  
**Note:** A Cancel button may be either light-colored or dark-colored and it may be on the right or the left, depending on whether the alternate choice is destructive. Be sure to properly identify which button is the Cancel button in your code (for more information, see *UIAlertView Class Reference*).  
Pressing the Home button while an alert is visible should quit the app, as expected. Itshould also be identical to tapping the Cancel button—that is, the alert is dismissed and the action is not performed.  
**Give alert buttons short, logical titles**. The best titles consist of one or two words that make sense in the context of the alert text. Follow these guidelines as you create titles for alert buttons:  
- As with all button titles, use title-style capitalization and no ending punctuation.
- Use verbs and verb phrases, such as "Cancel," "Allow," "Reply," or "Ignore" that relate directly to the alert text.
- Use "OK" for a simple acceptance option if there is no better alternative. Avoid using "Yes" or "No."
- <span id="page-118-0"></span>● Avoid "you," "your," "me," and "my" as much as possible. Button titles that use these words are often both ambiguous and patronizing.