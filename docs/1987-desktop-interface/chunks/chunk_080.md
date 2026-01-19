<!-- Chunk 80 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 2474 -->
Traditional character-oriented command-line interfaces rely on a cursor to indicate the place on the display where the next character that is typed will appear. The user uses arrow keys (sometimes called "cursor keys") to move the cursor around the screen. Because there is nothing else to "point" at, no pointer is needed.  
In the Desktop Interface, on the other hand, there may be many graphic objects on the screen, unrelated to the text insertion point, to point at. The screen pointer is logically attached to the mouse or other pointing device; the user manipulates it to <sup>I</sup> show the application what to do next, and where to do it. What Apple calls an [insertion point shows where the next characters to be typed will appear. In text, the [pointer shows where the insertion point will be moved to if the mouse button is Ipressed.  
Each pointer has <sup>a</sup> hot spot—the portion of the pointer that must be positioned over <sup>a</sup> screen object before mouse clicks can have an effect on that object. The hot spot should be intuitive, such as the tip of an arrow pointer or the center point of <sup>a</sup> crosshair pointer. Mouse clicks have an effect only when the pointer's hot spot is positioned over the target object's hot zone.  
As the pointer moves about the screen, it may change shape. For example, in <sup>a</sup> text oriented program the pointer takes the I-beam shape while it's within the text, to show where the insertion point will move to if the mouse button is pressed. When the pointer moves outside the text, it becomes an arrow. Don't confuse the user by changing the pointer's shape without <sup>a</sup> reason. You might want to have the pointer change shape to give feedback on the range of activities that make sense either in <sup>a</sup> particular area of the screen or in a current mode. Sometimes, the result of mouse actions depends on the item under the pointer when the mouse button is pressed. Where an application uses modes for different functions, the pointer can be a different shape in each mode. For example, in MacPaint, the pointer shape always reflects the currently selected tool.  
Table 3-1 shows some examples of pointers and their effects. You can create additional pointers as needed for other contexts.  
Table 3-1 Pointers  
| Pointer | Name                  | Used<br>for                                                                                            |
|---------|-----------------------|--------------------------------------------------------------------------------------------------------|
| 1^      | Arrow                 | menu<br>and<br>bar<br>other<br>box,<br>desktop<br>Scroll<br>controls,<br>size<br>bar,<br>bar,<br>title |
| I       | I-beam                | and<br>Selecting<br>inserting<br>text                                                                  |
| +       | Crosshairs            | Drawing,<br>shrinking,<br>or<br>graphic<br>stretching<br>objects                                       |
| =3>     | Plus<br>sign          | an<br>Selecting<br>in<br>array<br>fields                                                               |
|         | Wristwatch            | Showing<br>lengthy<br>operation<br>progress<br>that<br>a<br>is in                                      |
| ^       | Spinning<br>beachball | Showing<br>system<br>during<br>a lengthy<br>operation<br>the<br>that<br>alive<br>is still              |  
During a particularly lengthy operation, when the user can do nothing but wait until the operation is completed, the pointer may change its shape and become a status or progress indicator. This indicator lets the user know that the system hasn't died—it's just busy. The standard pointer used for this purpose is a wristwatch. Some applications use the "spinning beachball" pointer to show that all is well during longer operations. The kindest applications use a dial to show the passing of time, either in absolute terms or as a proportion of the total, or both. Figure 3-49 is an example.  
#### Percentage Complete:  
![](images/_page_108_Figure_2.jpeg)  
Time remaining: less than a minute.  
Figure 3-49
The progress dial in AppleLink®  
#### Mouse actions  
In general, just *moving* the mouse changes nothing except the location, and possibly the shape, of the pointer. Pressing the mouse button indicates the intention to do something, and releasing the button completes the action. Pressing by itself should have no more effect than clicking has—except in well-defined areas, such as scroll arrows, where it has the same effect as repeated clicking.  
The central mouse function is pointing. Other important mouse actions are clicking, double-clicking, pressing, and dragging.  
#### Clicking  
Clicking has two components: pushing down on the mouse button and then quickly releasing it while the mouse remains stationary. (If the mouse moves between button down and button up, dragging—not just clicking—is what happens.) Some uses of clicking are to select an object, to move an insertion point, and to turn on a control. The effect of clicking should be immediate and evident. If the function of the click is to cause an action (as when clicking on a button), the *selection is made* when the button is pressed, and the *action takes place* when the button is released.  
#### Double-clicking  
Double-clicking involves a second click that follows immediately after the end of <sup>a</sup> first click. If the two clicks are close enough to one another in terms of time (as set by the user in the Control Panel) and of screen location, then they constitute a double click.  
The most common use of double-clicking is as <sup>a</sup> shortcut way to perform an action. For example, clicking twice on an icon is <sup>a</sup> faster way to open it than clicking once to select it, then choosing Open from the File menu; clicking twice on <sup>a</sup> word to select it is faster than dragging through it.Double-clicking can also be used to select a larger object than one that can be selected by a single click.  
Double-clicking is a shortcut for those users physically able to use it. Double-clicking must never be the only way to perform <sup>a</sup> given action. Many novice users, children, and disabled people have a hard time double-clicking.  
Some applications support selection by double-clicking and triple-clicking. As always with multiple clicks, the second click extends the effect of the first click, and the third click extends the effect of the second click. For example, in a text-oriented application, the first click sets an insertion point, the second click selects the whole word containing the insertion point, and the third click might select the whole sentence or paragraph. In a graphics application, the first click might select a single object, and double and triple clicks might select successively larger sets of objects.  
Three clicks is probably the practical limit, and even that is difficult for many people. If an application defines the effect only of single-and double-clicking, a third click should have no effect. If triple-clicking is defined, then the fourth click should have no effect.  
#### Pressing  
Pressing means holding the mouse button down for <sup>a</sup> time while the mouse remains stationary. Pressing on the scroll bar's arrows, for example, causes scrolling until the user releases the mouse button. For certain kinds of objects, pressing on the object has the same effect as clicking it repeatedly. For example, clicking a scroll arrow causes a document to scroll one line; pressing on a scroll arrow causes the document to scroll continuously until the user releases the mouse button or reaches the end of the document.  
#### Dragging  
Dragging means pressing the mouse button, moving the mouse to a new position, and finally releasing the mouse button (Figure 3-50). Dragging can have different effects, depending on what's under the pointer when the mouse button is pressed. The uses of dragging include selecting blocks of text, choosing a menu item, selecting a range of objects, moving an icon or other object from one place to another, and shrinking or expanding an object.  
Graphic objects can be moved by dragging. The application either moves the entire object, or attaches a dotted outline of the object to the pointer and moves the outline as the user moves the pointer. When the user releases the mouse button, the application redraws the complete object at the new location.  
1. Pointer over icon to be dragged  
2. Click to select  
3. Drag outline to right  
4. Release button  
System folder  
System folder  
System folder  
System folder  
System folder  
System folder  
System folder  
System folder  
System folder  
System folder  
System folder  
System folder  
Figure 3-50
Dragging with the mouse  
An object being moved can be restricted to certain boundaries, such as the edges of a window. If the user moves the pointer outside the boundaries, the application stops drawing the dotted outline of the object. If the user releases the mouse button while the pointer is outside the boundaries, the object doesn't move. If, on the other hand, the user moves the pointer back within the boundaries before releasing the mouse button, the outline is redrawn in the new location. Moving an object beyond the boundary of the window can also cause the window to scroll (autoscroll) or even move the object from one window into another.  
#### Mouse-ahead  
Mouse-ahead (analogous to the keyboard's type-ahead) saves, in a memory buffer, any mouse actions the user performs when the application isn't ready to process them. If appropriate, the application can then carry out these stored processes when it has time. Alternatively, the application can choose to ignore saved-up mouse actions, but should do so only to protect the user from possibly damaging consequences.