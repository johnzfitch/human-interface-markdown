<!-- Chunk 99 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 1899 -->
When <sup>a</sup> block of text is selected, either with <sup>a</sup> pointing device or with cursor keys, pressing either Left Arrow or Right Arrow deselects the range. If Left Arrow ispressed, the insertion point goes to the beginning of what had been the selection. If Right Arrow is pressed, the insertion point goes to the end of what had been the selection.  
#### Selections in graphics  
In existing applications, there are several different ways to select graphic objects and to show selection feedback. This section shows how MacDraw and MacPaint do it, but other situations may require other solutions.  
A MacDraw document is <sup>a</sup> collection of individual graphic objects. To select one of these objects, the user clicks once on the object, which is then bracketed with "handles." (The handles are used to stretch or shrink the object.) Figures 3-59 and 3-60 show examples of selection in MacDraw and MacPaint.  
![](images/_page_128_Picture_3.jpeg)  
Figure 3-59 Graphic selection In MacDraw  
In MacDraw, there are two ways to select more than one object. A range selection includes every object completely contained within the dotted rectangle that encloses the range as the user drags the mouse. A discontinuous selection includes only those objects explicitly selected.  
<sup>A</sup> MacPaint document, on the other hand, is <sup>a</sup> series of pixels—not discrete objects. Selections are shown surrounded by <sup>a</sup> moving dashed line (sometimes called a marquee or "marching ants").  
![](images/_page_128_Picture_7.jpeg)  
Figure 3-60 Graphic selection in MacPaint  
#### Selections in arrays and tables  
An array is <sup>a</sup> one- or two-dimensional arrangement of fields. The user can select one or more fields, or part of the contents of a field.  
To select <sup>a</sup> single field, the user clicks in the field (Figure 3-61). The user can also select a field by moving into it with the Tab or Return key.  
Click here to select Hawaii field State Capital Alaska Juneau Arizona Phoenix California Sacramento Colorado Denver Hawaii 1^ Honolulu Idaho Boise Montana Helena Nevada Carson City New Mexico Santa Fe Oregon Salem Utah Salt Lake City Washington Olympia Wyoming Cheyenne  
| State         | Capital              |
|---------------|----------------------|
| Alaska        | Juneau               |
| Arizona       | Phoenix              |
| California    | Sacramento           |
| Colorado      | Denver               |
|               | ^ <br>Honolulu       |
| Idaho         | Boise                |
| Montana       | Helena               |
| Nevada        | Carson<br>City       |
| New<br>Mexico | Santa<br>Fe          |
| Oregon        | Salem                |
| Utah          | Lake<br>Salt<br>City |
| Washington    | Olympia              |
| Wyoming       | Cheyenne             |  
Figure 3-61 Field selection In an array  
To select part of the contents of a field, the user must first select the field. The user then clicks again to select the desired part of the field. Because the contents of a field are either text or graphics, this type of selection follows the rules outlined above.  
A table can also support selection of rows and columns. The most convenient way for the user to select a column is to click in the column header. To select more than one column, the user drags through several column headers. The same applies to rows.  
Figures 3-62, 3-63, and 3-64 show column, range, and discontinuous selections in arrays.  
Pressing the Tab key cycles the insertion point through the fields in an order determined by the application. From each field, the Tab key selects the "next" field. Typically, the sequence of fields is first from left to right, and then from top to bottom. When the last field in <sup>a</sup> form is selected, pressing the Tab key selects the first field in the form. If there's <sup>a</sup> good reason, an application may guide the user through the fields in some order other than the order in which the fields appear on the screen.  
The Return key selects the first field in the next row. If the idea of rows doesn't make sense in a particular context, then the Return key should have the same effect as the Tab key.  
| Click here to select the column— | State      | Capital        |
|----------------------------------|------------|----------------|
|                                  | Alaska     | Juneau         |
|                                  | Arizona    | Phoenix        |
|                                  | California | Sacramento     |
|                                  | Colorado   | Denver         |
|                                  | Hawaii     | Honolulu       |
|                                  | Idaho      | Boise          |
|                                  | Montana    | Helena         |
|                                  | Nevada     | Carson City    |
|                                  | New Mexico | Santa Fe       |
|                                  | Oregon     | Salem          |
|                                  | Utah       | Salt Lake City |
|                                  | Washington | Olympia        |
|                                  | Wyoming    | Cheyenne       |  
| State        | Capital        |
|--------------|----------------|
| Alasi a      | Juneau         |
| Arizona      | Phoenix        |
| California   | Sacramento     |
| Colorado     | Denver         |
| Hawati       | Honolulu       |
| ldaho        | Boise          |
| l fontana    | Helena         |
| Nevada       | Carson City    |
| New I textoo | Santa Fe       |
| Oregon       | Salem          |
| Utah         | Salt Lake City |
| Washington   | Olympia        |
| 'w'yoming    | Cheyenne       |  
Figure 3-62 Column selection in an array  
|                                               | State      | Capital        |
|-----------------------------------------------|------------|----------------|
|                                               | Alaska     | Juneau         |
|                                               | Arizona    | Phoenix        |
|                                               | California | Sacramento     |
|                                               | Colorado   | Denver         |
|                                               | Hawaii     | Honolulu       |
|                                               | Idaho      | Boise          |
|                                               | Prontana   | Helena         |
| Drag through this area —————to select a range | Nevada     | Carson City    |
|                                               | New Mexico | Santa Fe       |
|                                               | Oregon     | Salem          |
|                                               | Utah       | Salt Lake City |
|                                               | Washington | Olympia        |
|                                               | Wyoming    | Cheyenne       |  
| State      | Capital        |
|------------|----------------|
| Alaska     | Juneau         |
| Arizona    | Phoenix        |
| California | Sacramento     |
| Colorado   | Denver         |
| Hawaii     | Honolulu       |
| Idaho      | Boise          |
| l'Iontana  | Helena         |
| Nevada     | Carson City    |
| New Mexico | Santa Fe       |
| Oregon     | Salem          |
| Utah       | Salt Lake City |
| Washington | Olympia        |
|            |                |  
Figure 3-63
Range selection in an array  
![](images/_page_130_Figure_6.jpeg)  
Figure 3-64
Discontinuous selection in an array