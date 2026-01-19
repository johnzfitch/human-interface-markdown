<!-- Chunk 71 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 1294 -->
A **text button** is a rounded rectangle containing text that names the button's function. Figure 3-2 shows some typical text buttons in a slip.  
**Figure 3-2** A text button's name states what the button does  
![](images/_page_95_Picture_9.jpeg)  
#### <span id="page-96-0"></span>Text Button Sizes 3  
A text button should be the same height as the large Close box (described under ["Close Boxes" on page 3-14](#page-107-0)) and wide enough for its name to fit centered on one line in the bold style of the system font. Make the button wide enough to leave as much space at the sides of the text as there is space above the text.  
On an Apple MessagePad, make text buttons 13 pixels tall (not counting the 2-pixel black border). Use 9-point text in the bold style of the system font for the button name. Leave three pixels between the button's bottom border and the baseline of the text, and make the button wide enough to leave three or four pixels between the name and the button's left and right borders. In a group of buttons, you can make all buttons uniformly narrower if you must, but always leave at least two pixels of white space at the right and left ends of the text. Figure 3-3 shows the preferred spacing between the name and border of a text button on an Apple MessagePad.  
**Figure 3-3** Leave standard margins between a button's name and its borders  
![](images/_page_96_Figure_6.jpeg)  
Buttons **3-3**  
<span id="page-97-0"></span>If your application has buttons whose names change during the operation of the application, the application must resize the button when its name changes so that the spacing always conforms to the guidelines.  
#### Naming Text Buttons 3  
Keep button names short. Never use more than three words for a button name, and try to limit button names to one word. Capitalize button names like book titles. That is, always capitalize the first and last words of the name, and capitalize all other words except articles (*a, an, the*), coordinating conjunctions (for example, *and, or*), and prepositions of three or fewer letters. Since button names should seldom be more than two words, almost all words in button names should be capitalized.  
Avoid punctuation and symbols in button names. Except for very common symbols such as an ampersand (&), users find symbols ambiguous. Do not use ellipses (…) in the button name even if tapping the button displays another slip. However, a button name should begin with a diamond symbol (◆) if the button pops up a picker. (For complete information on pickers, see [Chapter 4, "Pickers"](#page-126-0)).  
#### Naming Take-Action Buttons 3  
A user typically reads the text in a slip until it becomes familiar, and then relies on visual cues, such as button names or positions, to respond. To assist users in quickly spotting which button in the slip initiates an action, name the take-action button with a specific verb such as Print, Fax, or File. These words are self-sufficient, whereas vaguely affirmative names such as OK and Yes require the user to scan other parts of the slip to verify what action the button initiates. [Figure 3-4](#page-98-0) compares a specific button name to a generic button name in the same context.  
<span id="page-98-0"></span>**Figure 3-4** Name buttons distinctively wherever possible  
![](images/_page_98_Picture_3.jpeg)  
There are cases where a button named OK or Yes serves best. You may want to name a button with a vague affirmative to encourage the user to look elsewhere in the slip for a complete description of a pending action with far-reaching consequences. Another place to use OK or Yes is in a slip where you simply can't name the action to be taken with one or two words. If you name buttons with generic words, be sure other text in the slip makes clear what action the button initiates.  
#### Naming Cancel- and Stop-Action Buttons 3  
A slip with a button that initiates an action also needs a means of canceling the pending action. On a Newton device you ordinarily use a large Close box (described under ["Close Boxes" on page 3-14](#page-107-0)), not a button named Cancel, to dismiss a slip and take no action. However, you can use a button named Cancel to complement an OK or Yes button. [Figure 3-5](#page-99-0) shows where to use a Cancel button and where not to use one.  
Buttons **3-5**  
<span id="page-99-0"></span>**Figure 3-5** Where to use a button named Cancel  
![](images/_page_99_Picture_3.jpeg)  
A button named Cancel should close the view it's in and return the application to the state it was in before the view appeared. Cancel means "Dismiss the operation I started, with no other effects." A Cancel button should not be the only button that can close a view; in such a view, use a Close box instead.  
Rather than Cancel, use a text button named Stop to allow a user to halt an operation that's underway, especially if this button is next to a large Close box. In that context a Cancel button may look to some users like a duplicate of the Close box. Figure 3-6 illustrates the use of a Stop button.  
**Figure 3-6** A Stop button lets a user halt an operation  
![](images/_page_99_Picture_7.jpeg)