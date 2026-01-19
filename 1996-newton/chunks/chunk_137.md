<!-- Chunk 137 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 1562 -->
There are several interface elements for text input. They can accept all types of written input, including general text, numbers, phone numbers, dates, and time. Applications can also tune the text-input elements for a specific type of text, such as numbers, phone numbers, or dates. All text-input elements have the following capabilities:  
- **Recognition** Automatically transform handwriting or printing to typeset text. (An application can let users turn off or delay recognition.)
- **Ink Text** Display and store handwriting and printing exactly as written, in **electronic ink,** for later transformation to typeset text at the user's discretion.
- **Text insertion** Add newly written words at the **caret** symbol displayed on the screen or at the end of the nearest line, depending on how the user sets handwriting preferences.
- **Clipping** Automatically clip text that won't fit, by showing an ellipsis to indicate text beyond what is visible.
- **Correction** Let users correct misrecognized text.  
- <span id="page-176-0"></span>■ **Editing** Let users edit text—select, delete, copy-and-paste, duplicate, and move.
- **Formatting** Let users format individual words and characters in several different fonts, styles, and sizes.  
Where there is space to write paragraphs of text (not just single lines), the text input elements also have these capabilities:  
- **Word wrap** Re-form lines of text as a user writes additional words, adjusting spaces between words and wrapping words from the end of a full line to the beginning of the next line without breaking in the middle of the word.
- **Paragraph resizing** Automatically lengthen or shorten a paragraph as a user adds or deletes words from it, and allow a user to select and manually resize paragraphs.
- **Side-by-side paragraphs** Create a new paragraph alongside an existing one when a user writes words far away from the existing paragraph.  
Almost all of these capabilities apply both to recognized text and to ink text. The exception: Users cannot correct ink text, since it has not been recognized. (Users can edit ink text, however.)  
#### Simple Input Line 6  
A simple **input line** consists of a dotted line to write on, as shown in Figure 6-7.  
**Figure 6-7** How an unlabeled text-input line works  
![](images/_page_176_Picture_12.jpeg)  
#### <span id="page-177-0"></span>Labeled Input Line 6  
A labeled input line consists of a simple input line with a text label at its left. Optionally this label can have a pop-up picker that lists common values, and a user can choose one to save the effort of writing it. As usual, a diamond at the beginning of a label indicates the option of a picker. Figure 6-8 shows examples of labeled input lines with and without a picker.  
![](images/_page_177_Figure_4.jpeg)  
If you choose to implement the picker behavior, it means users can tap the label to pop up a list of input options. If a user chooses from the picker, that choice appears on the input line as if the user wrote it there. The choice is marked with a check mark in the picker. Ordinarily the chosen text replaces all text on the input line, if any. Your application can provide different behavior, if necessary. For example, choosing from the Please picker in the Assist slip inserts the chosen text at the beginning of the input line without replacing any text.  
#### <span id="page-178-0"></span>Text Input Lines that Expand 6  
You can reduce the amount of space required for several stacked input lines in your application by using expanding input lines, which are called **expandos.**  Each expando consists of a text label to the left and a text value to its right. When a user taps an expando (the label or the value), a text-input area expands from it. A user can write in the expanded text-input area, and can close it by tapping another expando. Closing an expando collapses it and updates its value. If the expando currently has no value, two hyphens are displayed. Figure 6-9 shows how an expando works.  
**Figure 6-9** How expandos work  
![](images/_page_178_Figure_5.jpeg)  
1. After editing the expanded field, a user taps an input field that's not expanded  
![](images/_page_178_Picture_7.jpeg)  
2. The previously expanded field collapses and the tapped field expands  
Although expandos seem to make the most of a small amount of screen space quite elegantly, they have not proven successful with users. The way they work is not particularly intuitive, and users are prone to making mistakes with expandos even after learning how to use them. Instead of expandos, you should consider using straightforward labeled input lines in slips.  
Avoid including buttons or other controls in expandos. When expanded, an expando should only contain an input line. If your application needs more than that in an expando, it should be using slips instead.  
#### <span id="page-179-0"></span>Paragraph Input 6  
Another interface element accepts the input of multiple lines or paragraphs of text. This interface element can appear simply as a blank area in which a user can write information, but usually it contains one or more horizontal dotted lines, like lined writing paper. These lines indicate to users that the area accepts input. Figure 6-10 shows an example.  
**Figure 6-10** Interface element for multiple-line or paragraph text input  
![](images/_page_179_Picture_5.jpeg)  
#### Structured List Input 6  
The Newton interface also includes an element for the input of structured lists such as outlines and checklists. A structured list consists of a sequence of topics, each of which may be one or more paragraphs long. To the left of each topic is a small circular topic marker and an optional checkbox. A user can drag a topic's marker to move that topic above or below another topic. A user can make a topic subordinate or not subordinate to the topic above it by dragging its marker right or left. This ability to create a topic hierarchy can be suppressed by an application in any structured list. [Figure 6-11](#page-180-0) shows an example of a structured list view.  
**Figure 6-11** A user can rearrange a structured list by dragging topic markers  
<span id="page-180-0"></span>![](images/_page_180_Figure_3.jpeg)