<!-- Chunk 128 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 842 -->
A user can extend a selection by holding down the Shift key and clicking the mouse button. This action is called **Shift-clicking.**  
In text, if the user Shift-clicks within an already selected range, the new range is smaller than the old range.  
In an array, a Shift-click can extend the selected range or it can move the selection from the current cell to wherever the user Shift-clicks.  
<span id="page-101-1"></span>There are two models for extending a continuous selection using Shift-click. In the **addition model,** new text is added to a current selection. In the **fixed-point model,** the user can extend the selection on either side of the insertion point. Figure 7-6 illustrates the results of consecutive steps in both models.  
**Figure 7-6** Shift-clicking in the addition model and the fixed-point model  
| Step                                                                                           | Addition model | Fixed-point model |
|------------------------------------------------------------------------------------------------|----------------|-------------------|
| 1. User sets insertion point<br>by clicking before the<br>word "attention".                    |                |                   |
| 2. User extends the selection<br>to the right by Shift-clicking<br>after the word "behind".    |                |                   |
| 3. User extends the selection<br>to the left by Shift-clicking<br>before the word "Pay".       |                |                   |
| 4. User extends the selection<br>to the right by Shift-clicking<br>at the end of the sentence. |                |                   |  
<span id="page-101-3"></span><span id="page-101-2"></span>When considering which model to use in your application, keep in mind that the addition model provides more flexibility by allowing users to extend a selection in *both* directions.  
A Shift-clickshould result in a **continuous selection**—the selection is extended to include everything between the old anchor point and the new active end. A Command-click should result in a discontinuous selection. With **discontinuous selection,** in which the user can extend a selection by adding nonadjacent objects to already selected objects, the objects *between* the current selection and the new object are *not* included in the selection.  
<span id="page-102-1"></span>**Figure 7-7** Discontinuous selection  
![](images/_page_102_Picture_3.jpeg)  
In arrays and text inwhich a Shift-clickextends a continuous selection, the user can make discontinuous selections by holding down the Command keyand clicking. Each Command-clickadds the newobject to the existingselection. If one of the objects selectedwith Command-clickis alreadywithin an existing part of the selection, then it is removed from the selection instead of being added.  
<span id="page-102-2"></span>**Figure 7-8** Discontinuous selection within an array  
![](images/_page_102_Figure_6.jpeg)  
<span id="page-102-0"></span>Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after makinga discontinuous selection, but not allowthe userto type replacement characters, because it wouldn't be obvious which part of the selection the characters would replace.