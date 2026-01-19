<!-- Chunk 107 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 1224 -->
<span id="page-110-2"></span>This section describes selection techniques.  
#### Selection by Clicking  
The most straightforward method of selecting an object is by clicking it once. Icons, for example, are selected in this way in the Finder.  
Selecting **111 2008-01-15 | © 1992, 2001-2003, 2008 Apple Inc. All Rights Reserved.**  
<span id="page-111-0"></span>**Figure 8-4** Selection of a single item  
![](images/_page_111_Picture_3.jpeg)  
#### <span id="page-111-2"></span>Selection by Dragging  
The user can select a range of some objects by following this procedure:  
- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the mouse button, the user moves the pointer in any direction.  
As the pointer moves, visual feedback indicates the objects that would be selected if the mouse button is released.Fortext and arrays, the selected area is continuously highlighted.Forgraphics, a dotted rectangle expands or contracts to show the selected area. If appropriate, the view should scroll to allow extending the selection beyond a window.  
<span id="page-111-3"></span><span id="page-111-1"></span>3. When the desired range is selected, the user releases the mouse button. The point at which the button is released is called the **active end** of the range.  
**Figure 8-5** Selection of a range  
![](images/_page_111_Picture_11.jpeg)  
#### <span id="page-111-4"></span>Changing a Selection  
A user can extend a selection by holding down the Shift key and clicking the mouse button. This action is called **Shift-clicking.**  
In text, if the user Shift-clicks within an already selected range, the new range is smaller than the old range.  
In an array, a Shift-click can extend the selected range or it can move the selection from the current cell to wherever the user Shift-clicks.  
There are two models for extending a continuous selection using Shift-click. In the **addition model,** new text is added to a current selection. In the **fixed-point model,** the user can extend the selection on either side of the insertion point. Figure 8-6 illustrates the results of consecutive steps in both models.  
<span id="page-112-0"></span>**Figure 8-6** Shift-clicking in the addition model and the fixed-point model  
| Step                                                                                           | Addition model | Fixed-point model |
|------------------------------------------------------------------------------------------------|----------------|-------------------|
| 1. User sets insertion point<br>by clicking before the<br>word "attention".                    |                |                   |
| 2. User extends the selection<br>to the right by Shift-clicking<br>after the word "behind".    |                |                   |
| 3. User extends the selection<br>to the left by Shift-clicking<br>before the word "Pay".       |                |                   |
| 4. User extends the selection<br>to the right by Shift-clicking<br>at the end of the sentence. |                |                   |  
<span id="page-112-2"></span>When considering which model to use in your application, keep in mind that the addition model provides more flexibility by allowing users to extend a selection in *both* directions.  
<span id="page-112-3"></span><span id="page-112-1"></span>A Shift-clickshould result in a **continuous selection**—the selection is extended to include everything between the old anchor point and the new active end. A Command-click should result in a discontinuous selection. With **discontinuous selection,** in which the user can extend a selection by adding nonadjacent objects to already selected objects, the objects *between* the current selection and the new object are *not* included in the selection.  
**Figure 8-7** Discontinuous selection  
![](images/_page_112_Picture_7.jpeg)  
In arrays and text inwhich a Shift-clickextends a continuous selection, the user can make discontinuous selections by holding down the Command keyand clicking. Each Command-clickadds the newobject to the existingselection. If one of the objects selectedwith Command-clickis alreadywithin an existing part of the selection, then it is removed from the selection instead of being added.  
<span id="page-113-1"></span>**Figure 8-8** Discontinuous selection within an array  
![](images/_page_113_Figure_3.jpeg)  
<span id="page-113-0"></span>Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after makinga discontinuous selection, but not allowthe userto type replacement characters, because it wouldn't be obvious which part of the selection the characters would replace.