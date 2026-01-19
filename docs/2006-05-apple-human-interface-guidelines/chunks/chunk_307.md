<!-- Chunk 307 | Source: 2006-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 653 -->
Use **pop-up menus** to present a list of mutually exclusive choices in a dialog or window. Pop-up menus are used as a means of selecting one choice from a list of many. If you have a dialog with a set of six or more radio buttons, consider using a pop-up menu instead.  
#### A pop-up menu:  
- Usually has a label to the left (in left-to-right scripts) unless the menu is used as the title for a group box
- Has a double-triangle indicator
- Contains nouns (things) or adjectives (states or attributes), but not verbs (commands); use pull-down menus for commands
- Has a checkmark beside the current value when open  
A pop-up menu behaves like other menus: Users drag to choose an item—which then flashes briefly and appears as the current choice—or users move the cursor outside the menu to leave the current value active. An exploratory press in the menu to see what's available doesn't select a new value.  
In special cases, you may want to include a command that affects the contents of the pop-up menu itself. For example, in the Print dialog, the Printer pop-up menu contains Edit Printer List, so users can add a printer to the menu; the new printer becomes the menu's default selection. Put such commands at the bottom of a pop-up menu, below a separator.  
In some circumstances it maybe appropriate to use pop-up menus to complete sentences that describe advanced operations. For example, the Find window in the Finder and the Rules window in Mail Preferences both use pop-up menus in this way.  
Use pop-up menus to present up to 12 mutually exclusive choices that the user doesn't need to see all the time.  
Don't use pop-up menus:  
- For more than 12 items; use a scrolling list unless space is restricted
- When the number of items in the list can change
- When more than one selection is appropriate, such as text styles (in which you can select bold and italic, for example); use checkboxes or a pull-down menu in which checkmarks appear  
Don't use submenuswith pop-up menus. Doingso hides choices too deeplyand is physically difficult to use.  
<span id="page-247-0"></span>Bevel buttons and icon buttons can also be pop-up menus. See "Icon [Buttons](#page-245-0) and Bevel Buttons With [Pop-Up](#page-245-0) Menus " (page 246).  
**Figure 14-20** An open pop-up menu  
![](images/_page_247_Picture_8.jpeg)  
**Carbon:** Available in Interface Builder. To create one programmatically, use the function CreatePopUpButtonControl.  
**Cocoa:** Available in Interface Builder as a pop-up menu is an NSPopUpButton. See *Application Menus and Pop-up Lists* in Cocoa User Experience Documentation.