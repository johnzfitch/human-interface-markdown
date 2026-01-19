<!-- Chunk 215 | Source: 1992 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 1291 -->
![](images/_page_309_Picture_7.jpeg)  
Before performing an operation on an object, the user must select it, usually by clicking it, to distinguish it from other objects. Selecting the object to be operated on before identifying the operation itself is a fundamental characteristic of the Macintosh human interface. The pattern is usually something like this:  
- 1. The user selects an object (a noun, a thing to be operated on).
- 2. The user chooses an operation (a verb, the thing to be done).  
This is often called the "noun-verb paradigm."  
There is always a visual clue to show that something has been selected. For example, text and icons in a black-and-white environment usually appear in inverse video when selected. In color environments, icons appear darker and text is highlighted with the color the user set in the Color control panel. In some situations, other forms of highlighting may be more appropriate. The important thing is that there should always be immediate feedback, so the user knows that the click had an effect.  
![](images/_page_309_Picture_13.jpeg)  
Selecting an object never alters the object itself. Making a selection shouldn't commit the user to anything; there should never be a penalty for making an incorrect selection. The user can undo any selection by making any other selection or clicking outside the selection.  
How something is selected depends on what it is. Although there are many ways to select objects, the selection methods fall into easily recognizable groups. Users get used to selecting objects in certain ways, and applications that use these methods are easier to learn. Some of these methods apply to every type of application, and some to only particular types of applications.  
It's useful to distinguish among three types of objects—text, lists or arrays, and graphics—because the user deals with each of them in a different way when selecting them. Figure 10-14 shows an example of each.  
**Figure 10-14** Three ways of selecting information  
![](images/_page_310_Figure_4.jpeg)  
| Sales results     |              |              |              |    |          |
|-------------------|--------------|--------------|--------------|----|----------|
| Flavor            | 1st Qtr      | 2nd Qtr      | 3rd Qtr      |    | 企        |
| Vanilla           | \$37,000.00  |              | \$33,250.00  |    |          |
| Chocolate         | 40,000.00    |              | 41,000.00    | Г  |          |
| Strawberry        | 15,000.00    |              | 12,950.00    | Г  |          |
| Pistachio         | 21,000.00    |              | 20,100.00    | Г  |          |
| Rainbow Sherbet   | 19,000.00    |              | 19,750.00    | Г  |          |
| Orange Sherbet    | 35,750.00    | 36,000.00    | 39,000.00    |    |          |
| Total             | \$258,250.00 | \$254,890.00 | \$251,360.00 |    | л,       |
| 4.1               |              |              |              |    | $\simeq$ |
| <b>\( \rangle</b> |              |              |              | \$ | 9        |  
![](images/_page_310_Picture_8.jpeg)  
Each of these three ways of presenting information retains its integrity regardless of the context in which it appears. For example, a field in an array can contain text. When the user is manipulating the field as a whole, the field is treated as part of the array. When the user wants to change the contents of the field, he or she edits the field in the same way as any other text.  
Text can be arranged on the screen in a variety of ways. Some applications, such as word processors, might consist of nothing but text, whereas others, such as graphics-oriented applications, might use text almost incidentally.  
Selecting **287**  
It's useful to consider all the text appearing together in a particular context as a block of text. The size of the block can range from a single field, as in a dialog box, to the whole document, as in a word processor. Regardless of its size or arrangement, the application sees each block as a one-dimensional string of characters. Text is edited the same way regardless of where it appears.  
**Arrays** are tabular arrangements of **fields.** One-dimensional arrays are called *lists*, and two-dimensional arrays are called *forms* or *tables*. Each field contains a collection of information, usually text and possibly graphics. A table can be easily identified on the screen as it consists of rows and columns of fields (sometimes called *cells*) separated by horizontal and vertical lines. (Tables are often implemented in spreadsheet applications.) A form is something the user fills out, such as a tax form or credit-card application. Although the fields in a form can be arranged in any appropriate way, your application always considers these fields as being in a well-defined linear order.  
**Graphics** are pictures, drawn either by the user or by the application. Graphics in a document tend to consist of discrete objects, each of which can be selected individually.  
The sections that follow discuss the general methods of selecting and the specific methods that apply to text applications, graphics applications, and arrays.