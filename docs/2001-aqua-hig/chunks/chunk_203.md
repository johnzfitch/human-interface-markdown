<!-- Chunk 203 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 524 -->
A user can extend a selection by holding down the Shift key and clicking the mouse button. This action is called **Shift-clicking.**  
In text, a Shift-click typically results in a **continuous selection**—the selection is extended to include everything between the old anchor point and the new active end. Graphics applications typically support **discontinuous selection,** in which the user can extend a selection by adding nonadjacent objects to already selected objects, and the objects *between* the current selection and the new object are *not* included in the selection.  
In text, if the user Shift-clicks within an already selected range, the new range is smaller than the old range.  
In an array, a Shift-click can extend the selected range or it can move the selection from the current cell to wherever the user Shift-clicks.  
There are two models for extending a continuous selection using Shift-click. In the **addition model,** new text is added to a current selection. In the **fixed-point model,** the user can extend the selection on either side of the insertion point. Figure 9-5 illustrates the results of three consecutive steps in both models.  
<span id="page-178-1"></span>**Figure 9-5** Shift-clicking in the addition model and the fixed-point model  
|                         | Addition<br>model           | Fixed-point<br>model        |
|-------------------------|-----------------------------|-----------------------------|
| Setting insertion point | This is some<br>sample text | This is some<br>sample text |
| Extending selection     | This is some                | This is some                |
| to the right.           | sample text                 | sample text                 |
| Extending selection     | This is some                | This is some                |
| to the left.            | sample text                 | sample text                 |  
Selecting **179**  
When considering which model to use in your application, keep in mind that the addition model provides more flexibility by allowing users to extend a selection in *both* directions.