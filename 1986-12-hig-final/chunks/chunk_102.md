<!-- Chunk 102 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 1538 -->
In existing applications, there are several different ways to select graphic objects and to show selection feedback. This section shows how MacDraw and MacPaint do it, but other situations may require other solutions.  
A MacDraw document is a collection of individual graphic objects. To select one of these objects, the user clicks once on the object, which is then bracketed with "handles." (The handles are used to stretch or shrink the object.) Figure 59 and 60 show examples of selection in MacDraw and MacPaint.  
![](images/_page_127_Picture_0.jpeg)  
Figure 59
Graphics selections in MacDraw  
In MacDraw, there are two ways to select more than one object. A range selection includes every object completely contained within the dotted rectangle that encloses the range as the user drags the mouse. A discontinuous selection includes only those objects explicitly selected.  
A MacPaint document, on the other hand, is a series of pixels—not discrete objects. Selections are shown surrounded by a moving dashed line (sometimes called a marquee or "marching ants").  
![](images/_page_127_Picture_4.jpeg)  
Figure 60 Graphics selection in MacPaint  
#### Selections in arrays and tables  
An array is a one- or two-dimensional arrangement of fields. The user can select one or more fields, or part of the contents of a field.  
To select a single field, the user clicks in the field (Figure 61). The user can also select a field by moving into it with the Tab or Return key.  
Click here to select Hawaii field.  
| state      | capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenix        |
| California | Sacramento     |
| Colorado   | Denver         |
| Hawaii 🗼   | Honolulu       |
| Idaho      | Boise          |
| Montana    | Helena         |
| Nevada     | Carson City    |
| New Mexico | Santa Fe       |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
| Yyoming    | Cheyenne       |  
| state      | capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenix        |
| California | Sacramento     |
| Colorado   | Denver         |
| Hawaii     | Honolulu       |
| ldaho      | Boise          |
| Montana    | Helena         |
| Nevada     | Carson City    |
| New Mexico | Santa Fe       |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
| Yyoming    | Cheyenne       |
|            |                |  
Figure 61 Field selection in an array  
To select part of the contents of a field, the user must first select the field. The user then clicks again to select the desired part of the field. Because the contents of a field are either text or graphics, this type of selection follows the rules outlined above.  
A table can also support selection of rows and columns. The most convenient way for the user to select a column is to click in the column header. To select more than one column, the user drags through several column headers. The same applies to rows.  
Figures 62, 63, and 64 show column, range, and discontinuous selections in arrays.  
| Click here       |                |  |
|------------------|----------------|--|
| state            | capital        |  |
| Alaska           | Juneau         |  |
| Arizona          | Phoenix        |  |
| California       | Sacramento     |  |
| Colorado         | Denver         |  |
| Hawaii           | Honolulu       |  |
| ldaho            | Boise          |  |
| Montana          | Helena         |  |
| Nevada           | Carson City    |  |
| New Mexico       | Santa Fe       |  |
| Oregon           | Salem          |  |
| Utah             | Salt Lake City |  |
| Washington       | Olympia        |  |
| Yyoming Cheyenne |                |  |  
to select a column state capital Alaska Juneau AFTZONA Phoenix California Sacramento Colorado Denver Hawaii Honolulu dalio Boise l fontana Helena Nevada Carson City New Herico Santa Fe Oregon Salem litah Salt Lake City Washington Olympia algement Cheyenne  
Figure 62 Column selection in an array  
| state      | capital        |  |
|------------|----------------|--|
| Alaska     | Juneau         |  |
| Arizona    | Phoenix        |  |
| California | Sacramento     |  |
| Colorado   | Denver -       |  |
| Hawaii -   | Honolulu       |  |
| ldaho      | Boise          |  |
| Montana    | Helena         |  |
| Nevada     | Carson City    |  |
| New Mexico | Santa Fe       |  |
| Oregon     | Salem          |  |
| Utah       | Salt Lake City |  |
| Washington | Olympia        |  |
| Yyoming    | Cheyenne       |  |  
| state         |  | capital        |  |
|---------------|--|----------------|--|
| Alaska        |  | Juneau         |  |
| Arizona       |  | Phoenix        |  |
| California    |  | Sacramento     |  |
| Colorado      |  | Denver         |  |
| Hawaii        |  | Honolulu       |  |
| ldaho         |  | Boise          |  |
| l lontana     |  | Helena         |  |
| Herrada       |  | Carson City    |  |
| New I le rico |  | Santa Fe       |  |
| Úregon –      |  | Salem          |  |
| Utah          |  | Salt Lake City |  |
| Washington    |  | Olympia        |  |
| Yyoming       |  | Cheyenne       |  |  
Drag through this area  
and release to make this selection.  
Figure 63
Range selection in an array  
![](images/_page_130_Figure_1.jpeg)  
Figure 64
Discontinuous selection in an array  
Pressing the Tab key cycles the insertion point through the fields in an order determined by the application. From each field, the Tab key selects the "next" field. Typically, the sequence of fields is first from left to right, and then from top to bottom. When the last field in a form is selected, pressing the Tab key selects the first field in the form. If there's a good reason, an application may guide the user through the fields in some order other than the order in which the fields appear on the screen.  
The Return key selects the first field in the next row. If the idea of rows doesn't make sense in a particular context, then the Return key should have the same effect as the Tab key.