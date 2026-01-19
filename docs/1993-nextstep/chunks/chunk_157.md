<!-- Chunk 157 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 402 -->
The Application Kit has support for two kinds of button-list combinations: pop-up lists and pull-down lists. A pop-up or pull-down list is a window that comes to the screen when the user presses a button. The user can drag through the list to choose an option or action. The list stays on-screen only as long as the user keeps the mouse button down. Although pop-up lists and pull-down lists look similar, they have very different roles in the user interface.  
#### **Pop-Up Lists**  
Pop-up lists are used in lieu of a series of radio buttons. They save screen space and prevent overcrowding in panels. Each list is controlled by a button that can be recognized by a special symbollQ, as shown below. The label on the button that precedes the symbol indicates the .current selection from the list. When the user makes a new selection, the button label changes.  
![](images/_page_148_Picture_6.jpeg)  
Pressing the button pops the list up so that the item matching the button label appears on top of the button. The list remains up only while the user holds the mouse button down. When the user releases the mouse button after dragging to a different item in the list, the label on the button changes to that item.  
#### **Pull-Down Lists**  
Pull-down lists are similar to pop-up lists, but they're used to perform actions, rather than to set a state. In this respect, pull-down lists are somewhat like menus.  
Visually, pull-down lists differ from pop-up lists in that the controlling button's label never changes, and it's marked by a different symbol  $\nabla$ .  
![](images/_page_149_Picture_3.jpeg)