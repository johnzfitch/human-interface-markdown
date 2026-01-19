<!-- Chunk 313 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 6841 -->
<span id="page-370-1"></span>Table A-1 lists the system-reserved and commonly used keyboard shortcuts mentioned in the rest of this document.  
As you implement keyboard shortcuts in your application, use this table to find:  
- Which key sequences are reserved by Mac OS X. Users rely on these shortcuts to perform the specified actions no matter which application is currently running (these include shortcuts reserved for accessibility purposes). *Do not override these shortcuts*.
- Which key sequences are recommended for common application tasks. Users expect these shortcuts to mean the same thing from application to application. Provide these shortcuts *if your applicationperformsthe associated tasks*. You should avoid usingthese shortcuts for other purposes.  
If a keyboard sequence is not listed in Table A-1 you can use it for a frequently used command in your application, if a shortcut is appropriate. For guidance on creating new keyboard shortcuts, see "Creating Your Own Keyboard [Shortcuts"](#page-106-1) (page 107) Be aware, however, that Apple may reserve other keyboard shortcuts in the future. For more information on the system-reserved keyboard shortcuts, see "Reserved Keyboard [Shortcuts"](#page-105-2) (page 106)  
**Note:** With the exception of the system-reserved function keys F9, F10, F11, and F12, Table A-1 lists only combinations of two or more keys. For information on how to use specific single keys (such as Tab and Return), see "The [Functions](#page-98-1) of Specific Keys" (page 99)  
Table A-1 groups together the primary key that is modified and variations of key sequences based on the primary key. In the interests of space, the table uses the following symbols to represent the modifier keys (these are the same symbols menus display):  
- (Command) (Control)
- (Option)
- (Shift)  
Some shortcuts in Table A-1 are accompanied byan icon. This means thatyou should not override the shortcut because the operating system uses it in some way.  
A shortcut in Table A-1 that is not accompanied by an icon is recommended for applications that perform the associated task. If your application does not perform the task associated with a recommended shortcut, you should not use that shortcut to mean something else.  
<span id="page-371-0"></span>**Table A-1** Keyboard shortcuts  
<span id="page-371-10"></span><span id="page-371-9"></span><span id="page-371-8"></span><span id="page-371-7"></span><span id="page-371-6"></span><span id="page-371-5"></span><span id="page-371-4"></span><span id="page-371-3"></span><span id="page-371-2"></span><span id="page-371-1"></span>  
| Primary key | Key sequence | Associated action                                                                                                                                              |
|-------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Space bar   | Space        | Showor hide the Spotlight search field (when multiple languages<br>are installed, may rotate through enabled script systems).                                  |
|             | Space        | Apple reserved.                                                                                                                                                |
|             | Space        | Show the Spotlight search results window (when multiple<br>languages are installed, may rotate through keyboard layouts<br>and input methods within a script). |
|             | Space        | Apple reserved.                                                                                                                                                |
| Tab         | Tab          | Navigate through controls in a reverse direction. See "Keyboard<br>Focus and Navigation" (page 109).                                                           |
|             | Tab          | Move forward to the next most recently used application in a<br>list of open applications.                                                                     |
|             | Tab          | Move backward through a list of open applications (sorted by<br>recent use).                                                                                   |
|             | Tab          | Move focus to the next grouping of controls in a dialog or the<br>next table (when Tab moves to the next cell). See Accessibility<br>Overview.                 |
|             | Tab          | Move focus to the previousgroupingof controls. See Accessibility<br>Overview.                                                                                  |
| Esc         | Esc          | Open Front Row.                                                                                                                                                |
|             | Esc          | Open the Force Quit dialog.                                                                                                                                    |
| Eject       | Eject        | Quit all applications (after giving the user a chance to save<br>changes to open documents) and restart the computer.                                          |
|             | Eject        | Quit all applications (after giving the user a chance to save<br>changes to open documents) and shut the computer down.                                        |
| F1          | F1           | Toggle full keyboard access on or off. See Accessibility Overview.                                                                                             |
| F2          | F2           | Move focus to the menu bar. See Accessibility Overview.                                                                                                        |
| F3          | F3           | Move focus to the Dock. See Accessibility Overview.                                                                                                            |  
<span id="page-372-10"></span><span id="page-372-9"></span><span id="page-372-8"></span><span id="page-372-7"></span><span id="page-372-6"></span><span id="page-372-5"></span><span id="page-372-4"></span><span id="page-372-3"></span><span id="page-372-2"></span><span id="page-372-1"></span><span id="page-372-0"></span>  
| Primary key          | Key sequence | Associated action                                                                                                |
|----------------------|--------------|------------------------------------------------------------------------------------------------------------------|
| F4                   | F4           | Move focus to the active (or next) window. See Accessibility<br>Overview.                                        |
|                      | F4           | Move focus to the previously active window. See Accessibility<br>Overview.                                       |
| F5                   | F5           | Move focus to the toolbar. See Accessibility Overview.                                                           |
|                      | F5           | Turn VoiceOver on or off. See Accessibility Overview.                                                            |
| F6                   | F6           | Move focus to the first (or next) panel. See Accessibility Overview.                                             |
|                      | F6           | Move focus to the previous panel. See Accessibility Overview.                                                    |
| F7                   | F7           | Temporarily override the current keyboard access mode in<br>windows and dialogs. See Accessibility Overview.     |
| F9                   |              | Tile or untile all open windows.                                                                                 |
| F10                  |              | Tile or untile all open windows in the currently active<br>application.                                          |
| F11                  |              | Hide or show all open windows.                                                                                   |
| F12                  |              | Hide or display Dashboard.                                                                                       |
| `(grave<br>accent)   | `            | Activate the next open window in the frontmost application.<br>See "Window Layering" (page 224).                 |
|                      | `            | Activate the previous openwindowin the frontmost application.<br>See "Window Layering" (page 224).               |
|                      | `            | Move focus to the window drawer.                                                                                 |
| - (hyphen)           | -            | Decrease the size of the selected item (equivalent to the Smaller<br>command). See "The Format Menu" (page 184). |
|                      | -            | Zoom outwhen screen zoomingis on. See Accessibility Overview.                                                    |
| { (left<br>bracket)  | {            | Left-align a selection (equivalent to the Align Left command).<br>See "The Format Menu" (page 184).              |
| } (right<br>bracket) | }            | Right-align a selection (equivalent to the Align Right command).<br>See "The Format Menu" (page 184).            |
| (pipe)               |              | Center-align a selection (equivalent to the Align Center<br>command). See "The Format Menu" (page 184).          |
| : (colon)            | :            | Display the Spelling window (equivalent to the Spelling<br>command). See "The Edit Menu" (page 181).             |  
<span id="page-373-10"></span><span id="page-373-9"></span><span id="page-373-8"></span><span id="page-373-7"></span><span id="page-373-6"></span><span id="page-373-5"></span><span id="page-373-4"></span><span id="page-373-3"></span><span id="page-373-2"></span><span id="page-373-1"></span><span id="page-373-0"></span>  
| Primary key          | Key sequence | Associated action                                                                                                                                           |
|----------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ;<br>(semicolon)     | ;            | Find misspelledwords in the document (equivalent to the Check<br>Spelling command). See "The Edit Menu" (page 181).                                         |
| , (comma)            | ,            | Open the application's preferences window (equivalent to the<br>Preferences command). See "The Application Menu" (page 178).                                |
|                      | ,            | Decrease screen contrast. See Accessibility Overview.                                                                                                       |
| . (period)           |              | Increase screen contrast. See Accessibility Overview.                                                                                                       |
| ? (question<br>mark) | ?            | Open the application's help in Help Viewer. See "The Help<br>Menu" (page 187).                                                                              |
| / (forward<br>slash) | /            | Turn font smoothing on or off.                                                                                                                              |
| = (equal<br>sign)    | =            | Increase the size of the selected item (equivalent to the Bigger<br>command). See "The Format Menu" (page 184).                                             |
|                      | =            | Zoom in when screen zooming is on. See Accessibility Overview.                                                                                              |
| 3                    | 3            | Capture the screen to a file.                                                                                                                               |
|                      | 3            | Capture the screen to the Clipboard.                                                                                                                        |
| 4                    | 4            | Capture a selection to a file.                                                                                                                              |
|                      | 4            | Capture a selection to the Clipboard.                                                                                                                       |
| 8                    | 8            | Turn screen zooming on or off. See Accessibility Overview.                                                                                                  |
|                      | 8            | Invert the screen colors. See Accessibility Overview.                                                                                                       |
| A                    | A            | Highlight everyitem in a document orwindow, or all characters<br>in a text field (equivalent to the Select All command). See "The<br>Edit Menu" (page 181). |
| B                    | B            | Boldface the selected text or toggle boldfaced text on and off<br>(equivalent to the Bold command). See "The Edit Menu" (page<br>181).                      |
| C                    | C            | Duplicate the selected data and store on the Clipboard<br>(equivalent to the Copy command). See "The Edit Menu" (page<br>181).                              |
|                      | C            | Display the Colors window (equivalent to the Show Colors<br>command). See "The Format Menu" (page 184).                                                     |
|                      | C            | Copy the style of the selected text (equivalent to the Copy Style<br>command). See "The Format Menu" (page 184).                                            |  
<span id="page-374-15"></span><span id="page-374-14"></span><span id="page-374-13"></span><span id="page-374-12"></span><span id="page-374-11"></span><span id="page-374-10"></span><span id="page-374-9"></span><span id="page-374-8"></span><span id="page-374-7"></span><span id="page-374-6"></span><span id="page-374-5"></span><span id="page-374-4"></span><span id="page-374-3"></span><span id="page-374-2"></span><span id="page-374-1"></span><span id="page-374-0"></span>  
| Primary key | Key sequence | Associated action                                                                                                                                            |
|-------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
|             | C            | Copy the formatting settings of the selected item and store on<br>the Clipboard (equivalent to the Copy Ruler command). See<br>"The Format Menu" (page 184). |
| D           | D            | Show or hide the Dock. See "The Dock" (page 64).                                                                                                             |
|             | D            | Display the definition of the selected word in the Dictionary<br>application.                                                                                |
| E           | E            | Use the selection for a find operation. See "Find Windows" (page<br>246).                                                                                    |
| F           | F            | Open a Find window (equivalent to the Find command). See<br>"The Edit Menu" (page 181).                                                                      |
|             | F            | Jump to the search field control. See "Search Fields" (page 330).                                                                                            |
| G           | G            | Find the next occurrence of the selection (equivalent to the Find<br>Next command). See "The Edit Menu" (page 181).                                          |
|             | G            | Find the previous occurrence of the selection (equivalent to the<br>Find Previous command). See "The Edit Menu" (page 181).                                  |
| H           | H            | Hide the windows of the currently running application<br>(equivalent to the Hide ApplicationName command). See "The<br>Application Menu" (page 178).         |
|             | H            | Hide the windows of all other running applications (equivalent<br>to the Hide Others command). See "The Application<br>Menu" (page 178).                     |
| I           | I            | Italicize the selected text ortoggle italic text on or off (equivalent<br>to the Italic command). See "The Format Menu" (page 184).                          |
|             | I            | Display an Info window. See "Inspector Windows" (page 232).                                                                                                  |
|             | I            | Display an inspector window. See "Inspector Windows" (page<br>232).                                                                                          |
| J           | J            | Scroll to a selection.                                                                                                                                       |
| M           | M            | Minimize the active window to the Dock (equivalent to the<br>Minimize command). See "The Window Menu" (page 186).                                            |
|             | M            | Minimize all windows of the active application to the Dock<br>(equivalent to the Minimize All command). See "The Window<br>Menu" (page 186).                 |
| N           | N            | Open a new document (equivalent to the New command). See<br>"The File Menu" (page 179).                                                                      |
| O           | O            | Display a dialog for choosing a document to open (equivalent<br>to the Open command). See "The File Menu" (page 179).                                        |  
<span id="page-375-13"></span><span id="page-375-12"></span><span id="page-375-11"></span><span id="page-375-10"></span><span id="page-375-9"></span><span id="page-375-8"></span><span id="page-375-7"></span><span id="page-375-6"></span><span id="page-375-5"></span><span id="page-375-4"></span><span id="page-375-3"></span><span id="page-375-2"></span><span id="page-375-1"></span><span id="page-375-0"></span>  
| Primary key | Key sequence | Associated action                                                                                                                                       |
|-------------|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| P           | P            | Display the Print dialog (equivalent to the Print command). See<br>"The File Menu" (page 179).                                                          |
|             | P            | Display a dialog for specifying printing parameters (equivalent<br>to the Page Setup command). See "The File Menu" (page 179).                          |
| Q           | Q            | Quit the application (equivalent to the Quit command). See "The<br>Application Menu" (page 178).                                                        |
|             | Q            | Log out the current user (equivalent to the Log Out command).                                                                                           |
|             | Q            | Log out the current user without confirmation.                                                                                                          |
| S           | S            | Save the active document (equivalent to the Save command).<br>See "The File Menu" (page 179).                                                           |
|             | S            | Display the Save dialog (equivalent to the Save As command).<br>See "The File Menu" (page 179).                                                         |
| T           | T            | Display the Fonts window (equivalent to the Show Fonts<br>command). See "The Format Menu" (page 184).                                                   |
|             | T            | Show or hide a toolbar (equivalent to the Show/Hide Toolbar<br>command). See "The View Menu" (page 185) and<br>"Toolbars" (page 202).                   |
| U           | U            | Underline the selected text or turn underlining on or off<br>(equivalent to the Underline command). See "The Format<br>Menu" (page 184).                |
| V           | V            | Insert the Clipboard contents at the insertion point (equivalent<br>to the Paste command). See "The File Menu" (page 179).                              |
|             | V            | Apply the style of one object to the selected object (equivalent<br>to the Paste Style command). See "TheFormat Menu" (page 184).                       |
|             | V            | Apply the style of the surrounding text to the inserted object<br>(equivalent to the Paste and Match Style command). See "The<br>Edit Menu" (page 181). |
|             | V            | Apply formatting settings to the selected object (equivalent to<br>the Paste Ruler command). See "The Format Menu" (page 184).                          |
| W           | W            | Close the active window (equivalent to the Close command).<br>See "The File Menu" (page 179).                                                           |
|             | W            | Close a file and its associated windows (equivalent to the Close<br>File command). See "The File Menu" (page 179).                                      |
|             | W            | Close all windows in the application (equivalent to the Close<br>All command). See "The File Menu" (page 179).                                          |  
<span id="page-376-16"></span><span id="page-376-15"></span><span id="page-376-14"></span><span id="page-376-13"></span><span id="page-376-12"></span><span id="page-376-11"></span><span id="page-376-10"></span><span id="page-376-9"></span><span id="page-376-8"></span><span id="page-376-7"></span><span id="page-376-6"></span><span id="page-376-5"></span><span id="page-376-4"></span><span id="page-376-3"></span><span id="page-376-2"></span><span id="page-376-1"></span><span id="page-376-0"></span>  
| Primary key      | Key sequence | Associated action                                                                                                        |
|------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
| X                | X            | Remove the selection and store on the Clipboard (equivalent to<br>the Cut command). See "The Edit Menu" (page 181).      |
| Z                | Z            | Reverse the effect of the user's previous operation (equivalent<br>to the Undo command). See "The Edit Menu" (page 181). |
|                  | Z            | Reverse the effect of the last Undo command (equivalent to the<br>Redo command). See "The Edit Menu" (page 181).         |
| (right<br>arrow) |              | Change the keyboard layout to current layout of Roman script.                                                            |
|                  |              | Extend selection to the next semantic unit, typically the end of<br>the current line.                                    |
|                  |              | Extend selection one character to the right.                                                                             |
|                  |              | Extend selection to the end of the current word, then to the end<br>of the next word.                                    |
|                  |              | Move focus to another value or cell within a view, such as a<br>table. See Accessibility Overview.                       |
| (left<br>arrow)  |              | Change the keyboard layout to current layout of system script.                                                           |
|                  |              | Extend selection to the previous semantic unit, typically the<br>beginning of the current line.                          |
|                  |              | Extend selection one character to the left.                                                                              |
|                  |              | Extend selection to the beginning of the current word, then to<br>the beginning of the previous word.                    |
|                  |              | Move focus to another value or cell within a view, such as a<br>table. See Accessibility Overview.                       |
| (up<br>arrow)    |              | Extend selection upward in the next semantic unit, typicallythe<br>beginning of the document.                            |
|                  |              | Extend selection to the line above, to the nearest character<br>boundary at the same horizontal location.                |
|                  |              | Extend selection to the beginningof the current paragraph, then<br>to the beginning of the next paragraph.               |
|                  |              | Move focus to another value or cell within a view, such as a<br>table. See Accessibility Overview.                       |
| (down<br>arrow)  |              | Extend selection downward in the next semantic unit, typically<br>the end of the document.                               |  
#### **APPENDIX A**  
#### Keyboard Shortcuts Quick Reference  
<span id="page-377-1"></span><span id="page-377-0"></span>  
| Primary key | Key sequence | Associated action                                                                                                                                                                 |
|-------------|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|             |              | Extend selection to the line below, to the nearest character<br>boundary at the same horizontal location.                                                                         |
|             |              | Extend selection to the end of the current paragraph, then to the<br>end of the next paragraph (include the blank line between<br>paragraphs in cut, copy, and paste operations). |
|             |              | Move focus to another value or cell within a view, such as a<br>table. See Accessibility Overview.                                                                                |