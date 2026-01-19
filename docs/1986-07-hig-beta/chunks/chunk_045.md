<!-- Chunk 45 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 2782 -->
This section covers the topic of selection according of the *kind* of data involved: text, graphics, and arrays.  
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
#### Selections in Graphics  
There are several different ways to select graphic objects and to show selection feedback in existing applications. This section uses the MacDraw paradigm, but other situations may require other solutions.  
A MacDraw document is a collection of individual graphic objects. To select one of these objects, the user clicks once on the object, which is then bracketed with four "handles." (The handles are used to stretch or shrink the object, and aren't discussed here.) Figure 11 shows some examples of selection in MacDraw.  
![](images/_page_45_Picture_7.jpeg)  
Figure 11. Graphics Selections in MacDraw  
There are two ways to select more than one object. A range selection includes every object completely contained within the dotted rectangle that encloses the range as the user drags the mouse. A discontinuous selection includes only those objects explicitly selected.  
#### Selections in Arrays and Tables  
An array is a one- or two-dimensional arrangement of fields. The user can select one or more fields, or part of the contents of a field.  
To select a single field, the user clicks in the field (Figure 12). The user can also select a field by moving into it with the Tab or Return key.  
| r- | CI'<br>IC | ere<br>k h | o<br>t | se<br>ec<br>t | Hewei i | field, |
|----|-----------|------------|--------|---------------|---------|--------|
|----|-----------|------------|--------|---------------|---------|--------|  
| state      | capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenix        |
| California | Sacramento     |
| Colorado   | Denver         |
| Hawaii     | Honolulu       |
| Idaho      | Boise          |
| Montana    | Helena         |
| Nevada     | Carson City    |
| New Mexico | Santa Fe       |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
| Wyoming    | Cheyenne       |  
| state      | capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenh<        |
| California | Sacramento     |
| Colorado   | Denver         |
|            | Honolulu       |
| Idaho      | Boise          |
| Monhna     | Helena         |
| Nevada     | Carson City    |
| New Mexico | Sanh<br>Fe     |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
| Wyoming    | Cheyenne       |  
Figure 12. Field Selection in an Array  
To select part of the contents of a field, the user must first select the field. The user then clicks again to select the desired part of the field. Because the contents of a field are either text or graphics, this type of selection follows the rules outlined above.  
A table can also support selection of rows and columns. The most convenient way for the user to select a column is to click in the column header. To select more than one column, the user drags through several column headers. The same applies to rows.  
Figures 13, 14, and 15 show column, range, and discontinuous selections in arrays.  
| Click | here |
|-------|------|
|-------|------|  
| state      | capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenix        |
| California | Sacramento     |
| Colorado   | Denver         |
| Hawaii     | Honolulu       |
| Idaho      | Boise          |
| Montana    | Helena         |
| Nevada     | Carson City    |
| New Mexico | Santa Fe       |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
| Wyoming    | Cheyenne       |  
to select a column  
| state          | capital        |
|----------------|----------------|
| Alasia         | Juneau         |
| Ariex a        | Phoenix        |
| Eshio nis      | Sacramento     |
| Ealor site     | Denver         |
| Hawaii         | Honolulu       |
| ldsho          | Boise          |
| l londaria     | Helena         |
| [{k:::3d3      | Carson City    |
| Ne:: 1 1/2 100 | Santa Fe       |
| Dregon         | Salem          |
| Jtah /         | Salt Lake City |
| Washington     | Olympia        |
| W.froming      | Cheyenne       |  
Figure 13. Column Selection in an Array  
| state      | capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenix        |
| California | Sacramento     |
| Colorado   | Denver         |
| Hawaii     | Honolulu       |
| Idaho      | Boise          |
| Montana    | Helena         |
| Nevada     | , Carson City  |
| New Mexico | Santa Fe       |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
| Wyoming    | Cheyenne       |  
| capital        |
|----------------|
| Juneau         |
| Phoenix        |
| Sacramento     |
| Denver         |
| Honolulu       |
| Boise          |
| Helena         |
| Carson City    |
| Santa Fe       |
| Salem          |
| Salt Lake City |
| Olympia        |
| Cheyenne       |
|                |  
Drag through this area  
and release to make this selection.  
Figure 14. Range Selection in an Array  
| state      | capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenix        |
| California | Sacramento     |
| Colorado   | Denver         |
| Hawaii     | Honolulu       |
| Idaho      | Boise          |
| Montana    | Helena         |
| Nevada     | Carson City    |
| New Mexico | Santa Fe       |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
| Wyoming    | Cheyenne       |  
Figure 15. Discontinuous Selection in an Array  
The Tab key cycles through the fields in an order determined by the application. From each field, the Tab key selects the "next" field. Typically, the sequence of fields is first from left to right, and then from top to bottom. When the last field in a form is selected, pressing the Tab key selects the first field in the form. If there's a good reason, an application may guide the user through the fields in some order other than the order in which the fields appear on the screen.  
The Return key selects the first field in the next row. If the idea of rows doesn't make sense in a particular context, then the Return key should have the same effect as the Tab key.