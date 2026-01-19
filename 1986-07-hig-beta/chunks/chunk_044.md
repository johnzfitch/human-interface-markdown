<!-- Chunk 44 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 1887 -->
It's useful to distinguish among the three types of objects with which an application can deal: text, graphics, and lists (or arrays). Strictly speaking, *everything* on a Macintosh screen is displayed graphically, because the Macintosh has no text mode.  
The rest to some fai nt meani ng make pretence But Shad\v'e11 neve r devi ates into se nse. Some beams of \v'it on other souls may fall, Stri ke through and make a 1ucid interval; But Shad\v'ell's genuine night admits no ray, His risi ng fogs prevail upon the day.  
MacFlecknoe  
Page 1  
Text  
| Advertisi<br>ng   | 132.9 |  |
|-------------------|-------|--|
| Manufacturi<br>ng | 121.3 |  |
| R&D               | 18.7  |  |
| Inte<br>rest      | 12.2  |  |
|                   |       |  |
| Total             | 285.1 |  |
|                   |       |  |  
Arrey  
![](images/_page_39_Figure_7.jpeg)  
Graphics  
**Figure** 7. Three Ways of Structuring Infonnation  
**Text** can be arranged on the screen in a variety of ways. Some applications, such as word processors, might consist of nothing but text, whereas others, such as graphics-oriented applications, might use text almost incidentally. It's useful to consider all the text appearing together in a particular context as a block of text. The size of the block can range from a single field, as in a dialog box, to the whole document, as in a word processor.  
Regardless of its size or arrangement, the application sees each block as a one-dimensional string of characters. Text is edited the same way regardless of where it appears.  
Graphics are pictures, drawn either by the user or by the application. Graphics in a document tend to consist (but do not have to consist) of discrete objects, each of which can be selected individually.  
Arrays are one- or two-dimensional arrangements of fields. One-dimensional arrays are called lists, two-dimensional arrays are called tables or forms. Each field, in turn, contains a collection of information, usually text, but possibly graphics. A table can be easily identified on the screen, because it consists of rows and columns of fields (sometimes called cells) separated by horizontal and vertical lines. A form is something the user fills out, like a tax form or credit-card application. The fields in a form can be arranged in any appropriate way; nevertheless, the application regards the fields as in a definite linear order.  
Each of these three ways of presenting information retains its integrity, regardless of the context in which it appears. For example, a field in an array can contain text. When the user is manipulating the field as a whole, the field is treated as part of the array. When users want to change the contents of the field, they edit the field in the same way as they would any other text.  
This section discusses first the general methods of selecting and then the specific methods that apply to text applications, graphics applications, and arrays. Figure 8 compares some of the general methods.  
![](images/_page_40_Figure_6.jpeg)  
Figure 8. Selection Methods  
#### Selection in General  
This section covers the topic of selection without regard to the kind of data involved: selection by clicking, range selection, extending a selection, and discontinuous selection. In all cases, inverse video indicates what has been selected.  
#### Selection by Clicking  
The most straightforward method of selecting an object is by clicking on it once. Most things that can be selected are selected this way. The result of double clicking depends on the context: double clicking on an application icon selects it and opens it, a shortcut for selecting then choosing open from the File menu.  
#### Range Selection  
The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:  
- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continually highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. (If possible, the view should scroll to allow extending the selection beyond one windowful.)
- 3. When the feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the active end of the range.  
#### Extending a Selection  
A user can change the extent of an existing selection by holding down the Shift key and clicking the mouse button (Shift-Click). Exactly what happens next depends on the context.  
In text or an array, the result of a Shift-click is always a range. The position where the button is clicked becomes the new endpoint or anchor point of the range; the selection can be extended in any direction. If the user shift-clicks within the current range, the new range will be smaller than the old range.  
Extended selections can be made across the panes of a split window. (See "Splitting Windows.")  
#### Making a Discontinuous Selection  
In graphics applications, objects aren't usually considered to be in any particular sequence. A selection is extended by adding objects to it, and the added objects do not have to be adjacent to the objects already selected. The user can add either an individual object or a range of objects to the selection by holding down the Shift key before making the additional  
selection (Shift-click). When this happens, the objects between the current selection and the new object are not automatically included in the selection. This kind of selection is called a **discontinuous selection**. If the user holds down the Shift key and selects one or more objects that are already highlighted, the objects are deselected.  
In the case of graphics, *all* selections are discontinuous selections because graphic objects are discrete. This is not the case with arrays and text, however. In these two kinds of applications, an extended selection made by a Shift-click always includes everything between the old selection and the new endpoint. To provide for discontinuous selection in these applications, Apple-click is included in the human interface.  
To make a discontinuous selection in a text or array application, the user selects the first piece in the usual way and holds down the Apple key before selecting the remaining pieces. Each piece is selected in the same way as if it were the whole selection, but because the Apple key is held down, the new pieces are added to the existing selection instead of replacing it. If one of the pieces selected with Apple-click is already within an existing part of the selection, then instead of being added to the selection it's removed from the selection. Figure 9 shows a sequence in which several pieces are selected and deselected.  
![](images/_page_42_Figure_4.jpeg)  
Figure 9. Discontinuous Selection Within an Array  
Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the  
user to choose a font after making a discontinuous selection, but wouldn't allow the user to type replacement characters (which part of the selection would they replace?).