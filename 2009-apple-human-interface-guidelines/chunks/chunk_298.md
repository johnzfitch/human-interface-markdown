<!-- Chunk 298 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 7015 -->
<span id="page-366-1"></span>Table A-1 lists the system-reserved and commonly used keyboard shortcuts mentioned in the rest of this document.  
As you implement keyboard shortcuts in your application, use this table to find:  
- Which key sequences are reserved by Mac OS X.
- Users rely on these shortcuts to perform the specified actions no matter which application is currently running (these include shortcuts reserved for accessibility purposes). *Do not override these shortcuts*.
- Which key sequences are recommended for common application tasks.
- Users expect these shortcuts to mean the same thing from application to application. Provide these shortcuts *if your application performs the associated tasks*.  
If your application does not perform the task associated with a recommended shortcut, think very carefully before you consider overriding it. Remember that although reassigning an unused shortcut might make sense in your application, your users are likely to know and expect the original, established meaning.  
If a keyboard sequence is not listed in Table A-1 you can use it for a frequently used command in your application, if a shortcut is appropriate. For guidance on creating new keyboard shortcuts,see ["Creating](#page-107-1) Your Own Keyboard [Shortcuts"](#page-107-1) (page 108) Be aware, however, that Apple may reserve other keyboard shortcuts in the future. For more information on the system-reserved keyboard shortcuts, see ["Reserved](#page-106-1) Keyboard [Shortcuts"](#page-106-1) (page 107)  
**Note:** With the exception of the system-reserved function keys F9, F10, F11, and F12, Table A-1 lists only combinations of two or more keys. For information on how to use specific single keys (such as Tab and Return), see "The [Functions](#page-99-0) of Specific Keys" (page 100)  
Table A-1 groups together the primary key that is modified and variations of key sequences based on the primary key. In the interests of space, the table uses the following symbols to represent the modifier keys (these are the same symbols menus display):  
- (Command)
- (Control)
- (Option)
- (Shift)  
Some shortcuts in Table A-1 are accompanied by an icon. This means that you should not override the shortcut because the operating system uses it in some way.  
A shortcut in Table A-1 that is not accompanied by an icon isrecommended for applicationsthat perform the associated task.  
<span id="page-367-0"></span>**Table A-1** Keyboard shortcuts  
<span id="page-367-12"></span><span id="page-367-11"></span><span id="page-367-10"></span><span id="page-367-9"></span><span id="page-367-8"></span><span id="page-367-7"></span><span id="page-367-6"></span><span id="page-367-5"></span><span id="page-367-4"></span><span id="page-367-3"></span><span id="page-367-2"></span><span id="page-367-1"></span>  
| Primary<br>key | Key sequence | Associated action                                                                                                                                              |
|----------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Space bar      | Space        | Show or hide the Spotlight search field (when multiple languages are<br>installed, may rotate through enabled script systems).                                 |
|                | Space        | Apple reserved.                                                                                                                                                |
|                | Space        | Show the Spotlight search results window (when multiple languages<br>are installed, may rotate through keyboard layouts and input methods<br>within a script). |
|                | Space        | Apple reserved.                                                                                                                                                |
| Tab            | Tab          | Navigate through controlsin a reverse direction. See "Keyboard Focus<br>and Navigation" (page 110).                                                            |
|                | Tab          | Move forward to the next most recently used application in a list of<br>open applications.                                                                     |
|                | Tab          | Move backward through a list of open applications (sorted by recent<br>use).                                                                                   |
|                | Tab          | Move focus to the next grouping of controls in a dialog or the next<br>table (when Tab moves to the next cell). See Accessibility Overview.                    |
|                | Tab          | Move focus to the previous grouping of controls. See Accessibility<br>Overview.                                                                                |
| Esc            | Esc          | Open Front Row.                                                                                                                                                |
|                | Esc          | Open the Force Quit dialog.                                                                                                                                    |
| Eject          | Eject        | Quit all applications (after giving the user a chance to save changes<br>to open documents) and restart the computer.                                          |
|                | Eject        | Quit all applications (after giving the user a chance to save changes<br>to open documents) and shut the computer down.                                        |
| F1             | F1           | Toggle full keyboard access on or off. See Accessibility Overview.                                                                                             |
| F2             | F2           | Move focus to the menu bar. See Accessibility Overview.                                                                                                        |
| F3             | F3           | Move focus to the Dock. See Accessibility Overview.                                                                                                            |
| F4             | F4           | Move focus to the active (or next) window. See Accessibility Overview.                                                                                         |
|                | F4           | Move focusto the previously active window. See AccessibilityOverview.                                                                                          |  
<span id="page-368-9"></span><span id="page-368-8"></span><span id="page-368-7"></span><span id="page-368-6"></span><span id="page-368-5"></span><span id="page-368-4"></span><span id="page-368-3"></span><span id="page-368-2"></span><span id="page-368-1"></span><span id="page-368-0"></span>  
| Primary<br>key       | Key sequence | Associated action                                                                                                    |  |
|----------------------|--------------|----------------------------------------------------------------------------------------------------------------------|--|
| F5                   | F5           | Move focus to the toolbar. See Accessibility Overview.                                                               |  |
|                      | F5           | Turn VoiceOver on or off. See Accessibility Overview.                                                                |  |
| F6                   | F6           | Move focus to the first (or next) panel. See Accessibility Overview.                                                 |  |
|                      | F6           | Move focus to the previous panel. See Accessibility Overview.                                                        |  |
| F7                   | F7           | Temporarily override the current keyboard access mode in windows<br>and dialogs. See Accessibility Overview.         |  |
| F8                   |              | Tile or untile all enabled spaces.                                                                                   |  |
| F9                   |              | Tile or untile all open windows.                                                                                     |  |
| F10                  |              | Tile or untile all open windows in the currently active application.                                                 |  |
| F11                  |              | Hide or show all open windows.                                                                                       |  |
| F12                  |              | Hide or display Dashboard.                                                                                           |  |
| `(grave<br>accent)   | `            | Activate the next open window in the frontmost application. See<br>"Window Layering" (page 222).                     |  |
|                      | `            | Activate the previous open window in the frontmost application. See<br>"Window Layering" (page 222).                 |  |
|                      | `            | Move focus to the window drawer.                                                                                     |  |
| - (hyphen)           | -            | Decrease the size of the selected item (equivalent to the Smaller<br>command). See "The Format Menu" (page 183).     |  |
|                      | -            | Zoom out when screen zooming is on. See Accessibility Overview.                                                      |  |
| { (left<br>bracket)  | {            | Left-align a selection (equivalent to the Align Left command). See "The<br>Format Menu" (page 183).                  |  |
| } (right<br>bracket) | }            | Right-align a selection (equivalent to the Align Right command). See<br>"The Format Menu" (page 183).                |  |
| (pipe)               |              | Center-align a selection (equivalent to the Align Center command).<br>See "The Format Menu" (page 183).              |  |
| : (colon)            | :            | Display the Spelling window (equivalent to the Spelling command).<br>See "The Edit Menu" (page 181).                 |  |
| ;<br>(semicolon)     | ;            | Find misspelled words in the document (equivalent to the Check<br>Spelling command). See "The Edit Menu" (page 181). |  |  
<span id="page-369-9"></span><span id="page-369-8"></span><span id="page-369-7"></span><span id="page-369-6"></span><span id="page-369-5"></span><span id="page-369-4"></span><span id="page-369-3"></span><span id="page-369-2"></span><span id="page-369-1"></span><span id="page-369-0"></span>  
| Primary<br>key       | Key sequence | Associated action                                                                                                                                             |
|----------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| , (comma)            | ,            | Open the application's preferences window (equivalent to the<br>Preferences command). See "The Application Menu" (page 177).                                  |
|                      | ,            | Decrease screen contrast. See Accessibility Overview.                                                                                                         |
| . (period)           |              | Increase screen contrast. See Accessibility Overview.                                                                                                         |
| ? (question<br>mark) | ?            | Open the application's help in Help Viewer. See "The Help Menu" (page<br>187).                                                                                |
| / (forward<br>slash) | /            | Turn font smoothing on or off.                                                                                                                                |
| = (equal<br>sign)    | =            | Increase the size of the selected item (equivalent to the Bigger<br>command). See "The Format Menu" (page 183).                                               |
|                      | =            | Zoom in when screen zooming is on. See Accessibility Overview.                                                                                                |
| 3                    | 3            | Capture the screen to a file.                                                                                                                                 |
|                      | 3            | Capture the screen to the Clipboard.                                                                                                                          |
| 4                    | 4            | Capture a selection to a file.                                                                                                                                |
|                      | 4            | Capture a selection to the Clipboard.                                                                                                                         |
| 8                    | 8            | Turn screen zooming on or off. See Accessibility Overview.                                                                                                    |
|                      | 8            | Invert the screen colors. See Accessibility Overview.                                                                                                         |
| A                    | A            | Highlight every item in a document or window, or all characters in a<br>text field (equivalent to the Select All command). See "The Edit<br>Menu" (page 181). |
| B                    | B            | Boldface the selected text or toggle boldfaced text on and off<br>(equivalent to the Bold command). See "The Edit Menu" (page 181).                           |
| C                    | C            | Duplicate the selected data and store on the Clipboard (equivalent to<br>the Copy command). See "The Edit Menu" (page 181).                                   |
|                      | C            | Display the Colors window (equivalent to the Show Colors command).<br>See "The Format Menu" (page 183).                                                       |
|                      | C            | Copy the style of the selected text (equivalent to the Copy Style<br>command). See "The Format Menu" (page 183).                                              |  
<span id="page-370-16"></span><span id="page-370-15"></span><span id="page-370-14"></span><span id="page-370-13"></span><span id="page-370-12"></span><span id="page-370-11"></span><span id="page-370-10"></span><span id="page-370-9"></span><span id="page-370-8"></span><span id="page-370-7"></span><span id="page-370-6"></span><span id="page-370-5"></span><span id="page-370-4"></span><span id="page-370-3"></span><span id="page-370-2"></span><span id="page-370-1"></span><span id="page-370-0"></span>  
| Primary<br>key | Key sequence | Associated action                                                                                                                                            |
|----------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                | C            | Copy the formatting settings of the selected item and store on the<br>Clipboard (equivalent to the Copy Ruler command). See "The Format<br>Menu" (page 183). |
| D              | D            | Show or hide the Dock. See "The Dock" (page 62).                                                                                                             |
|                | D            | Display the definition of the selected word in the Dictionary<br>application.                                                                                |
| E              | E            | Use the selection for a find operation. See "Find Windows" (page 243).                                                                                       |
| F              | F            | Open a Find window (equivalent to the Find command). See "The Edit<br>Menu" (page 181).                                                                      |
|                | F            | Jump to the search field control. See "Search Fields" (page 326).                                                                                            |
| G              | G            | Find the next occurrence of the selection (equivalent to the Find Next<br>command). See "The Edit Menu" (page 181).                                          |
|                | G            | Find the previous occurrence of the selection (equivalent to the Find<br>Previous command). See "The Edit Menu" (page 181).                                  |
| H              | H            | Hide the windows of the currently running application (equivalent to<br>the Hide ApplicationName command). See "The Application<br>Menu" (page 177).         |
|                | H            | Hide the windows of all other running applications (equivalent to the<br>Hide Others command). See "The Application Menu" (page 177).                        |
| I              | I            | Italicize the selected text or toggle italic text on or off (equivalent to<br>the Italic command). See "The Format Menu" (page 183).                         |
|                | I            | Display an Info window. See "Inspector Windows" (page 229).                                                                                                  |
|                | I            | Display an inspector window. See "Inspector Windows" (page 229).                                                                                             |
| J              | J            | Scroll to a selection.                                                                                                                                       |
| M              | M            | Minimize the active window to the Dock (equivalent to the Minimize<br>command). See "The Window Menu" (page 186).                                            |
|                | M            | Minimize all windows of the active application to the Dock (equivalent<br>to the Minimize All command). See "The Window Menu" (page 186).                    |
| N              | N            | Open a new document (equivalent to the New command). See "The<br>File Menu" (page 179).                                                                      |
| O              | O            | Display a dialog for choosing a document to open (equivalent to the<br>Open command). See "The File Menu" (page 179).                                        |
| P              | P            | Display the Print dialog (equivalent to the Print command). See "The<br>File Menu" (page 179).                                                               |  
<span id="page-371-14"></span><span id="page-371-13"></span><span id="page-371-12"></span><span id="page-371-11"></span><span id="page-371-10"></span><span id="page-371-9"></span><span id="page-371-8"></span><span id="page-371-7"></span><span id="page-371-6"></span><span id="page-371-5"></span><span id="page-371-4"></span><span id="page-371-3"></span><span id="page-371-2"></span><span id="page-371-1"></span><span id="page-371-0"></span>  
| Primary<br>key | Key sequence | Associated action                                                                                                                                       |
|----------------|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
|                | P            | Display a dialog for specifying printing parameters (equivalent to the<br>Page Setup command). See "The File Menu" (page 179).                          |
| Q              | Q            | Quit the application (equivalent to the Quit command). See "The<br>Application Menu" (page 177).                                                        |
|                | Q            | Log out the current user (equivalent to the Log Out command).                                                                                           |
|                | Q            | Log out the current user without confirmation.                                                                                                          |
| S              | S            | Save the active document (equivalent to the Save command). See<br>"The File Menu" (page 179).                                                           |
|                | S            | Display the Save dialog (equivalent to the Save As command). See<br>"The File Menu" (page 179).                                                         |
| T              | T            | Display the Fonts window (equivalent to the Show Fonts command).<br>See "The Format Menu" (page 183).                                                   |
|                | T            | Show or hide a toolbar (equivalent to the Show/Hide Toolbar<br>command). See "The View Menu" (page 184) and "Toolbars" (page 200).                      |
| U              | U            | Underline the selected text or turn underlining on or off (equivalent<br>to the Underline command). See "The Format Menu" (page 183).                   |
| V              | V            | Insert the Clipboard contents at the insertion point (equivalent to the<br>Paste command). See "The File Menu" (page 179).                              |
|                | V            | Apply the style of one object to the selected object (equivalent to the<br>Paste Style command). See "The Format Menu" (page 183).                      |
|                | V            | Apply the style of the surrounding text to the inserted object<br>(equivalent to the Paste and Match Style command). See "The Edit<br>Menu" (page 181). |
|                | V            | Apply formatting settings to the selected object (equivalent to the<br>Paste Ruler command). See "The Format Menu" (page 183).                          |
| W              | W            | Close the active window (equivalent to the Close command). See "The<br>File Menu" (page 179).                                                           |
|                | W            | Close a file and its associated windows (equivalent to the Close File<br>command). See "The File Menu" (page 179).                                      |
|                | W            | Close all windows in the application (equivalent to the Close All<br>command). See "The File Menu" (page 179).                                          |
| X              | X            | Remove the selection and store on the Clipboard (equivalent to the<br>Cut command). See "The Edit Menu" (page 181).                                     |  
<span id="page-372-16"></span><span id="page-372-15"></span><span id="page-372-14"></span><span id="page-372-13"></span><span id="page-372-12"></span><span id="page-372-11"></span><span id="page-372-10"></span><span id="page-372-9"></span><span id="page-372-8"></span><span id="page-372-7"></span><span id="page-372-6"></span><span id="page-372-5"></span><span id="page-372-4"></span><span id="page-372-3"></span><span id="page-372-2"></span><span id="page-372-1"></span><span id="page-372-0"></span>  
| Primary<br>key   | Key sequence | Associated action                                                                                                        |
|------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
| Z                | Z            | Reverse the effect of the user's previous operation (equivalent to the<br>Undo command). See "The Edit Menu" (page 181). |
|                  | Z            | Reverse the effect of the last Undo command (equivalent to the Redo<br>command). See "The Edit Menu" (page 181).         |
| (right<br>arrow) |              | Change the keyboard layout to current layout of Roman script.                                                            |
|                  |              | Extend selection to the next semantic unit, typically the end of the<br>current line.                                    |
|                  |              | Extend selection one character to the right.                                                                             |
|                  |              | Extend selection to the end of the current word, then to the end of<br>the next word.                                    |
|                  |              | Move focus to another value or cell within a view, such as a table. See<br>Accessibility Overview.                       |
| (left<br>arrow)  |              | Change the keyboard layout to current layout of system script.                                                           |
|                  |              | Extend selection to the previoussemantic unit, typically the beginning<br>of the current line.                           |
|                  |              | Extend selection one character to the left.                                                                              |
|                  |              | Extend selection to the beginning of the current word, then to the<br>beginning of the previous word.                    |
|                  |              | Move focus to another value or cell within a view, such as a table. See<br>Accessibility Overview.                       |
| (up<br>arrow)    |              | Extend selection upward in the next semantic unit, typically the<br>beginning of the document.                           |
|                  |              | Extend selection to the line above, to the nearest character boundary<br>at the same horizontal location.                |
|                  |              | Extend selection to the beginning of the current paragraph, then to<br>the beginning of the next paragraph.              |
|                  |              | Move focus to another value or cell within a view, such as a table. See<br>Accessibility Overview.                       |
| (down<br>arrow)  |              | Extend selection downward in the next semantic unit, typically the<br>end of the document.                               |
|                  |              | Extend selection to the line below, to the nearest character boundary<br>at the same horizontal location.                |  
<span id="page-373-0"></span>  
| Primary<br>key | Key sequence | Associated action                                                                                                                                                                         |
|----------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                |              | Extend selection to the end of the current paragraph, then to the end<br>of the next paragraph (include the paragraph terminator, such as<br>Return, in cut, copy, and paste operations). |
|                |              | Move focus to another value or cell within a view, such as a table. See<br>Accessibility Overview.                                                                                        |