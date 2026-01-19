<!-- Chunk 11 | Source: 1983 Lisa UI Guidelines.pdf | Est. Tokens: 275 -->
The graphics style is used for information that is conveyed through pictures rather than words. In some products, such as LisaDraw, the user draws pictures using the mouse; in others, such as the Desktop Manager, the user manipulates pictures drawn by the application. A graphics application can be thought of as a collection of objects that are either separate or arranged in groups. A separate object can be operated on without affecting any of the other objects.  
A graphics object is either a geometrical shape (as in LisaDraw) or a bit map (as in the Desktop Menager).  
Figure 1-3 snows a window containing a typical graphics document (from LisaDraw).  
![](images/_page_6_Picture_8.jpeg)  
Floure 1-3. LisaDraw Document  
Details: A geometrically defined object can be scaled more smoothly than a bit map, but a bit map object can show finer detail.  
Implementation: In the Toolkit, geometrically defined objects are supported by the Structured Graphics building block, and bit map graphics are supported by the Bit map graphics building block. Quickdraw is also available for custom graphics.