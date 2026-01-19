<!-- Chunk 194 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1443 -->
<span id="page-180-2"></span>The **Edit menu** provides commands that allow people to change (edit) the contents of documents and other text containers, such as fields. It also provides the commands that allow people to share data, within and between applications, via the Clipboard.  
<span id="page-180-1"></span>The **Clipboard** stores whatever data is cut or copied from a document until the user replaces the contents by cutting or copying new data. The Clipboard is available to all applications, and its contents don't change when the user switches from one application to another. The Clipboard provides excellent support for the exchange of different data types between applications. Your application should maintain formatting when it copies text to the Clipboard.  
**Figure 13-17** The Edit menu  
![](images/_page_180_Picture_11.jpeg)  
Your application's Edit menu should provide the following commands. Even if your application doesn't handle text editing within its documents, these commandsshould be available for use in dialogs and wherever users can edit text:  
<span id="page-181-8"></span>**Undo (Command-Z).** The Undo command reverses the effect of the user's previous operation.  
Support the Undo command for:  
- Operations that change the contents of a document
- Operations that require a lot of effort to re-create
- Most menu items
- Most keyboard input  
Operations that may not be undoable include:  
- Selecting
- Scrolling
- Splitting a window
- Changing a window's size or location  
<span id="page-181-0"></span>Add the name of the last operation to the Undo command. If the last operation was a menu command, add the command name. For example, if the user hasjust inputsome text, the command could read Undo Typing; if the user has chosen the Paste command, the Undo command should read Undo Paste. If the last operation can't be reversed, change the command to Can't Undo and display it dimmed to provide feedback about the current state.  
<span id="page-181-5"></span>If a user attempts to perform an operation that could have a detrimental effect on data and that can't be undone, warn the user (see ["Alerts"](#page-236-0) (page 237)).  
<span id="page-181-7"></span>**Redo (Command-Shift-Z).** The Redo command reverses the effect of the last Undo command. Add the name of the last undone operation to the Redo command.  
<span id="page-181-3"></span>**Cut (Command-X).** Removes the selected data and stores it on the Clipboard, replacing the previous contents of the Clipboard.  
<span id="page-181-6"></span><span id="page-181-4"></span>**Copy (Command-C).** Makes a duplicate of the selected data, which is stored on the Clipboard.  
**Paste (Command-V).** Inserts the Clipboard contents at the insertion point. The Clipboard contents remain unchanged, permitting the user to choose Paste multiple times.  
<span id="page-181-1"></span>**Paste and Match Style (Command-Option-Shift-V).** In text-editing applications, insertsthe Clipboard contents at the insertion point and matches the style of the inserted text to the surrounding text. If your application provides several text-formatting commands, you might choose to group them in a Format menu instead of listing them in the Edit menu (see "The [Format](#page-182-0) Menu" (page 183)).  
<span id="page-181-2"></span>**Delete.** Removes selected data without storing the selection on the Clipboard. Choosing Delete is the equivalent of pressing the Delete key or the Clear key. Use Delete as the menu command, rather than Clear.  
**Select All (Command-A).** Highlights every object in the document or window, or all characters in a text field.  
<span id="page-182-2"></span>**Find… (Command-F).** Opens an interface for finding items. This command could be in the File menu instead if the object of the search is files—for example, if the application is finding a file on the Internet. When appropriate, your application should also contain a Find/Replace command. "Find [Windows"](#page-242-0) (page 243) shows an example of a typical Find window for searching text.  
If your application provides multiple find-related commands, you may want to include a Find submenu. A Find submenu commonly contains Find (Command-F), Find Next (Command-G), Find Previous (Command-Shift-G), Use Selection for Find (Command-E), and Jump to Selection (Command-J). If you include a Find submenu, the Find command is not followed by an ellipsis character.  
<span id="page-182-7"></span><span id="page-182-3"></span>**Find Next (Command-G).** Performs the last Find operation again. This item should be grouped with the Find command in either the File or Edit menu.  
**Spelling… (Command-:)**. In applications that support text-editing, performs a spell-check of the selected text and opens an interface in which users can correct the spelling, view suggested spellings, and find other misspelled words.  
If your application provides multiple spelling-related commands, you may want to include a Spelling submenu. A Spelling submenu typically contains Check Spelling (Command-;) and Check Spelling as You Type commands. If you include a Spelling submenu, the Spelling command is not followed by an ellipsis character.  
<span id="page-182-6"></span>**Speech.** Displays a submenu containing the Start Speaking and Stop Speaking commands. If your application displays text, you can provide the Speech menu item to allow users to listen to the text spoken aloud by the system.  
<span id="page-182-10"></span><span id="page-182-0"></span>**Special Characters…** Displays the Special Characters window, which allows users to input characters from any character set supported by Mac OS X into text entry fields. This menu item is automatically inserted at the bottom of the Edit menu.