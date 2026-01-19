<!-- Chunk 39 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 844 -->
A user can extend a selection by holding down the Shift key and clicking the mouse button. This action is called **Shift-clicking.**  
In text, if the user Shift-clicks within an already selected range, the new range is smaller than the old range.  
In an array, a Shift-click can extend the selected range or it can move the selection from the current cell to wherever the user Shift-clicks.  
There are two models for extending a continuous selection using Shift-click. In the **addition model,** new text is added to a current selection. In the **fixed-point model,** the user can extend the selection on either side of the insertion point. Figure 2-6 illustrates the results of consecutive steps in both models.  
<span id="page-34-0"></span>**Figure 2-6** Shift-clicking in the addition model and the fixed-point model  
| S ep                                                                                              | Add<br>on mode | F xed po n mode |
|---------------------------------------------------------------------------------------------------|----------------|-----------------|
| U e<br>e<br>e<br>o<br>po<br>b<br>g be o e<br>e<br>wo d a e<br>o                                   |                |                 |
| 2 U e e<br>e d<br>e<br>e e<br>o<br>o<br>e<br>g<br>b<br>S<br>g<br>a e<br>e wo d be<br>d            |                |                 |
| 3 U e e<br>e d<br>e<br>e e<br>o<br>o<br>e e<br>b<br>S<br>g<br>be o e<br>e wo d Pa                 |                |                 |
| 4 U e e<br>e d<br>e<br>e e<br>o<br>o<br>e<br>g<br>b<br>S<br>g<br>a<br>e e d o<br>e<br>e<br>e<br>e |                |                 |  
<span id="page-34-3"></span><span id="page-34-2"></span>When considering which model to use in your application, keep in mind that the addition model provides more flexibility by allowing users to extend a selection in *both* directions.  
<span id="page-34-1"></span>A Shift-click should result in a **continuous selection**—the selection is extended to include everything between the old anchor point and the new active end. A Command-click should result in a discontinuous selection. With **discontinuous selection,** in which the user can extend a selection by adding nonadjacent objects to already selected objects, the objects *between* the current selection and the new object are *not* included in the selection.  
**Figure 2-7** Discontinuous selection  
![](images/_page_34_Picture_8.jpeg)  
In arrays and text in which Shift-click extends a continuous selection, the user can make discontinuous selections by holding down the Command key and clicking. Each Command-click adds the new object to the existing selection. If one of the objects selected with Command-click is already within an existing part of the selection, then it is removed from the selection instead of being added.  
<span id="page-35-1"></span>**Figure 2-8** Discontinuous selection within an array  
![](images/_page_35_Figure_3.jpeg)  
<span id="page-35-0"></span>Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after making a discontinuous selection, but not allow the user to type replacement characters, because it wouldn't be obvious which part of the selection the characters would replace.