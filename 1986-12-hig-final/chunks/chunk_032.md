<!-- Chunk 32 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 1148 -->
The standard pointing device is the one-button mouse. A pointer on the screen follows the motion of the mouse. Other devices—including track balls, joysticks, and styluses—can also perform the functions of a mouse.  
#### Mouse actions  
Simply moving the mouse just moves the pointer. All other events—changes to the information displayed on the screen—take place only when the **mouse button** is used.  
The user can do three things with the mouse button: click, press, and drag. Clicking happens when the user presses down on the mouse button and quickly releases while the mouse remains stationary. Pressing means holding the mouse button down for a time while the mouse remains stationary. Dragging involves pushing down the mouse button, moving the mouse (and the pointer) to a new location, then releasing the mouse button. With these few basic actions, the user can perform a wide range of tasks in a consistent way.  
#### **Pointers**  
Pointers on the screen assume different shapes, according to the context of the application, giving users additional feedback on the nature of their interactions with the computer. The changing pointer is one of the few truly *modal* aspects of the Apple Desktop Interface: a given action may yield quite different results, depending on the shape of the pointer at the time. It is essential that the user can easily distinguish the different modes.  
Three common pointer shapes are the arrow pointer, the I-beam, and the wristwatch.  
The **arrow pointer** is the general pointer for selecting icons, pulling down menus, and choosing menu items.  
To move the insertion point (the blinking vertical bar that shows the user where text can be entered), the user moves the **I-beam pointer** to the new location and clicks the mouse button. For the user, this is less awkward, more natural, and much faster than a cursor-based system. Unlike cursors moved by arrow keys, the insertion point is moved directly to a new location without intermediate states.  
Another pointer shape is the **wristwatch**, which indicates that user input is disabled while some action is ongoing. The shape of the pointer always provides the user with information.  
| Pointer | <u>Name</u><br>Arrow | Used for  Scroll bar and other controls, size box, title bar, menu bar, desktop, and so on |
|---------|----------------------|--------------------------------------------------------------------------------------------|
| I       | l-beam               | Selecting and inserting text                                                               |
| +       | Crosshair            | Drawing and modifying graphic objects                                                      |
| �       | Plus Sign            | Selecting fields in an array                                                               |
|         | Wristwatch           | Showing that a lengthy operation is in progress                                            |  
Figure 9
Pointers  
#### Selecting  
Before performing an operation on an object (or several objects), the user must select it to distinguish it from other objects. This selection is typically done by clicking on an object, or by dragging through a range of objects or a portion of text.  
Selecting the object of an operation before identifying the operation itself is a fundamental characteristic of the Apple human interface. This is sometimes called the "noun-verb" paradigm.  
There is always a visual cue to show that something has been selected. For example, text and icons usually appear in inverse video when selected. The important thing is that there should always be immediate feedback, so that the user knows that the mouse button (click or drag) had an effect.  
Separating the selection and action functions gives the user considerable power and flexibility. The paradigm matches the syntax that we normally use in ordinary non-computer actions: "Hey, you..." (selection) "...do this" (choose an action).  
Selecting before committing to an action means that the user can explore and change direction without executing inappropriate or time-consuming routines. Simply selecting an object—for example a document—doesn't alter the contents of this object. Making a selection needn't commit the user to anything; there is not a penalty for making an incorrect selection.  
In most cases, the user can undo any selection by making any other selection. When this is not possible, either use an alert box to warn the user, or implement cancel or undo commands to let the user back gracefully out of undesired situations.