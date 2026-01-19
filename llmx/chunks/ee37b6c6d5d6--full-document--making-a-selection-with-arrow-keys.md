---
chunk_index: 1421
ref: "ee37b6c6d5d6"
id: "ee37b6c6d5d61c7f1c1b827e76d6cd2bbcc66204a98326f2d4248a425a6e4492"
slug: "full-document--making-a-selection-with-arrow-keys"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1829, 1865]
token_estimate: 670
content_sha256: "8d6f3f9c011013c54b7fd966dc1cd81b52c041abb36569bdcc583cd59d3693f6"
compacted: false
heading_path: ["Selection by data type","Selections in text","Making a selection with arrow keys"]
symbol: null
address: null
asset_path: null
---

#### Making a selection with arrow keys

To use arrow keys to make a text selection, the user holds down Shift while pressing an arrow key. If it's important that your Macintosh application makes use of the numeric keypad, you shouldn't use these Shift-arrow key combinations. This is because the key codes for the four Shift-arrow key combinations are the same as those for the keypad's +, \*, /, and = keys. If the use of a Shift-arrow key combination for making selections is more important to your application than is the numeric keypad, the following paragraphs tell how it should work.

After a Shift-arrow key combination has been pressed, the insertion point moves and the range over which it moves becomes selected. If both the Shift key and another modifier key are held down, the insertion point moves as defined for the particular modifier key, and the range over which the insertion point moves becomes selected. For example, Option-Shift-Left Arrow selects the whole word that contains the character to the left of the insertion point (just like double clicking on a word).

A selection made by using the mouse is no different from one made by using arrow keys. A selection started with the mouse can be extended by using Shift and Left or Right Arrow.

In a text application, pressing Shift and either Left Arrow or Right Arrow selects a single character. Assuming that the Left Arrow key was used, the anchor point of the selection is on the right side of the selection, the active end on the left. Each subsequent Shift–Left Arrow adds another character to the left side of the selection. A Shift–Right Arrow at this point shrinks the selection. Figure 57 summarizes these actions.

| 1. | Insertion point is within a word: | word          |
|----|-----------------------------------|---------------|
| 2. | Shift- is pressed:                | w <b>g</b> rd |
| 3. | Another Shift- :                  | <b>w</b> rd   |
| 4. | Shift-                            | ward          |
| 5. | Three more times Shift-           | wo            |

Figure 57
Selecting with Shift-arrow keys

Pressing Option–Shift and either Left Arrow or Right Arrow (in a text application) selects the entire word containing the character to the left of the insertion point. Assuming Left Arrow were pressed, the anchor point is at the right end of the word, the active end at the left. Each subsequent Option–Shift–Left Arrow adds another word to the left end of the selection, as shown in Figure 58.

1. Insertion point is within a word:

another word

2. Option-Shift- is pressed:

another word

3. Another Option-Shift-

another word

Figure 58
Selecting with Option-Shift-arrow keys