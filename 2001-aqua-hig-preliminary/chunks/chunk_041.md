<!-- Chunk 41 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 880 -->
The **Edit menu** provides commands that allow people to change, or edit, the contents of documents. It also provides the commands that allow people to share data, within and between applications, via the Clipboard.  
The **Clipboard** stores whatever data is cut or copied from a document until the user replaces the contents by cutting or copying new data. The Clipboard is available to all applications and its contents don't change when the user switches from one application to another.  
Your application's Edit menu should provide the following commands. Even if your application doesn't handle text editing within its documents, these commands should be available for use in modal dialogs (such as Save As):  
■ **Undo:** The Undo command reverses the effect of the user's previous operation. When the user chooses Undo, the command changes to **Redo,** which reverses the effect of the last Undo command. Most Carbon applications have only one level of undo.  
|   | Support the Undo command for                        |
|---|-----------------------------------------------------|
| ■ | operations that change the contents of a document   |
| ■ | operations that require a lot of effort to recreate |
| ■ | most menu items                                     |
| ■ | most keyboard input                                 |
|   | Operations that may not be undoable include         |
| ■ | selecting                                           |
| ■ | scrolling                                           |
| ■ | splitting a window                                  |
| ■ | changing a window's size or location                |
|   |                                                     |  
Add the name of the last operation to the Undo and Redo commands. For example, if the user has just input some text, the command could read **Undo Typing.** If the last operation can't be reversed, change the command to **Can't Undo** and display it dimmed to provide feedback about the current state.  
If a user attempts to perform an operation that could have a detrimental effect on data and that can't be undone, warn the user. See ["Alerts" \(page 75\).](#page-74-0)  
<span id="page-45-9"></span><span id="page-45-8"></span><span id="page-45-6"></span>Command-Z should be reserved as a keyboard equivalent for the Undo/Redo command.  
- **Cut:** Removes the selected data and stores it on the Clipboard, replacing its previous contents.
- Command-X should be reserved as a keyboard equivalent for the Cut command.
- <span id="page-45-5"></span>■ **Copy:** Makes a duplicate of the selected data, which is stored on the Clipboard. Command-C should be reserved as a keyboard equivalent for the Copy command.
- <span id="page-45-7"></span>■ **Paste:** Inserts the Clipboard contents at the insertion point location. The Clipboard content remains unchanged, permitting the user to choose Paste multiple times.
- Command-V should be reserved as a keyboard equivalent for the Paste command.
- <span id="page-45-2"></span>■ **Clear:** Removes selected data without storing the selection on the Clipboard. Choosing Clear is the equivalent of pressing the Delete key.
- <span id="page-45-4"></span><span id="page-45-3"></span>■ **Select All:** Highlights every object in the document.
- Command-A should be reserved as a keyboard equivalent for the Select All command.
- **Find:** Finds specified text. In some cases—if the application is finding a file on the Internet—it might make more sense to put this command in the File menu.