---
chunk_index: 1420
ref: "c77e62bc56f2"
id: "c77e62bc56f2477658755333579412250d70214f5ccc77ae8b806bf392399604"
slug: "full-document--selections-in-text"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1762, 1828]
token_estimate: 1189
content_sha256: "c4a2bac867763e751fcab52cd1a3109f0d014de9c8c16bed2ca6b3e9b4b10797"
compacted: false
heading_path: ["Selection by data type","Selections in text"]
symbol: null
address: null
asset_path: null
---

#### Selections in text

In most applications, the user is required at some point to edit text. The principle of consistency (both within and among applications) requires that text be selected and edited in a consistent way, regardless of where it appears.

A block of text is a string of characters. A text selection is a substring of this string, which can have any length from zero characters to the whole block. Each of the text selection methods selects a different kind of substring. Figure 56 shows different kinds of text selections.

| Insertion point            | Life is just a bowl of Apples! |
|----------------------------|--------------------------------|
| Range of characters        | Life is just a bowl of Apples! |
| Word                       | Life is just a bowl of Apples! |
| Range of words             | Life is just a bowl of Apples! |
| Discontinuous<br>selection | Life is ust a bowl of Apples   |

Figure 56 Text selections

The **insertion point** is a zero-length text selection. The user establishes the location of the insertion point by clicking somewhere in the text. The insertion point then appears at the nearest character boundary. If the user clicks anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character (unless the document is filled with space characters).

The insertion point shows where text will be inserted when the user begins typing, or where cut or copied data (the contents of the Clipboard) will be pasted. As each character is typed, it is inserted to the left of the insertion point.

If, between mouse-down (the moment the mouse button is pressed) and mouse-up (the moment the button is released), the user drags (moves the pointer more than about half the width of a character), the characters that were dragged across become selected (the selection is a *range selection* rather than an insertion point).

The user selects a whole *word* by double-clicking somewhere within that word. If the user begins a double-click sequence, but then drags the mouse between the mouse-down and the mouse-up of the second click, the selection becomes a range of words rather than a single word. As the pointer moves, the application highlights or unhighlights a whole word at a time.

A word, or range of words can also be selected in the same way as any other range; whether this type of selection is treated as a range of characters or as a range of words depends on the operation. For example, in MacWrite, a range of individual characters that happens to coincide with a range of words is treated like characters for purposes of extending a selection, but is treated like words for purposes of "intelligent cut and paste" (described later in this chapter under "Editing text").

The following definition of a *word* applies to the United States and Canada. In other countries, the definition differs to reflect local formats for numbers, dates, and currency. A word is defined as any continuous string that contains only the following characters:

- a letter
- a digit
- a nonbreaking space (Option-space or Apple-space)
- a currency symbol (\$, ¢, £, or ¥)
- a percent sign
- a comma between digits
- a period before a digit
- an apostrophe between letters or digits
- a hyphen, but not a minus sign (Option-hyphen) or a dash (Option-Shift-hyphen)

If the user double-clicks over any character *not* on the list above, only that character is selected.

These are examples of words:

\$123,456.78

shouldn't

3 1/2 (with a nonbreaking space)

5%

These are examples of strings treated as more than one word:

7/10/6

blue cheese (with a breaking space)

"Wow!" (The quotation marks and exclamation point aren't part of the word.)

In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parenthesis in a pair, as well as all the characters between them, by double-clicking on either one of them. The same feature could be implemented for both square and curly brackets. This would mean that the user could select the entire expression

 $[x+y-(4*3)\land (n-1)]$ 

simply by double clicking on [ or ].

The user selects a range of text by dragging through the range. A range can be a range of characters, words, lines, or paragraphs, as defined by the application.

If the user extends the range, the way the range is extended depends on what kind of range it is. If it's a range of individual characters, it can be extended one character at a time. If it's a range of words (including a single word), it's extended only by whole words.