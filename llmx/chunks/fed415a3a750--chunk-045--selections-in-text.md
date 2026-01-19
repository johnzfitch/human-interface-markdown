---
chunk_index: 717
ref: "fed415a3a750"
id: "fed415a3a750b97a3a9c19158c26af539a2e48b711cc9de5efd56ff8dd2e9e0f"
slug: "chunk-045--selections-in-text"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_045.md"
kind: "markdown"
lines: [3, 46]
token_estimate: 1176
content_sha256: "4ffd34618d2b8b180b654bd1c8310788c50f116983cc9fe8f3e9d370a5569929"
compacted: false
heading_path: ["Selections in Text"]
symbol: null
address: null
asset_path: null
---

#### Selections in Text  
In most applications, the user is required at some point to edit text. The principle of consistency (both within and between applications) requires that text be selected and edited in a consistent way, regardless of where it appears.  
A block of text is a string of characters. A text selection is a substring of this string, which can have any length from zero characters to the whole block. Each of the text selection methods selects a different kind of substring. Figure 10 shows different kinds of text selections.  
| Insertion point            | Life is just a bowl of Apples! |
|----------------------------|--------------------------------|
| Range of characters        | Life is just a bowl of Apples! |
| Word                       | Life is just a bowl of Apples! |
| Range of words             | Life is just a bowl of Apples! |
| Discontinuous<br>selection | Life is just a bowl of Apples  |  
Figure 10. Text Selections  
The insertion point is a zero-length text selection. The user establishes the location of the insertion point by clicking somewhere in the text. The insertion point then appears at the nearest character boundary. If the user clicks anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character (unless the document is filled with space characters).  
The insertion point shows where text will be inserted when the user begins typing, or where cut or copied data (the contents of the Clipboard) will be pasted. After each character is typed, the insertion point is moved to the right of the insertion.  
If, between the mouse-down and the mouse-up, the user drags (moves the pointer more than about half the width of a character), the selection is a range selection rather than an insertion point.  
The user selects a whole word by double clicking somewhere within that word. If the user begins a double click sequence, but then drags the mouse between the mouse-down and the mouse-up of the second click, the selection becomes a range of words rather than a single word. As the pointer moves, the application highlights or unhighlights a whole word at a time.  
A word, or range of words, can also be selected in the same way as any other range; whether this type of selection is treated as a range of characters or as a range of words depends on the operation. For example, in MacWrite, a range of individual characters that happens to coincide with a range of words is treated like characters for purposes of extending a selection, but is treated like words for purposes of "intelligent cut and paste" (described later in "Text Editing").  
The following is the definition of a word in the United States and Canada. In other countries, the definition differs to reflect local formats for numbers, dates, and currency. A word is defined as any continuous string that contains only the following characters:  
- a letter (including letters with diacritical marks)
- · a digit
- a nonbreaking space (Option-space or Apple-Space)
- a currency symbol (\$, ¢, £, or ¥)
- · a percent sign
- · a comma between digits
- · a period before a digit
- · an apostrophe between letters or digits
- a hyphen, but *not* a minus sign (Option-hyphen) or a dash (Option-Shift-hyphen)  
If the user double-clicks over any character *not* on the list above, that character is selected, but it is not considered a word.  
These are examples of words:  
```
$123,456.78
shouldn't
3 1/2 (with a nonbreaking space)
.5%
```  
These are examples of nonwords:  
```
7/10/6 blue cheese (with a breaking space) "Wow!" (The quotation marks and exclamation point aren't part of the word.)
```  
In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parenthesis in a pair, as well as all the characters between them, by double clicking on either one of them. The same could be implemented for both square and curly brackets. This would mean that the user could select the entire expression  
```
[x+y-(4*3)^{n-1}]
```  
simply by double clicking on [ or ].  
The user selects a range of text by dragging through the range. A range is either a range of words or a range of individual characters, as described under "Selecting Words."  
If the user extends the range, the way the range is extended depends on what kind of range it is. If it's a range of individual characters, it can be extended one character at a time. If it's a range of words (including a single word), it's extended only by whole words.