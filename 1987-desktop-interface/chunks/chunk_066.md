<!-- Chunk 66 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 1630 -->
The items in <sup>a</sup> particular menu should be logically related to the title of the menu. Menu items must be terse, preferably one word with the first letter capitalized. If it's necessary to use more than one word (Save As or Page Setup, for example), capitalize all important words in the name. In addition to the names, three features of menus help the user understand what each item does: grouping, toggles, and special visual features.  
#### Grouping operations in menus  
The most frequently used operations should be at the top of a menu. The least frequently used (such as Quit) should be at the bottom.  
As already mentioned, there are two kinds of menu items: actions (verbs) and attributes (adjectives). An attribute stays in effect until it's canceled, whereas an action ceases to be relevant after it has been performed. A single menu can contain both actions and attributes, but the actions should be grouped together and the attributes grouped together. The groups are separated by dotted lines (the dotted lines are actually disabled menu items that are "named" with <sup>a</sup> horizontal line; Figure 3-22 illustrates these visual features of menus).  
Another reason to group operations is to break up <sup>a</sup> menu so it's easier to read. Operations grouped for this reason are logically related, but independent. Operations that are actions are usually grouped this way, such as Cut, Copy, Paste, and Clear in the Edit menu.  
Attribute operations that are interdependent are grouped, either as mutually exclusive groups or as accumulating groups.  
In a mutually exclusive attribute group, only one item in the group is in effect at any one time. The item that's in effect is preceded in the menu by <sup>a</sup> check mark. If the user chooses <sup>a</sup> different item in the group, the check mark is moved to the new item. An example is the Finder's View menu, in which only one view at a time can be in effect (Figure 3-20). (Radio button controls, in which pressing one button in a group disables all the others, are also examples of mutually exclusive attribute groups.)  
![](images/_page_81_Picture_0.jpeg)  
Figure 3-20 View menu  
In an accumulating attribute group, any number of attributes can be in effect at the same time. One of the items in the group cancels all the others. An example is the standard Style menu, in which the user can choose any combination of Bold, Italic, Underline, Outline, or Shadow—but Plain Text cancels all the others. (Check-box controls, in which all, none, or any other number of the boxes may be in effect at a time, are also examples of accumulating attributes.)  
#### Toggled menu items  
Another way to show the presence or absence of an attribute is with <sup>a</sup> toggled operation. A toggled attribute has two states, and <sup>a</sup> single menu item allows the user to "toggle" between the states. You can show the user that an operation is toggled either with check marks or by changing the wording.  
Here's an example of changing the wording in <sup>a</sup> toggled menu item. When rulers are showing in <sup>a</sup> program that uses rulers, one item in the Format menu is Hide Rulers. If the user chooses this item, the rulers are hidden, and the name changes to Show Rulers (Figure 3-21). Use this technique only when the wording of the items makes it obvious that they're opposite states of the same attribute—it's better to use verbs (Turn on... /Turn off... or Hide.../Show...) rather than nouns for this sort of menu item. Undo and Redo is another good example.  
![](images/_page_81_Picture_6.jpeg)  
Figure 3-21 Toggled operations  
#### Special visual features  
In addition to the way menu items are name and grouped, menus have other features that provide added information:  
- An ellipsis (...) after <sup>a</sup> menu item means that after the item is chosen, the user will be asked for more information before the operation is carried out. Usually, the user must fill in <sup>a</sup> dialog box and click an OK button or its equivalent. Don't use the ellipsis when the dialog box that will appear is merely <sup>a</sup> confirmation or warning (for example, "Save changes before quitting?").
- D Check marks indicate attributes that are currently in effect.
- Any menu items that the user can't choose at the moment are displayed in gray letters. If the user moves the pointer over a dimmed item, that item isn't highlighted.
- a If an item has a keyboard equivalent (if it can be chosen from the keyboard as well as from <sup>a</sup> menu), its name in the menu is followed by the Apple (or cloverleaf) symbol and a character. To choose an item this way, the user presses the character key while holding down the Apple (Command) key.  
Figure 3-22 illustrates these features.  
Several other menu features are also supported:  
- D In the Style menu only, menu items can be shown in Bold, Italic, Outline, Underline, or Shadow, to illustrate the text styles themselves.
- A menu item can be preceded by <sup>a</sup> special character such as V or (to indicate which item is in effect). Icons can also appear in menus, but because of their size they require two menu lines.
- D Applications can have special kinds of menus for special situations. A pull-down menu can even be <sup>a</sup> palette that can be "torn off the menu bar and moved around the screen (Figure 3-23). See "Palettes" later in this chapter.  
![](images/_page_83_Figure_0.jpeg)  
Figure 3-22 Visual features of menus  
![](images/_page_83_Picture_2.jpeg)  
Figure 3-23 A pull-down palette  
#### Scrolling menus  
If a menu becomes too long to fit on the screen, an indicator appears at the bottom of the menu to show that there are more items (Figure 3-24). When the user drags over the indicator, the menu scrolls to show the additional items. When the last item is shown, the indicator disappears.  
![](images/_page_84_Picture_2.jpeg)  
Figure 3-24 Scrolling menu Indicator at bottom of menu  
As soon as the menu starts scrolling, another indicator appears at the top of the menu to show that some items are now hidden in that direction (Figure 3-25).  
![](images/_page_84_Picture_5.jpeg)  
Figure 3-25 Scrolling menu indicator at top of menu  
If the user drags back up to the top, the menu scrolls back down in the same manner. If the user lets go of the mouse button or selects another menu, and then selects the original menu again, it appears in its original position, with the hidden items and the indicator at the bottom.