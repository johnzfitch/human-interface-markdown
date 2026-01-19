---
chunk_index: 398
ref: "f81bbd4efcfe"
id: "f81bbd4efcfe49cd428cb88a94d13ea9c33289dc18b0b34fc9a6ea918c5efb55"
slug: "chunk-067"
path: "marker/1985 Apple II Human Interface Guidelines/chunks/chunk_067.md"
kind: "markdown"
lines: [1, 31]
token_estimate: 502
content_sha256: "211c9776747558185e4c63abd93a86b438d3b016f21ceefaab2f789807d2cdfc"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 67 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 478 -->
The user selects a whole word by double-clicking somewhere within that word. If the user begins a double-click sequence, but then drags the mouse between the mouse-down and the mouse-up of the second click, the selection becomes a range of words rather than a single word. As the pointer moves, the application highlights or unhighlights a whole word at a time. The cursor-key user cannot select a range of words, although she can select the whole first word or paragraph by pressing Open-Apple-M repeatedly.  
A word, or range of words, can also be selected in the same way as any other range; whether this type of selection is treated as a range of  
1/15/84 Tognazzini  
characters or as a range of words depends on the operation. For example, in MacWrite, a range of individual characters that happens to coincide with a range of words is treated like characters for purposes of extending a selection, but is treated like words for purposes of intelligent cut and paste.  
A word is defined as any continuous substring that contains only the following characters:  
- a letter (including letters with diacritical marks)
- a digit
- a nonbreaking space (Open-Apple-Space)
- a dollar sign, cent sign, English pound symbol, or yen symbol
- a percent sign
- a comma between digits
- a period before a digit
- an apostrophe between letters or digits
- a hyphen, but not a minus sign (Open-Apple-hyphen)  
This is the definition in the United States and Canada; in other countries, it would have to be changed to reflect local formats for numbers, dates, and currency.  
If the user double-clicks over any character not on the list above, only that character is selected.  
Examples of words:  
```
$123,456.78
shouldn't
3 1/2 [with a nonbreaking space]
.5%
```  
Examples of nonwords:  
```
7/10/6
blue cheese [with a breaking space]
"Yoicks!" [the quotation
marks and exclamation point aren't part of the word]
```