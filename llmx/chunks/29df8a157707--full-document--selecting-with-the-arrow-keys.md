---
chunk_index: 2894
ref: "29df8a157707"
id: "29df8a157707002d032b48dac9ff7d5e8df9b6764596bf99b16dcda0eb70d17e"
slug: "full-document--selecting-with-the-arrow-keys"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4621, 4646]
token_estimate: 779
content_sha256: "4de820538679679403e4c18c3915428420eb2002e56d060f96becbb80acb9594"
compacted: false
heading_path: ["Selecting","Selections in Text","Selecting With the Mouse","Selecting With the Arrow Keys"]
symbol: null
address: null
asset_path: null
---

#### Selecting With the Arrow Keys

To use arrow keys to make a text selection, the user holds down Shift while pressing an arrow key. If it's important that your Macintosh application makes use of the numeric keypad, you shouldn't use these Shift–arrow key combinations. This is because the keypad's codes for the four Shift–arrow key combinations are the same as those for the keypad's +, \*, /, and = keys. If the use of a Shift–arrow key combination for making selections is more important to your application than is the numeric keypad, the following paragraphs describe how it should work.

When a Shift–arrow key combination is pressed, the active end of the selection moves and the range over which it moves becomes selected. If both the Shift key and another modifier key are held down, the end of the selection moves as defined for the particular modifier key, and the range over which it moves becomes selected. For example, Option–Shift–Left Arrow selects the whole word that contains the character to the left of the insertion point (just like double-clicking a word).

A selection made by using the mouse is no different from one made by using arrow keys. A selection started with the mouse can be extended by using Shift and Left Arrow or Right Arrow.

In a text application, pressing Shift and either Left Arrow or Right Arrow selects a single character. If the Left Arrow key is used, the anchor point of the selection is on the right side of the selection, the active end on the left. Each subsequent Shift–Left Arrow adds another character to the left side of the selection. In many applications, a Shift–Right Arrow at this point shrinks the selection. In some applications, a Shift–Right Arrow at this point extends the selection, making the right side of the selection the active end (see the description of the addition and fixed-point methods for extending text selections in "Changing a Selection With Shift-Click" beginning on page 289). In this case, each subsequent Shift–Right Arrow adds another character to the right side of the selection.

Selecting **295**

Figure 10-20 summarizes these two different series of steps.

**Figure 10-20** Selecting with Shift and arrow keys

![](images/_page_319_Figure_4.jpeg)

Pressing Option-Shift and either Left Arrow or Right Arrow (in a text application) selects the entire word containing the character to the left or right of the insertion point. Assuming Left Arrow is pressed, the anchor point is at the right end of the word, the active end at the left. Each subsequent Option–Shift–Left Arrow adds another word to the left end of the selection, as shown in Figure 10-21.

**Figure 10-21** Selecting with Option-Shift and arrow keys

When a block of text is selected, either with a pointing device or with arrow keys, pressing either Left Arrow, Right Arrow, Up Arrow, or Down Arrow deselects the range. If Left Arrow is pressed, the insertion point goes to the beginning of what had been the selection. If Right Arrow is pressed, the insertion point goes to the end of what had been the selection.

![](images/_page_320_Picture_2.jpeg)