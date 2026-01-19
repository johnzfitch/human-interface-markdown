<!-- Chunk 141 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 3051 -->
Users must be able to change input they have written, drawn, or typed. In all the Newton input areas described in this chapter, people can use consistent techniques for the following data-editing actions:  
- Select text and shapes
- Join words
- Break one paragraph into two
- Erase text or shapes
- Insert space in text
- Insert new text
- Replace text
- Correct misrecognized text
- Change capitalization of text
- Change paragraph margins  
- <span id="page-189-0"></span>■ Remove extra space from paragraphs
- Duplicate text or shapes
- Change shapes
- Move objects  
The techniques people use for these editing actions are described in the next 12 sections (ending with ["Moving Objects" on page 6-32](#page-199-0)).  
To make these editing actions available in your application, you don't have to do anything at all as long as you use standard input elements based on Newton prototypes. Although you can make some of the editing actions available in custom input areas, you can't make them all available. In particular, it's impossible to implement the customary techniques for selecting multiple objects, moving objects, changing paragraph margins, and more.  
#### Selecting Text and Shapes 6  
Users must select text or shapes before copying, moving, or otherwise manipulating them. To select an object, a user holds down the pen on or near the object until a heavy mark appears under the pen and the Newton device makes a high-pitched sound. Then the user draws the highlighting mark over or around the object. (The sound does not happen if the "Pen sound effects" option is turned off in the Sound section of the built-in Preferences application.) [Figure 6-17](#page-190-0) shows how selection works.  
To select words, a user draws the highlighting mark across them. To select text that's on more than one line, a user draws the highlighting mark from the beginning of the first word to the end of the last word. To select several whole lines of text, a user draws the highlighting mark vertically through the lines of text.  
To select lines in a shape, a user draws the highlighting mark along the lines.  
To select whole paragraphs, shapes, or a combination of text and shapes, a user circles them with the highlighting mark. The highlighting mark doesn't need to be close to the items, as long as it encloses them completely and doesn't enclose anything else. The Newton system puts a gray selection box around the object or objects the user circled.  
**Figure 6-17** Selecting words and shapes  
<span id="page-190-0"></span>![](images/_page_190_Figure_3.jpeg)  
A user can extend a selection or select more objects by drawing additional highlighting marks. If they are far apart, the user may select one at a time. Selected objects do not have to be adjacent, but all selected objects must be in the same input area. Anything that is selected remains selected when the user selects more in the same input area. If a user selects nonadjacent objects,  
<span id="page-191-0"></span>objects that the user has not selected may appear within the borders of the gray selection box, but only the selected objects are highlighted.  
#### Erasing Text or Shapes 6  
To erase text or shapes, a user scrubs them out with zigzag gestures. Immediately after scrubbing, the user hears a poof sound and sees smoke clouds cover the scrubbed objects. The smoke quickly dissipates to reveal the scrubbed objects have disappeared.  
A zigzag must go back and forth at least four times to be considered a scrubbing gesture. The zigzag should have sharp corners, and each segment of the zigzag should be about the same length. The zigzag can have any of the four orientations shown in Figure 6-18.  
**Figure 6-18** Orientations of the scrubbing gesture  
![](images/_page_191_Picture_7.jpeg)  
Depending on the size of the zigzag, it can erase a letter, a word, or a group of words. Also depending on its size, one zigzag can erase a whole shape or part of one. In addition, a single zigzag can erase text and shapes that have been selected. [Figure 6-19](#page-192-0) shows examples of scrubbing a little and scrubbing a lot.  
<span id="page-192-0"></span>**Figure 6-19** Scrubbing a little or a lot A single word A group of words A single letter (scrub over the letter at least four times) Part of a shape Selected text and shapes (start scrubbing outside the selection to avoid moving it) A whole shape  
The effect of scrubbing may be different if a user first selects several objects. If a user selects several objects, contiguous or not, and then scrubs over all or any part of the selected objects, all the selected objects are deleted. Unselected objects, if any, are not deleted by this scrub. However, if nothing is selected, all objects touched by the scrubbing gesture are deleted.  
Your application doesn't have to do anything to handle scrubbing in input areas that are based on Newton prototypes. If you make other input areas, you must program them to recognize the scrubbing gesture, play the poof sound, and display the dissipating smoke animation sequence. Scale the smoke cloud to the size of the user's zigzag gesture, keeping the height and width proportional to the original image's dimensions. Do not scale the smoke cloud down so much that it becomes unrecognizable, even if the zigzag gesture is very small.  
#### <span id="page-193-0"></span>Joining Words 6  
To join words, a user draws a V between them at their baselines, as shown in Figure 6-20.  
**Figure 6-20** Joining two words  
#### Breaking Paragraphs 6  
To break one paragraph into two, a user draws a backwards L at the desired breaking point, as shown in Figure 6-21.  
**Figure 6-21** Breaking a paragraph into two paragraphs  
1. User draws a small V between two words 2. System joins the words  
![](images/_page_193_Figure_9.jpeg)  
![](images/_page_193_Figure_11.jpeg)  
1. User draws a backwards L 2. System breaks paragraph at that point  
#### Inserting Space in Text 6  
To insert space in text, users draw carets and lines as shown in [Figure 6-22](#page-194-0). The top of the caret should line up with the baseline of the letters.  
<span id="page-194-0"></span>![](images/_page_194_Figure_2.jpeg)  
#### Inserting New Text 6  
When a caret is displayed in an input area, it marks the point where the Newton system will insert newly written words. No matter where a user writes in the input area, the Newton system inserts the text at the caret. It doesn't matter whether the system is set for text recognition or ink text. Figure 6-23 illustrates the caret.  
**Figure 6-23** A caret marks the text insertion point  
| Caret |                                 |                                      |
|-------|---------------------------------|--------------------------------------|
|       |                                 |                                      |
|       |                                 |                                      |
|       | 1. User writes the word success | 2. New word is inserted at the caret |  
<span id="page-195-0"></span>A user can move the caret simply by tapping the screen at the desired location. Users always know and control exactly where their writing goes.  
The caret is not displayed if a user turns off the "Insert new words at caret" option in the Handwriting Recognition section of the built-in Preferences application. In that case, a user can insert a new word by writing it on top of the word it should precede; the Newton system shifts the old word to the right and inserts the new word.  
A user can input a punctuation mark or other special character by choosing it from the picker that pops up when the user taps the caret. In addition, the Caret picker allows a user to break a paragraph at the caret (moving the caret to the start of the new paragraph); delete the character to the left of the caret; or insert a blank space. Figure 6-24 shows the Caret picker.  
**Figure 6-24** The Caret picker lists 14 hard-to-write characters and three actions  
![](images/_page_195_Figure_6.jpeg)  
#### <span id="page-196-0"></span>Replacing Text 6  
By extending the method for inserting text, a user can replace existing text. Instead of tapping to position the caret, the user drags the highlighting mark to select the text to replace. Then the user writes the replacement text anywhere on the screen and the selected text is replaced.  
#### Correcting Misrecognized Text 6  
If the Newton system does not recognize a word correctly, the user can correct it by several means. For one, the user can replace any letter by writing another letter over it. The user also has the option of selecting or erasing the word and writing it again. Another alternative: the user can double-tap a word to pop up a picker that lists some alternate words. From the list of alternates the user can select one as a replacement. Figure 6-25 shows how a Correction picker works.  
**Figure 6-25** How a Correction picker works  
![](images/_page_196_Figure_7.jpeg)  
At the bottom of the Correction picker are three buttons: a Keyboard button, a Corrector button, and a Try Letters button. Tapping Try Letters causes the Newton system to ignore the recognition dictionaries and try to recognize the word letter by letter. Tapping the Keyboard button displays a keyboard,  
with which the user can type corrections. Tapping the Corrector button brings up a Corrector view, in which the user can make corrections to individual letters. The user can write over a letter to replace it, delete a letter by scrubbing it, or insert a space in which to write an additional letter. In addition, the user can tap a letter in the Corrector view to pop up a Correction picker that lists alternate letters plus the commands Insert and Delete. Figure 6-26 shows how a Corrector view works.  
**Figure 6-26** How a Corrector view works  
![](images/_page_197_Figure_4.jpeg)  
1. User taps Corrector button  
![](images/_page_197_Figure_6.jpeg)  
The Corrector view can also be used for bulk correction. In this scenario, the user leaves the Corrector open and one by one taps words to be corrected. Software developers can define corrector templates for different types of data (dates, times, etc.).  
#### <span id="page-198-0"></span>Changing Capitalization of Text 6  
To change how a word is capitalized, a user selects the word and then draws a vertical line over it. Drawing the line in an upward direction over the first letter of the word capitalizes that letter. Drawing the line upward over the middle of the word capitalizes all letters. Drawing the line downward changes capital letters to lowercase.  
#### Changing Paragraph Margins 6  
To change paragraph margins, a user selects the paragraph by drawing a selection box around it. Then the user holds the pen on the left or right side of the box and drags it.  
#### Removing Extra Space from Paragraphs 6  
To remove extra space from a paragraph, a user selects the paragraph by drawing a selection box around it. Then the user taps the border of the box.  
#### Duplicating Text or Shapes 6  
After selecting text or shapes, a user can duplicate the selection by quickly tapping twice inside the selection and not lifting the pen after the second tap. That gesture is called **tap-and-a-half** because the pen goes down, up, and down again (but not up again). Keeping the pen down, the user then drags a duplicate away from the original item.  
#### Changing Shapes 6  
After drawing a selection box around a whole shape, a user can drag any corner to change the shape. Dragging a corner or edge of the selection box stretches, shrinks, or distorts the whole shape.  
#### <span id="page-199-0"></span>Moving Objects 6  
A user can move an object—text, ink text, sketch, shape, or a combination of them—by selecting the object and then dragging it to another part of the same input area or to another visible input area. The user can also drag the selected object to the top, left, or right edge of the screen, where it becomes a miniature and attaches itself to the edge of the screen. Then the user can go to another view and drag the miniature from the edge of the screen to any visible input area.