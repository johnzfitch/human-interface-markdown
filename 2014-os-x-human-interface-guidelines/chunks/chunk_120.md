<!-- Chunk 120 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 266 -->
A **command pop-down menu** provides pull-down menu functionality within a window.  
![](images/_page_195_Picture_9.jpeg)  
**API Note:** To define a command pop-down menu in your code, use the NSPopUpButton class and specify the pull down type.  
#### A command pop-down menu:  
- Always displays the same text when it's closed, which acts as the menu title (in contrast, a closed pop-up menu displays the currently selected item). To learn more about pop-up menus, see [Pop-Up](#page-189-1) Menu (page 190).
- Contains a single, downward-pointing arrow and can display checkmarks to the left of all currently active selections.  
● Opens when users click anywhere in the control.  
**Avoid listing too many items in a command pop-down menu.** Command pop-down menus should contain between 3 and 12 commands. The items in a command pop-down menu don't have to be mutually exclusive.  
**In general, don't supply an introductory label for a command pop-down menu.** The text in the control should be sufficient to tell users what they can expect to find in the menu.