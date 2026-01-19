---
chunk_index: 2038
ref: "5f2d46983d72"
id: "5f2d46983d7214579af9085ebccae72c115834bb4962463556abc68567613ef3"
slug: "full-document--selections-in-text"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2337, 2399]
token_estimate: 1765
content_sha256: "46706f22b732a833e01178232b255cd1a606edc6935f51b61955e07f92b7a27e"
compacted: false
heading_path: ["Selection by data type","Selections in text"]
symbol: null
address: null
asset_path: null
---

#### Selections in text

In most applications, the user is required at some point to edit text. The principle of consistency (both within and among applications) requires that text be selected and edited in a consistent way, regardless of where it appears.

A block of text is <sup>a</sup> string of characters. A text selection is <sup>a</sup> substring of this string, which can have any length from zero characters to the whole block. Each of the text selection methods selects a different kind of substring. Figure 3-56 shows different kinds of text selections.

| point<br>Insertion         | bowl<br>Apples'<br>just<br>of<br>a<br>Li<br>is<br>fe]<br>/ |
|----------------------------|------------------------------------------------------------|
| Range<br>characters<br>of  | 1 ''<br>Q83<br>[^^J^<br>J^'                                |
| Word                       | Apples'<br>i ife<br>lust<br>iaawii<br>of<br>a<br>is        |
| Range<br>words<br>of       | ^a<br>bowl<br>Apples'<br>of                                |
| Discontinuous<br>selection | isj^^a<br>bowl<br>Life<br>of                               |

Figure 3-56 Text selections

The insertion point is a zero-length text selection. The user establishes the location of the insertion point by clicking somewhere in the text. The insertion point then appears at the nearest character boundary. If the user clicks anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character (unless the document isfilled with space characters).

The insertion point shows where text will be inserted when the user begins typing, or where cut or copied data (the contents of the Clipboard) will be pasted. As each character is typed, it is inserted to the left of the insertion point.

If, between mouse-down (the moment the mouse button is pressed) and mouse-up (the moment the button is released), the user drags (moves the pointer more than about half the width of a character), the characters that were dragged across become selected. The selection is a range selection rather than an insertion point.

The user selects a whole word by double-clicking somewhere within that word. If the user begins a double-click sequence, but then drags the mouse between the mouse down and the mouse-up of the second click, the selection becomes <sup>a</sup> range of words rather than a single word. As the pointer moves, the application highlights or unhighlights a whole word at a time.

A word or range of words can also be selected in the same way as any other range; whether this type of selection is treated as a range of characters or as a range of words depends on the operation. For example, in MacWrite, a range of individual characters that happens to coincide with a range of words is treated like characters for purposes of extending a selection, but is treated like words for purposes of "intelligent cut and paste" (described later in this chapter under "Editing Text").

The following definition of a word applies in the United States and Canada. In other countries, the definition differs to reflect local formats for numbers, dates, and currency. A word is defined as any continuous string that contains only the following

| characters:                                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
| a<br>letter                                                                                                                                          |
| D<br>a<br>digit                                                                                                                                      |
| nonbreaking<br>space<br>(Option-space<br>or<br>Apple-space)<br>a                                                                                     |
| symbol<br>currency<br>¥)<br>a<br>or<br>£,<br>(\$,<br><t,< td=""></t,<>                                                                               |
| percent<br>a<br>sign                                                                                                                                 |
| comma<br>between<br>a<br>digits                                                                                                                      |
| period<br>before<br>a<br>a<br>digit                                                                                                                  |
| an<br>between<br>apostrophe<br>or<br>letters<br>digits                                                                                               |
| D<br>hyphen,<br>minus<br>but<br>not<br>(Option-hyphen)<br>dash<br>(Option-Shift-hyphen)<br>a<br>a<br>sign<br>or<br>a                                 |
| any<br>on<br>user<br>over<br>the<br>double-clicks<br>not<br>only<br>character<br>the<br>above,<br>character<br>If<br>that<br>list<br>is<br>selected. |
| These<br>examples<br>of<br>words:<br>are                                                                                                             |
| \$123,456.78                                                                                                                                         |
| shouldn't                                                                                                                                            |
| 3<br>nonbreaking<br>1/2<br>(with<br>space)<br>a                                                                                                      |
| .5%                                                                                                                                                  |

These are examples of strings treated as more than one word:

7/10/6

blue cheese (with a breaking space)

"Wow!" (The quotation marks and exclamation point aren't part of the word.)

In some contexts—in <sup>a</sup> programming language, for example—it may be appropriate to allow users to select both the left and right parentheses in a pair, as well as all the characters between them, by double-clicking on either one of them. The same feature could be implemented for both braces and brackets. This would mean that the user could select the entire expression

[x+;K4\*3) A (rc-l)]

simply by double-clicking on [ or ].

The user selects <sup>a</sup> range of text by dragging through the range. A range can be <sup>a</sup> range of characters, words, lines, or paragraphs, as defined by the application.

If the user extends the range, the way the range is extended depends on what kind of range it is. If it's a range of individual characters, it can be extended one character at a time. If it's a range of words (including a single word), it's extended only by whole words.