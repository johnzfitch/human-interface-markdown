---
chunk_index: 2293
ref: "2ae3498b4b94"
id: "2ae3498b4b94651319c5b82581a7f1cf1c6648ca70f33224efa523b315d6e68e"
slug: "chunk-105--undo-redo"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_105.md"
kind: "markdown"
lines: [25, 36]
token_estimate: 954
content_sha256: "9d8ad25c02246f094e1d344e87d6467232ddb7a0b66162d9dfcb24a400b114fc"
compacted: false
heading_path: ["The Clipboard","Undo/Redo"]
symbol: null
address: null
asset_path: null
---

#### Undo/Redo  
The Undo command reverses the effect of the user's previous operation. The Redo command reverses the effect of the last Undo command. Undo and Redo are a single toggled item. In most applications, there is one level of undo operations. The application determines which operations can be undone. Simple operations require your application to store a minimal amount of information about the previous state of the data in order to implement the Undo command. For example, if a user cuts one word from a document, you only need to store the size, the location, the content, and the style of the data. For operations that require you to store the entire state of the document in order to implement the Undo command, it may be more difficult to implement. You should consider the needs of your audience when making difficult decisions about which operations support the Undo command. Remember that your application must be able to redo every undo operation.  
In general, support the Undo command for operations that *change the user's contents* of a document. It's nice, but not necessary, to support the Undo command for operations that *don't change the user's contents* of a document. Actions that take a lot of effort to recreate are probably those that a user would most expect to be able to undo. For example, a user might spend several minutes arranging windows on a screen in a specific layout. If that user then accidentally chose the Tile command, the user would expect to be able to recover the original layout by using the Undo command.  
Most menu items, regardless of how the user invokes them, should be undoable. Most keyboard input, any sequence of characters typed from the keyboard or numeric keypad, including Delete (Backspace), Return, and Tab should also be undoable.  
Operations that may not be undoable include selecting, scrolling, splitting the window, or changing a window's size or location. None of these operations interrupts a typing sequence. For example, if the user types a few characters and then scrolls the document, the Undo operation doesn't undo the scrolling but does undo the typing. Whenever the location affected by the Undo command isn't currently showing on the screen, your application should scroll the document so the user can see the effect of the Undo command.  
You should add the name of the last operation to the Undo command. For example, it could read Undo Typing if the user just finished entering some text in a document. If the last operation can't be undone, you should use the phrase Can't Undo and display it dimmed, because it provides more feedback to the user about the current state. The Undo command changes to Redo after the user chooses Undo. You should also include the operation name in the Redo string when possible. If the user chooses Redo, reverse the undo operation.  
Figure 4-77 shows an example of the Edit menu with correctly updated Undo and Redo commands.  
**Figure 4-77** The Undo and Redo commands  
![](images/_page_137_Picture_4.jpeg)  
![](images/_page_137_Picture_5.jpeg)  
If a user is about to complete an operation that could have a deleterious effect on data and that can't be undone, you should warn the user. For example, if a user is about to destroy a lot of data by replacing every fifth word with a space, display an alert box that says something to the effect of, "You are about to change a lot of your document. You can't undo this operation." The buttons should be labeled Replace and Cancel. If the user is about to make a change that affects only the environment, such as changing a window location, then it's not necessary to display a warning.  
The Command-Z combination is reserved as a keyboard equivalent for the Undo/Redo command in the Edit menu. It shouldn't be used for any other purpose.