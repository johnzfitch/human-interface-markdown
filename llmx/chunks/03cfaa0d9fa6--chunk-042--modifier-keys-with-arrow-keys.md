---
chunk_index: 705
ref: "03cfaa0d9fa6"
id: "03cfaa0d9fa66d368876aa4e5153816bd1d472ad6d1a44946723058b82b21f67"
slug: "chunk-042--modifier-keys-with-arrow-keys"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_042.md"
kind: "markdown"
lines: [21, 25]
token_estimate: 592
content_sha256: "8fd7b21afd5e187f3d1a536bb548fb3b9550c1a6066c11e3556823cdfc53e23b"
compacted: false
heading_path: ["**Appropriate** Uses **for the Arrow** Keys","**Moving the Insertion Point** ,-","Moving the Insertion Point in Empty Documents","Modifier Keys with Arrow Keys"]
symbol: null
address: null
asset_path: null
---

#### Modifier Keys with Arrow Keys  
Holding down the Apple key while pressing an arrow key should move the insertion point to the appropriate edge of the window. If the insertion point reaches the edge of the window, then the document is scrolled one windowful in the appropriate direction and the insertion point moves to the same edge of the new windowful. Apple—Up Arrow moves the insertion point to the top of the window, Apple—Down Arrow to the bottom, Apple—Left Arrow to the left edge, and Apple—Right Arrow to the right edge (but not past the last character).  
The Option key is reserved as a "semantic modifier" key. The application determines what the semantic units are. For example, in a word processor, where the basic semantic unit is the character and the next larger one is the word, Option–Left Arrow and Option-Right Arrow might move the insertion point to the beginning and end, respectively, of a word. (Movement of the insertion point by word boundaries should use the same definition of word that the application uses for double clicking.) The next larger semantic unit could be defined as the sentence, in which case Option–Shift–Left Arrow and Option–Shift–Right Arrow would move the insertion point to the beginning and end, respectively, of a sentence. In a programming language editor, where the basic semantic unit is the token and the next larger one might be the line, Option–Left Arrow and Option–Right Arrow might move the insertion point left and right to the beginning and end of the line, respectively.  
In an application (such as a spreadsheet) that represents itself as an array, the basic semantic unit would be the cell. Option—Left Arrow would designate the cell to the left of the currently active cell as the new active cell, and so on. Using modifier keys with arrow keys doesn't do anything to the data; Option—Left Arrow just performs an Enter and moves the selection to the next cell to the left.  
Though the use of multiple modifier key combinations (such as Command-Option-Left Arrow) is discouraged, it's all right to use the **Shift** key with any *one* of the other modifier keys for making a selection. (See "Making a Selection With Arrow Keys.") Keep in mind that if multiple keys must be pressed simultaneously, they should be fairly close together—otherwise many people won't be able to use that combination.