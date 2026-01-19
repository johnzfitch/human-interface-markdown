---
chunk_index: 706
ref: "be49e9d799a6"
id: "be49e9d799a6f80fb54a36c426e9486467959fc951184792163739f26162e02f"
slug: "chunk-042--making-a-selection-with-arrow-keys"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_042.md"
kind: "markdown"
lines: [26, 47]
token_estimate: 910
content_sha256: "32c2080270fb086082ff0898eb2fb8e9f7b63003038fa90f80f238e449c530ad"
compacted: false
heading_path: ["**Appropriate** Uses **for the Arrow** Keys","**Moving the Insertion Point** ,-","Moving the Insertion Point in Empty Documents","Making a Selection With Arrow Keys"]
symbol: null
address: null
asset_path: null
---

#### Making a Selection With Arrow Keys  
To use arrow keys to make a selection, the user holds down Shift while pressing an arrow key. Application programs that depend (as TextEdit does) on the numeric keypad should not use these Shift-Arrow key combinations. This is because the key codes for the four Shift-arrow key combinations are the same as those for the keypad's +, \*, /, and = keys. If the use of Shift-arrow for making selections is more important to your application than is the numeric keypad, the following paragraphs tell how it should work.  
After a Shift-arrow key combination has been pressed, the insertion point moves and the range over which it moves becomes selected. If both the Shift key and another modifier key are held down, the insertion point moves (as defined for the particular modifier key) and the range over which the insertion point moves becomes selected. For example, Shift-Left Arrow selects the character to the left of the insertion point, Command-Shift-Left Arrow selects from the insertion point to the left edge of the window, and Option-Shift-Left Arrow selects the whole word that contains the character to the left of the insertion point (just like double clicking on a word).  
A selection made by using the mouse is no different from one made by using arrow keys. A selection started with the mouse can be extended by using Shift and Left or Right Arrow.  
The two ends of a selected range have different characteristics and different names. The **anchor point** is the location of the insertion point when selection was started. The **active end** is the place to which the insertion point moves to complete the selection. Once selection begins, the anchor point cannot be moved except by beginning a new selection. To extend or shrink a selection, the user moves the active end as specified here. As the active end moves, it can cross over the anchor point.  
In a text application, pressing Shift and either Left Arrow or Right Arrow selects a single character. Assuming that the Left Arrow key was used, the anchor point of the selection is on the right side of the selection, the active end on the left. Each subsequent Shift—Left Arrow adds another character to the left side of the selection. A Shift—Right Arrow at this point shrinks the selection. Figure 5 summarizes these actions.  
| 1. | Insertion point is within a word: | word |
|----|-----------------------------------|------|
| 2. | Shift- is pressed:                | ward |
| 3. | another Shift- 🖛 :                | word |
| 4. | Shift-→:                          | ward |
| 5. | three more times Shift-           | word |  
Figure 5. Selecting With-Shift-Arrow Keys  
Pressing Option—Shift and either Left Arrow or Right Arrow (in a text application) selects the entire word containing the character to the left of the insertion point. Assuming Left Arrow was used, the anchor point is at the right end of the word, the active end at the left. Each subsequent Option—Shift—Left Arrow adds another word to the left end of the selection, as shown in Figure 6.  
1. Insertion point is within a word:  
another word  
2. Option-Shift- is pressed:  
another word  
3. another Option-Shift- ::  
another word  
Figure 6. Selecting With Option-Shift-Arrow Keys  
Pressing Command—Shift—Left Arrow (in a text application) selects the area from the insertion point to the left edge of the window. The anchor point is at the right end of the selection, the active end is at the left. Each subsequent Command—Shift—Left Arrow scrolls the document one windowful left and extends the selection to the left edge of the new window.