<!-- Chunk 66 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 901 -->
The **Edit menu** provides commands that allow people to change, or edit, the contents of documents. It also provides the commands that allow people to share data, within and between applications, via the Clipboard.  
<span id="page-57-5"></span>The **Clipboard** stores whatever data is cut or copied from a document until the user replaces the contents by cutting or copying new data. The Clipboard is available to all applications and its contents don't change when the user switches from one application to another.  
<span id="page-57-1"></span>**Figure 4-10** The Edit menu  
![](images/_page_57_Picture_7.jpeg)  
Your application's Edit menu should provide the following commands. Even if your application doesn't handle text editing within its documents, these commands should be available for use in dialogs:  
<span id="page-57-4"></span>■ **Undo:** The Undo command reverses the effect of the user's previous operation. When the user chooses Undo, the command changes to **Redo,** which reverses the effect of the last Undo command.  
<span id="page-57-3"></span>Support the Undo command for  
| ■ | operations that change the contents of a document   |
|---|-----------------------------------------------------|
| ■ | operations that require a lot of effort to recreate |
| ■ | most menu items                                     |
| ■ | most keyboard input                                 |
|   | Operations that may not be undoable include         |
| ■ | selecting                                           |
| ■ | scrolling                                           |
| ■ | splitting a window                                  |
| ■ | changing a window's size or location                |  
Add the name of the last operation to the Undo and Redo commands. For example, if the user has just input some text, the command could read **Undo Typing.** If the last operation can't be reversed, change the command to **Can't Undo** and display it dimmed to provide feedback about the current state.  
<span id="page-58-6"></span>If a user attempts to perform an operation that could have a detrimental effect on data and that can't be undone, warn the user. See ["Alerts" \(page 95\).](#page-94-1)  
<span id="page-58-7"></span><span id="page-58-4"></span>Command-Z should be reserved as a keyboard equivalent for the Undo/Redo command.  
- **Cut:** Removes the selected data and stores it on the Clipboard, replacing the previous contents of the Clipboard.
- Command-X should be reserved as a keyboard equivalent for the Cut command.
- <span id="page-58-3"></span>■ **Copy:** Makes a duplicate of the selected data, which is stored on the Clipboard. Command-C should be reserved as the keyboard equivalent for the Copy command.
- **Paste:** Inserts the Clipboard contents at the insertion point. The Clipboard content remains unchanged, permitting the user to choose Paste multiple times. Command-V should be reserved as the keyboard equivalent for the Paste
- **Delete:** Removes selected data without storing the selection on the Clipboard. Choosing Delete is the equivalent of pressing the Delete key or the Clear key.
- **Select All:** Highlights every object in the document.  
<span id="page-58-2"></span><span id="page-58-1"></span>Command-A should be reserved as the keyboard equivalent for the Select All command.  
<span id="page-58-5"></span><span id="page-58-0"></span>command.  
<span id="page-59-4"></span>■ **Find:** Finds specified text. In some cases—if the application is finding a file on the Internet, for example—it might make more sense to put this command in the File menu.