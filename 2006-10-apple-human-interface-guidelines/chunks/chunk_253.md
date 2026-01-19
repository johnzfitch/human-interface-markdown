<!-- Chunk 253 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 360 -->
Use sheets for dialogs specific to a document when the user interacts with the dialog and dismisses it before proceeding with work. Some examples of when to use sheets:  
- A modal dialogfor an activitythat is specific to a particular document, such as savingor printing.
- A modal dialog that is specific to a single-window application that does not create documents. A single-windowutility program might use a sheet to request acceptance of a licensingagreement from the user, for example.
- Other window-specific dialogs that are typically dismissed by the user before proceeding. Use a sheet when a dialog benefits from being attached to the window as a modal dialog, even if you might otherwise design the dialog as a modeless dialog.  
#### **When Not to Use Sheets**  
Don't use sheets in the following situations:  
■ For dialogs that apply to several windows. Use sheets only when a particular dialog is associated with only one window.  
- For modeless operations in which the dialog should be left open to allow the user to observe the effects of changes applied. Such tasks (find and replace operations, for example) are better suited to modeless dialogs, utility windows, or drawers.
- <span id="page-209-6"></span>■ On a window that doesn't have a title bar. Sheets should emerge from a definite visual edge.
- When the user will need information in the window that is essential to filling in requested information in the sheet.