<!-- Chunk 78 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 1363 -->
Another type of menu is a pop-up menu. A pop-up menu isn't in the menu bar, but appears somewhere else on the screen (usually in a dialog box) when the user clicks in a particular place.  
![](images/_page_102_Picture_0.jpeg)  
Figure 3-43 A dialog box with pop-up menus  
Pop-up menus are used for setting values or choosing from lists of related items. The indication that there is a pop-up menu is a box around the current value, with a one-pixel-thick drop shadow (Figure 3-43). When the user presses on this box, the pop-up menu appears, with the current value—checked and highlighted—under the pointer (Figure 3-44). If the menu has a title, the title highlights while the menu is visible.  
![](images/_page_102_Figure_3.jpeg)  
Figure 3-44
A pop-up menu as the pointer is dragged through It  
The pop-up menu acts like other menus: the user can move around inside it and choose another item, which then appears highlighted in the box, or can move outside it to leave the current value active. If it reaches the top or bottom of the screen, a pop-up menu scrolls like other menus.  
If your application uses pop-up menus, keep the following guidelines in mind:  
- □ Pop-up menus are used only for lists of values or related items (similar to hierarchical submenus); they should not be used for commands.
- ☐ You must draw the shadowed box indicating that there is a pop-up menu, so the user knows that it's there—pop-up menus are never invisible.
- □ While the menu is showing, its title is inverted. If several pop-up menus are near each other, this clears up the possible ambiguity about which one is being chosen from.  
- ☐ The current value always appears under the pointer when the menu appears, so that simply clicking on the box doesn't change the item.
- ☐ Don't use hierarchical pop-up menus.
- □ Pop-up menus don't have Command-key equivalents.  
Always consider whether a pop-up menu is the simplest thing to use in each case, or whether a standard menu or a scrolling box might be more appropriate.  
#### **Palettes**  
Some applications use palettes to provide a quick way for the user to change from one operation to another. A palette is a collection of small symbols, usually enclosed in rectangles. A symbol can be an icon, a pattern, a character, or a drawing that stands for an operation. When the user has clicked on one of the symbols (or in its rectangle), it is distinguished from the other symbols (by highlighting, for example), and the previously highlighted symbol goes back to its normal state. Figure 3-45 shows two palettes from MacPaint.  
![](images/_page_103_Figure_6.jpeg)  
Figure 3-45 Two palettes  
Typically, the symbol that's selected determines what operations the user can perform. Selecting a tool from a palette puts the user into a mode. Modes are generally discouraged but can be justified when changing from one mode to another is almost instantaneous and when the user can always see at a glance which mode is in effect. (Changing the shape of the pointer is one way to indicate that a mode has been set.) Like all modal features, palettes should be used only when they're the most natural way to structure an application.  
A palette can be either part of a window (as in MacDraw) or separate from the main window (as in MacPaint). Each has its disadvantages. If the palette is part of the window, then parts of the palette may be concealed if the user makes the window smaller. On the other hand, if it's not part of the window, then it takes up extra space on the desktop (in which case it should at least be movable so the user can move it out of the way).  
If an application supports multiple open documents but only one palette, the palette reflects the settings for the active window.  
#### Tear-off menus  
A tear-off menu is a menu, generally graphic rather than textual, that the user can "tear" from the menu bar and move around the screen like a window. Tear-off menus save desktop space, allow larger windows, and give the user more flexibility than do fixed palettes.  
The user can choose a pattern from the tear-off menu shown in Figure 3-46 simply by pulling down the menu like any other menu, then dragging the pointer to the desired pattern and releasing the mouse button.  
![](images/_page_104_Picture_5.jpeg)  
Figure 3-46 Graphic pull-down menu  
If the user holds down the Apple key while opening such a menu, then moves the pointer more than ten pixels from any edge of the menu, an outline of the menu follows the pointer. When the mouse button is released, the menu appears at its new location (Figure 3-47).  
![](images/_page_105_Picture_0.jpeg)  
Figure 3-47
Torn-off menu  
Even after a menu has been torn off, it can still be accessed from the menu bar. The state of the torn-off menu must be reflected in its pull-down counterpart, and vice versa (Figure 3-48). A given menu can exist in torn-off form only once: if the user tears it off a second time, the first instance disappears.  
![](images/_page_105_Picture_3.jpeg)  
Figure 3-48
Torn-off menu also available in menu bar  
Like document windows, torn-off menus can be dragged around the screen and closed with a close box. To avoid confusion, however, tear-off menus don't look exactly like document windows. Tear-off menus are always "in front" of all open document windows. If a single application can have more than one menu torn off at a time, the application must determine their order of precedence.