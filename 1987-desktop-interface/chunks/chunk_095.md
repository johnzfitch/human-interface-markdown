<!-- Chunk 95 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 751 -->
This section covers the topic of selection without regard to the kind of data involved: selection by clicking, range selection, extending a selection, and discontinuous selection. In <sup>a</sup> monochrome environment, inverse video indicates what has been selected. Figure 3-53 compares some of the general methods.  
IS BID D E IE M D E Clicking on B selects B Range selection of A through C selects A. B, and C Discontinuous selection (range selection of A. B. and C Is extended to Include E) m m d m  
Figure 3-53 Selection methods  
#### Selection by clicking  
The most straightforward method of selecting an object is by clicking on it once. Icons, insertion points, and most other things that can be selected are selected this way.  
#### Range selection  
The user selects a range of objects by dragging through them. Although the exact meaning of the selection depends on the type of application, the procedure is always the same:  
- 1 The user positions the pointer at one corner of the range and presses the mouse button. This position is called the anchor point of the range.
- 2 Without releasing the button, the user moves the pointer in any direction. As the pointer is moved, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continuously highlighted. For graphics, a dotted rectangle expands or contracts to show the range that will be selected. (If possible, the view should scroll to allow extending the selection beyond one windowful.)
- 3 When the feedback shows the desired range, the user releases the mouse button. The point at which the button is released is called the active end of the range.  
#### Extending a selection  
A user can change the extent of an existing selection by holding down the Shift key and clicking the mouse button (Shift-click). Exactly what happens next depends on the context.  
In text or an array, the result of a Shift-click is always the selection of a range (Figure 3-54). The position where the button is clicked becomes the new endpoint of the range. If the user Shift-clicks within the current range, the new range will be smaller than the old range.  
Extended selections can be made even across the panes of <sup>a</sup> split window.  
| The<br>selection                   | ro.««M^aifl <agi«.tb«ihiba<br>IJ'iiJlJ.tlAl.kl a</agi«.tb«ihiba<br>  |
|------------------------------------|----------------------------------------------------------------------|
| here<br>Shift-click<br>1.          | (Shaw)<br>if there<br>timelenough.<br>later<br>is                    |
| expands<br>The<br>selection<br>2.  | Everything<br>happ<br>if there<br>(Shaw)<br>later<br>is              |
| here<br>Shift-click<br>3.          | (Shaw)<br>enough.                                                    |
| The<br>selection<br>shrinks<br>14. | na<br>33<br>jBiEisa<br>time<br>(Shaw)<br>there<br>enough.<br>is<br>f |  
[Figure 3-54 Expanding and shrinking a text selection