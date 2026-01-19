<!-- Chunk 159 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 784 -->
A button's appearance during a click (or while it's pressed) should change in one of the following ways:  
- It can highlight.
- It can both highlight and appear to be pushed in.
- It can change the image it displays.  
**Note:** Highlighting can be done either automatically by the Application Kit or by changing the image to a custom, "highlighted" image.  
Buttons normally both push in and highlight. However, for aesthetic reasons, buttons that are right next to each other (such as scroll buttons and graphical radio buttons) shouldn't push in. This is because buttons that have no space around their bezeled edges look less three-dimensional than normal.  
**Note:** Although it's possible to have a button only push in (without highlighting), this isn't recommended because it's hard to see.  
The recommended changes for action (one-state) buttons are illustrated in the following figure. The scroll button in the bottom row doesn't push in, since it's very small and is right up against another scroll button.  
![](images/_page_152_Picture_9.jpeg)  
The possibilities for two-state buttons are illustrated in the following figure.  
![](images/_page_152_Picture_11.jpeg)  
Note: In the figure showing two-state buttons, the button in the bottom row is a graphical radio button. It doesn't push in because it's right next to the other radio buttons in its group (although they aren't shown in this figure).  
The figure of two-state buttons also illustrates some of the principles that determine how a button looks during a click:  
- A button must change its appearance during a click, as soon as the mouse button goes down.
- The appearance of a button during a click should reflect what's about to happen. Buttons that display a state should reflect the new state both during and after the click.  
#### Implementing Pop-Up and Pull-Down Lists  
You must provide a title for each pop-up list. Usually this is done by putting a titled box around the pop-up list's button. The figure below shows a typical example, using a box with the title Units.  
![](images/_page_153_Picture_6.jpeg)  
Because the label on a pull-down list's button doesn't change, pull-down lists don't need a titled box around them.  
When using a pop-up or pull-down list, be careful that the open list doesn't blend in with the objects near it. If an item in the list pops up next to a label, for example, users might interpret them in combination. Take care, too, that the open list doesn't obscure any objects that help users understand its content.  
#### Programming Note: Lists that Bring Up Attention Panels  
When an item in a pop-up or pull-down list opens an attention panel, the list by default stays up until the panel is dismissed. Because lists are in a higher window tier than attention panels, they can obscure attention panels. To avoid this, you should dismiss the list before bringing up the attention panel. One way of doing this is to have the list item call the perform:with:afterDelay:canceIPrevious: method to schedule the execution of a method 1 millisecond in the future. This method should then bring up the attention panel.