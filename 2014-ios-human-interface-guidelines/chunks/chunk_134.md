<!-- Chunk 134 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 2379 -->
An **alert** gives people important information that affects their use of an app or the device.  
![](images/_page_196_Picture_3.jpeg)  
**API Note:** To learn about using an alert in your code, see *UIAlertView Class Reference* .  
#### An alert:  
- Displays a required title and an optional message
- Contains one or more buttons  
The infrequency with which alerts appear helps users take them seriously. It's best to minimize the number of alerts your app displays, and make sure each one offers critical information and useful choices.  
**Avoid creating unnecessary alerts.** In general, alerts are unnecessary in the following scenarios:  
| If an alert does this                                                                         | Do this instead of using an alert                                                                                                                                                                                                                   |
|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Provides<br>information<br>related<br>to<br>the<br>standard<br>functioning<br>of<br>an<br>app | Design<br>an<br>eye-catching<br>way<br>to<br>display<br>the<br>information,<br>one<br>that<br>harmonizes<br>with<br>the<br>app's<br>style.                                                                                                          |
| Updates<br>users<br>on<br>tasks<br>that<br>are<br>progressing<br>normally                     | Use<br>a<br>progress<br>view<br>or<br>activity<br>indicator<br>(described<br>in<br>"Progress<br>View"<br>(page<br>189)<br>and<br>"Activity<br>Indicator"<br>(page<br>182))<br>or<br>integrate<br>status<br>information<br>into<br>the<br>app<br>UI. |
| Asks<br>for<br>confirmation<br>of<br>user-initiated<br>tasks                                  | Use<br>an<br>action<br>sheet<br>(described<br>in<br>"Action<br>Sheet"<br>(page<br>200)).                                                                                                                                                            |  
| If an alert does this                                                       | Do this instead of using an alert                                                                                                                 |
|-----------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| Informs<br>users<br>of<br>problems<br>they<br>can<br>do<br>nothing<br>about | If<br>the<br>problem<br>isn't<br>critical,<br>integrate<br>the<br>information<br>into<br>the<br>app's<br>UI;<br>otherwise,<br>use<br>an<br>alert. |  
As you read the guidelines for designing alert text, it's useful to know the following definitions:  
- **Title-style capitalization** means that every word is capitalized, except articles, coordinating conjunctions, and prepositions of four or fewer letters when they aren't the first word.
- **Sentence-style capitalization** means that the first word is capitalized, and the rest of the words are lowercase unless they are proper nouns or proper adjectives.  
**Succinctly describe the situation and explain what people can do about it.** Ideally, the text you write gives people enough context to understand why the alert has appeared and to decide which button to tap.  
![](images/_page_197_Picture_6.jpeg)  
**Keep the title short enough to display on a single line, if possible.** A long alert title is difficult for people to read quickly, and it might get truncated or force the alert message to scroll.  
**Avoid single-word titles.** Single-word titles, such as Error or Warning, rarely provide any useful information.  
**When possible, use a sentence fragment.** A short, informative statement tends to be easier to understand than a complete sentence.  
**As much as possible, write a title that makes it unnecessary to add a message.** For example, you might be able to avoid adding a message if you use a question—or, less frequently, two sentences—for the alert title.  
**Don't hesitate to be negative.** People understand that most alerts tell them about problems or warn them about dangerous situations. It's better to be negative and direct than it is to be positive but oblique.  
**As much as possible, avoid "you," "your," "me," and "my."** Sometimes, text that identifies people directly can be ambiguous and can even be interpreted as insulting or patronizing.  
**Use capitalization and punctuation appropriately.** Specifically:  
| When the alert title                                                                                   | Use                                                                                                        |
|--------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| Is<br>a<br>sentence<br>fragment<br>or<br>a<br>single<br>sentence<br>that<br>is<br>not<br>a<br>question | Title-style<br>capitalization<br>and<br>no<br>ending<br>punctuation                                        |
| Is<br>a<br>single<br>sentence<br>that<br>is<br>a<br>question                                           | Sentence-style<br>capitalization<br>and<br>an<br>ending<br>question<br>mark                                |
| Consists<br>of<br>two<br>or<br>more<br>sentences                                                       | Sentence-style<br>capitalization<br>and<br>appropriate<br>ending<br>punctuation<br>for<br>each<br>sentence |  
**If you must provide an optional alert message, write a short, complete sentence.** If possible, keep the message short enough to be displayed on one or two lines. If the message is too long, it will scroll, giving users a poor experience. Use sentence-style capitalization and appropriate ending punctuation in the message.  
![](images/_page_198_Picture_3.jpeg)  
**Avoid lengthening alert text with descriptions of which button to tap.** Ideally, the combination of unambiguous alert text and logical button labels gives people enough information to understand the situation and their choices. If you must provide detailed guidance, follow these guidelines:  
- Be sure to use the word "tap" (not "touch" or "click" or "choose") to describe the selection action.
- Don't enclose a button title in quotation marks, but do preserve its capitalization.  
**Be sure to test the appearance of an alert in both orientations.** Because in landscape the height of an alert is constrained, the alert's appearance may differ from its appearance in portrait. It's recommended that you optimize the length of the alert text so that it can be read without scrolling no matter what the orientation.  
![](images/_page_198_Picture_8.jpeg)  
**Generally, use a two-button alert.** A two-button alert is often the most useful, because it's easiest for people to choose between two alternatives. A single button alert is less likely to be helpful because it informs people without giving them any control over the situation. An alert that contains three or more buttonsissignificantly more complex than a two-button alert and should be avoided as much as possible. If you add too many buttons to an alert, it can cause the alert to scroll, which is a bad user experience.  
**Note:** If you find that you need to offer people more than two choices, consider using an action sheet instead (to learn how to use an action sheet, see ["Action](#page-199-0) Sheet" (page 200)).  
**Place buttons appropriately.** Ideally, the button that's most natural to tap should meet two criteria: It should perform the action that users are most likely to want and it should be the least likely to cause problems if a user taps it inadvertently. Specifically:  
- When the most likely button performs a nondestructive action, it should be on the right in a two-button alert. The button that cancels this action should be on the left.
- When the most likely button performs a destructive action, it should be on the left in a two-button alert. The button that cancels this action should be on the right.  
**Note:** Pressing the Home button while an alert is visible should quit the app, as expected. Doing so should also be identical to tapping the Cancel button—that is, the alert is dismissed and the action isn't performed.  
**Give alert buttons short, logical titles.** The best button titles consist of one or two words that describe the result of tapping the button. Follow these guidelines as you create titles for alert buttons:  
- As with all button titles, use title-style capitalization and no ending punctuation.
- As much as possible, use verbs and verb phrasesthat relate directly to the alert text—for example, "Cancel," "View All," "Reply," or "Ignore."
- Use "OK" for a simple acceptance option if there is no better alternative. Avoid using "Yes" or "No."
- <span id="page-199-0"></span>● Avoid "you," "your," "me," and "my" as much as possible. Button titles that use these words are often ambiguous and can appear patronizing.