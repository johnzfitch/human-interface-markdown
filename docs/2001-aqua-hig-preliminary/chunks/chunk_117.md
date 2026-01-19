<!-- Chunk 117 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 1114 -->
<span id="page-142-1"></span>This section describes various selection techniques.  
**Figure 8-4** Selection techniques  
![](images/_page_142_Picture_9.jpeg)  
Selecting **143**  
#### <span id="page-143-0"></span>Selection by Clicking  
The most straightforward method of selecting an object is by clicking it once. Icons, for example, are selected in this way.  
#### <span id="page-143-1"></span>Selection by Dragging  
The user can select a range of some objects by following this procedure:  
- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the mouse button, the user moves the pointer in any direction.
- As the pointer moves, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continuously highlighted. For graphics, a dotted rectangle expands or contracts to show the selected area. If appropriate, the view should scroll to allow extending the selection beyond a window.
- 3. When the desired range is selected, the user releases the mouse button. The point at which the button is released is called the **active end** of the range.  
#### <span id="page-143-2"></span>Changing a Selection With Shift-Click  
A user can extend a selection by holding down the Shift key and clicking the mouse button. This action is called **Shift-clicking.**  
In text, a Shift-click typically results in a **continuous selection**—the selection is extended to include everything between the old anchor point and the new active end. Graphics applications typically support **discontinuous selection,** in which the user can extend a selection by adding non-adjacent objects to already selected objects, and the objects *between* the current selection and the new object are *not* included in the selection.  
In text, if the user Shift-clicks within an already selected range, the new range is smaller than the old range.  
In an array, a Shift-click can extend the selected range or it can move the selection from the current cell to wherever the user Shift-clicks.  
There are two models for extending a continuous selection using Shift-click. In the **addition** model, new text is added to a current selection. In the **fixed-point** model, the user can extend the selection on either side of the insertion point. [Figure 8-5](#page-144-2) illustrates the results of three consecutive steps in both models.  
<span id="page-144-2"></span><span id="page-144-1"></span>**Figure 8-5** Shift-clicking in the addition model and the fixed-point model  
|                         | Addition<br>Model           | Fixed-point<br>Model        |
|-------------------------|-----------------------------|-----------------------------|
| Setting insertion point | This is some<br>sample text | This is some<br>sample text |
| Extending selection     | This is some                | This is some                |
| to the right.           | sample text                 | sample text                 |
| Extending selection     | This is some                | This is some                |
| to the left.            | sample text                 | sample text                 |  
When considering which model to use in your application, keep in mind that the addition model provides more flexibility by allowing users to extend a selection in *both* directions.  
#### <span id="page-144-0"></span>Changing a Selection With Command-Click  
In arrays and text in which Shift-click extends a continuous selection, the user can make discontinuous selections by holding down the Command key and clicking. Each Command-click adds the new object to the existing selection. If one of the objects selected with Command-click is already within an existing part of the selection, then it is removed from the selection instead of being added.  
Selecting **145**  
<span id="page-145-1"></span>**Figure 8-6** Discontinuous selection within an array  
![](images/_page_145_Figure_3.jpeg)  
Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after making a discontinuous selection, but not allow the user to type replacement characters, because it wouldn't be obvious which part of the selection the characters would replace.