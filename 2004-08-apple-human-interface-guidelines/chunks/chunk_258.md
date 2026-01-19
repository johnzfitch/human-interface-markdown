<!-- Chunk 258 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 7034 -->
Always try to use tab views to indicate multiple changeable panes, as shown in the previous sections. However, if you have too many tabs to fit into a window properly you should instead use a pop-up menu to change the contents of a group box (see [Figure 11-24](#page-224-2) (page 225).  
<span id="page-224-1"></span>As with tabs, the pop-up menu should be centered on the top of the group box.  
<span id="page-224-2"></span>**Figure 11-24** Pop-up menu for changeable panes  
![](images/_page_224_Picture_5.jpeg)  
#### **CHAPTER 11**  
Layout Examples  
<span id="page-226-5"></span><span id="page-226-1"></span><span id="page-226-0"></span>Table A-1 lists all the keyboard shortcuts that are predefined for use by the operating system and those recommended for use in applications. The table is organized by the key that is modified, with variations of modifier keys grouped together. References to explanations of how to use these shortcuts are in the Action column.  
Some sequences have icons that provide additional information:  
- - indicates that the operating system uses that shortcut. Do not override these shortcuts.
- <span id="page-226-2"></span>■  
indicates that these are suggested keyboard shortcuts for applications. Unless your application does not implement the functionality represented by the shortcut, you should provide these keyboard shortcuts.  
The unmarked keyboard shortcuts are suggested for the specified action *if a keyboard shortcut is necessary*—just because a shortcut exists does not mean you need to use it. Try to avoid using these keyboard shortcuts for actions other than those indicated.  
For more information on keyboard shortcuts, including when to use them, see ["Keyboard](#page-27-0) [Shortcuts"](#page-27-0) (page 28). This table lists only the combinations of two or more keys. For information on how to use specific single keys, see ["The Functions of Specific Keys"](#page-20-1) (page 21).  
<span id="page-226-4"></span><span id="page-226-3"></span>**Table A-1** Keyboard shortcuts  
| Primary key | Keyboard sequence       | Action                                                                                                         |
|-------------|-------------------------|----------------------------------------------------------------------------------------------------------------|
| Space bar   | Command–Space bar       | Rotates through enabled script<br>systems.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28). |
|             | Shift–Command–Space bar | Apple reserved.                                                                                                |  
<span id="page-227-5"></span><span id="page-227-4"></span><span id="page-227-3"></span><span id="page-227-2"></span><span id="page-227-1"></span><span id="page-227-0"></span>  
| Primary key | Keyboard sequence         | Action                                                                                                                                                                                                |
|-------------|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|             | Option–Command–Space bar  | Rotates through keyboard<br>layouts and input methods<br>within a script.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                                         |
|             | Control–Command–Space bar | Apple reserved.                                                                                                                                                                                       |
| Tab         | Shift-Tab                 | Navigates through controls in<br>a reverse direction.<br>See "Keyboard Focus and<br>Navigation" (page 31).                                                                                            |
|             | Command-Tab               | Moves forward to the next<br>most recently used application<br>in a list of open applications.                                                                                                        |
|             | Command-Shift-Tab         | Moves backward through a list<br>of open applications (sorted by<br>recent use).                                                                                                                      |
|             | Control-Tab               | Moves focus to the next<br>grouping of controls in a<br>dialog or the next table (when<br>Tab moves to the next cell).<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities. |
|             | Shift-Control-Tab         | Moves focus to the previous<br>grouping of controls.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                   |
| Esc         | Command-Option-Esc        | Opens the Force Quit dialog.                                                                                                                                                                          |
| Eject       | Command-Control-Eject     | Quits all applications (after<br>giving the user a chance to<br>save changes to open<br>documents) and restart the<br>computer.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).   |  
<span id="page-228-6"></span><span id="page-228-5"></span><span id="page-228-4"></span><span id="page-228-3"></span><span id="page-228-2"></span><span id="page-228-1"></span><span id="page-228-0"></span>  
| Primary key | Keyboard sequence            | Action                                                                                                                                                                                                 |
|-------------|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|             | Command-Option-Control-Eject | Quits all applications (after<br>giving the user a chance to<br>save changes to open<br>documents) and shuts the<br>computer down.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28). |
| F1          | Control-F1                   | Toggles full keyboard access<br>on or off.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                              |
| F2          | Control-F2                   | Moves focus to the menu bar.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                                            |
| F3          | Control-F3                   | Moves focus to the Dock.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                                                |
| F4          | Control-F4                   | Moves focus to the active (or<br>next) window.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                          |
|             | Shift-Control-F4             | Moves focus to the previously<br>active window.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                         |
| F5          | Control-F5                   | Moves focus to the toolbar.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                                             |
| F6          | Control-F6                   | Moves focus to the first (or<br>next) utility window.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                                   |  
<span id="page-229-5"></span><span id="page-229-4"></span><span id="page-229-3"></span><span id="page-229-2"></span><span id="page-229-1"></span><span id="page-229-0"></span>  
| Primary key       | Keyboard sequence | Action                                                                                                                                                              |
|-------------------|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                   | Shift-Control-F6  | Moves focus to the previous<br>utility window.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                       |
| F7                | Control-F7        | Temporarily overrides the<br>current keyboard access mode<br>in windows and dialogs.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities. |
| `(grave accent)   | Command-`         | Activates the next open<br>window in the frontmost<br>application.<br>See "Window<br>Layering" (page 120).                                                          |
|                   | Command-Shift-`   | Activates the previous open<br>window in the frontmost<br>application.<br>See "Window<br>Layering" (page 120).                                                      |
| - (hyphen)        | Command           | Equivalent to the Smaller<br>command.<br>See "The Format<br>Menu" (page 92).                                                                                        |
|                   | Command-Option    | Zooms out (screen zooming).<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.                                                          |
| { (left bracket)  | Command-{         | Equivalent to the Align Left<br>command.<br>See "The Format<br>Menu" (page 92).                                                                                     |
| } (right bracket) | Command-}         | Equivalent to the Align Right<br>command.<br>See "The Format<br>Menu" (page 92).                                                                                    |
| (pipe)            | Command-          | Equivalent to the Align Center<br>command.<br>See "The Format<br>Menu" (page 92).                                                                                   |  
<span id="page-230-3"></span><span id="page-230-2"></span><span id="page-230-1"></span><span id="page-230-0"></span>  
| Primary key       | Keyboard sequence        | Action                                                                                                        |
|-------------------|--------------------------|---------------------------------------------------------------------------------------------------------------|
| : (colon)         | Command-:                | Equivalent to the Spelling<br>command.<br>See "The Edit<br>Menu" (page 90).                                   |
| ; (semicolon)     | Command-;                | Equivalent to the Check<br>Spelling command.<br>See "The Edit<br>Menu" (page 90).                             |
| , (comma)         | Command-,                | Equivalent to the Preferences<br>command.<br>See "The Application<br>Menu" (page 87).                         |
|                   | Command-Option-Control-, | Decreases screen contrast.<br>See "The Application<br>Menu" (page 87).                                        |
| . (period)        | Command-Option-Control   | Increases the screen contrast.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities. |
| ? (question mark) | Command-?                | Opens help for the application.<br>See Apple Software Design<br>Guidelines.                                   |
| / (forward slash) | Command-Option-/         | Turns font smoothing on or off.                                                                               |
| = (equal sign)    | Command-Shift-=          | Equivalent to the Bigger<br>command.<br>See "The Format<br>Menu" (page 92).                                   |
|                   | Command-Option-=         | Zooms in (screen zooming).<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.     |
| 3                 | Command-Shift-3          | Captures screen to file.                                                                                      |
|                   | Command-Shift-Control-3  | Captures screen to Clipboard.                                                                                 |
| 4                 | Command-Shift-4          | Captures selection to file.                                                                                   |
|                   | Command-Shift-Control-4  | Captures selection to<br>Clipboard.                                                                           |  
<span id="page-231-5"></span><span id="page-231-4"></span><span id="page-231-3"></span><span id="page-231-2"></span><span id="page-231-1"></span><span id="page-231-0"></span>  
| Primary key | Keyboard sequence        | Action                                                                                                            |
|-------------|--------------------------|-------------------------------------------------------------------------------------------------------------------|
| 8           | Command-Option-8         | Turns screen zooming on or<br>off.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities. |
|             | Command-Option-Control-8 | Inverts the screen colors.<br>See Making Carbon Applications<br>Accessible to Users With<br>Disabilities.         |
| A           | Command-A                | Equivalent to the Select All<br>command.<br>See "The Edit<br>Menu" (page 90).                                     |
| B           | Command-B                | Equivalent to the Bold<br>command.<br>See "The Edit<br>Menu" (page 90).                                           |
| C           | Command-C                | Equivalent to the Copy<br>command.<br>See "The Edit<br>Menu" (page 90).                                           |
|             | Command-Shift-C          | Equivalent to the Show Colors<br>command.<br>See "The Format<br>Menu" (page 92).                                  |
|             | Command-Option-C         | Equivalent to the Copy Style<br>command.<br>See "The Edit<br>Menu" (page 90).                                     |
|             | Command-Control-C        | Equivalent to the Copy Ruler<br>command.<br>See "The Edit<br>Menu" (page 90).                                     |
| D           | Command-D                | Equivalent to the Find<br>Previous command.<br>See "The Edit<br>Menu" (page 90).                                  |
|             | Command-Option-D         | Shows or hides the Dock.<br>See Apple Software Design<br>Guidelines.                                              |  
<span id="page-232-10"></span><span id="page-232-9"></span><span id="page-232-8"></span><span id="page-232-7"></span><span id="page-232-6"></span><span id="page-232-5"></span><span id="page-232-4"></span><span id="page-232-3"></span><span id="page-232-2"></span><span id="page-232-1"></span><span id="page-232-0"></span>  
| Primary key | Keyboard sequence | Action                                                                                         |
|-------------|-------------------|------------------------------------------------------------------------------------------------|
| E           | Command-E         | Uses selection for a find<br>operation.<br>See "Find Window" (page 131).                       |
| F           | Command-F         | Equivalent to the Find<br>command.<br>See "The Edit<br>Menu" (page 90).                        |
|             | Command-Option-F  | Jumps to the search field<br>control.<br>See "Search Fields" (page 189).                       |
| G           | Command-G         | Equivalent to the Find Next<br>command.<br>See "The Edit<br>Menu" (page 90).                   |
|             | Command-Shift-G   | Equivalent to the Find<br>Previous command.<br>See "The Edit<br>Menu" (page 90).               |
| H           | Command-H         | Equivalent to the Hide<br>ApplicationName command.<br>See "The Application<br>Menu" (page 87). |
|             | Command-Option-H  | Equivalent to the Hide Others<br>command.<br>See "The Application<br>Menu" (page 87).          |
| I           | Command-I         | Equivalent to the Italic<br>command.<br>See "The Edit<br>Menu" (page 90).                      |
|             | Command-I         | Equivalent to the Show Info<br>command.<br>See "The File Menu" (page 88).                      |
|             | Command-Option-I  | Equivalent to the Show<br>Inspector command.<br>See "The File Menu" (page 88).                 |
| J           | Command-J         | Scrolls to selection.                                                                          |
| M           | Command-M         | Equivalent to the Minimize<br>command.<br>See "The Window<br>Menu" (page 96).                  |  
<span id="page-233-8"></span><span id="page-233-7"></span><span id="page-233-6"></span><span id="page-233-5"></span><span id="page-233-4"></span><span id="page-233-3"></span><span id="page-233-2"></span><span id="page-233-1"></span><span id="page-233-0"></span>  
| Primary key | Keyboard sequence      | Action                                                                                    |
|-------------|------------------------|-------------------------------------------------------------------------------------------|
|             | Command-Option-M       | Equivalent to the Minimize All<br>Windows command.<br>See "The Window<br>Menu" (page 96). |
| N           | Command-N              | Equivalent to the New<br>command.<br>See "The File Menu" (page 88).                       |
| O           | Command-O              | Equivalent to the Open<br>command.<br>See "The File Menu" (page 88).                      |
| P           | Command-P              | Equivalent to the Print<br>command.<br>See "The File Menu" (page 88).                     |
|             | Command-Shift-P        | Equivalent to the Page Setup<br>command.<br>See "The File Menu" (page 88).                |
| Q           | Command-Q              | Equivalent to the Quit<br>command.<br>See "The Apple<br>Menu" (page 86).                  |
|             | Command-Shift-Q        | Equivalent to the Log Out<br>command.<br>See Apple Software Design<br>Guidelines.         |
|             | Command-Shift-Option-Q | Logs out without confirmation.<br>See Apple Software Design<br>Guidelines.                |
| S           | Command-S              | Equivalent to the Save<br>command.<br>See "The File Menu" (page 88).                      |
|             | Command-Shift-S        | Equivalent to the Save As<br>command.<br>See "The File Menu" (page 88).                   |
| T           | Command-T              | Equivalent to the Show Fonts<br>command.<br>See "The Edit<br>Menu" (page 90).             |  
<span id="page-234-10"></span><span id="page-234-9"></span><span id="page-234-8"></span><span id="page-234-7"></span><span id="page-234-6"></span><span id="page-234-5"></span><span id="page-234-4"></span><span id="page-234-3"></span><span id="page-234-2"></span><span id="page-234-1"></span><span id="page-234-0"></span>  
| Primary key | Keyboard sequence | Action                                                                                                            |
|-------------|-------------------|-------------------------------------------------------------------------------------------------------------------|
|             | Command-Option-T  | Equivalent to the Show/Hide<br>Toolbar command.<br>See "The View<br>Menu" (page 93) and<br>"Toolbars" (page 108). |
| U           | Command-U         | Equivalent to the Underline<br>command.<br>See "The Edit<br>Menu" (page 90).                                      |
| V           | Command-V         | Equivalent to the Paste<br>command.<br>See "The File Menu" (page 88).                                             |
|             | Command-Option-V  | Equivalent to the Paste Style<br>command.<br>See "The Edit<br>Menu" (page 90).                                    |
|             | Command-Control-V | Equivalent to the Paste Ruler<br>command.<br>See "The Edit<br>Menu" (page 90).                                    |
| W           | Command-W         | Equivalent to the Close<br>command.<br>See "The File Menu" (page 88).                                             |
|             | Command-Shift-W   | Equivalent to the Close File<br>command.<br>See "The File Menu" (page 88).                                        |
|             | Command-Option-W  | Equivalent to the Close All<br>Windows command.<br>See "The File Menu" (page 88).                                 |
| X           | Command-X         | Equivalent to the Cut<br>command.<br>See "The File Menu" (page 88).                                               |
| Z           | Command-Z         | Equivalent to the Undo<br>command.<br>See "The File Menu" (page 88).                                              |
|             | Command-Shift-Z   | Equivalent to the Redo<br>command.<br>See "The File Menu" (page 88).                                              |  
<span id="page-235-7"></span><span id="page-235-6"></span><span id="page-235-5"></span><span id="page-235-4"></span><span id="page-235-3"></span><span id="page-235-2"></span><span id="page-235-1"></span><span id="page-235-0"></span>  
| Primary key | Keyboard sequence         | Action                                                                                                                                                                     |
|-------------|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Right Arrow | Command–Right Arrow       | Changes keyboard layout to<br>current layout of Roman script.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                          |
|             | Command–Shift–Right Arrow | Extends selection to the next<br>semantic unit, typically the end<br>of the current line.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).              |
|             | Shift–Right Arrow         | Extends selection one character<br>to the right.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                                       |
|             | Shift–Option–Right Arrow  | Extends selection to the end of<br>the current word, then to the<br>end of the next word.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).              |
|             | Control–Right Arrow       | Moves focus to another value<br>or cell within a control, such as<br>a table.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                          |
| Left Arrow  | Command–Left Arrow        | Changes keyboard layout to<br>current layout of system script<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                          |
|             | Command–Shift–Left Arrow  | Extends selection to the<br>previous semantic unit,<br>typically the beginning of the<br>current line.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28). |
|             | Shift–Left Arrow          | Extends selection one character<br>to the left.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                                        |  
<span id="page-236-4"></span><span id="page-236-3"></span><span id="page-236-2"></span><span id="page-236-1"></span><span id="page-236-0"></span>  
| Primary key | Keyboard sequence       | Action                                                                                                                                                                                    |
|-------------|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|             | Shift–Option–Left Arrow | Extends selection to the<br>beginning of the current word,<br>then to the beginning of the<br>previous word.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).          |
|             | Control–Left Arrow      | Moves focus to another value<br>or cell within a control, such as<br>a table.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                         |
| Up Arrow    | Command–Shift–Up Arrow  | Extends selection upward in<br>the next semantic unit,<br>typically the beginning of the<br>document.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                 |
|             | Shift–Up Arrow          | Extends selection to the line<br>above, to the nearest character<br>boundary at the same<br>horizontal location.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).      |
|             | Shift–Option–Up Arrow   | Extends selection to the<br>beginning of the current<br>paragraph, then to the<br>beginning of the next<br>paragraph.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28). |
|             | Control–Up Arrow        | Moves focus to another value<br>or cell within a control, such as<br>a table.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                         |  
<span id="page-237-4"></span><span id="page-237-3"></span><span id="page-237-2"></span><span id="page-237-1"></span><span id="page-237-0"></span>  
| Primary key | Keyboard sequence        | Action                                                                                                                                                                                                                                                          |
|-------------|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Down Arrow  | Command–Shift–Down Arrow | Extends selection downward<br>in the next semantic unit,<br>typically the end of the<br>document.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                                                                           |
|             | Shift–Down Arrow         | Extends selection to the line<br>below, to the nearest character<br>boundary at the same<br>horizontal location.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                                                            |
|             | Shift–Option–Down Arrow  | Extends selection to the end of<br>the current paragraph, then to<br>the end of the next paragraph<br>(include the blank line between<br>paragraphs in cut, copy, and<br>paste operations).<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28). |
|             | Control–Right Arrow      | Moves focus to another value<br>or cell within a control, such as<br>a table.<br>See "Keyboard Shortcuts<br>Reserved by the<br>System" (page 28).                                                                                                               |