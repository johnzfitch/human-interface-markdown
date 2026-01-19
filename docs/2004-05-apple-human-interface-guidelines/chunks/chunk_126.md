<!-- Chunk 126 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 306 -->
Inspectors are utility windows that allow users to view the attributes of a selection. They also often provide ways to modify these attributes. Xcode, Keynote, and the Finder all make use of inspectors. Inspectors should update dynamically based on the current selection.  
An Info window functions like an inspector except that it does not update dynamically as selections change. It shows attributes of the item that was selected when the window was opened, even after the focus has been changed to another item.  
<span id="page-129-2"></span>It may be useful to provide both inspectors and Info windows in your application because in some cases it's more useful to have one window where context changes when another item is selected (inspector) and in other cases it's more useful to be able to see the attributes of more than one item at a time (Info window). Multiple inspector windows and Info windows can be open at the same time.  
Figure 8-27 and Figure 8-28 show examples of an inspector and an Info window.  
<span id="page-130-1"></span>**Figure 8-27** An inspector window  
![](images/_page_130_Picture_3.jpeg)  
**Figure 8-28** An Info window  
<span id="page-130-2"></span>![](images/_page_130_Picture_5.jpeg)