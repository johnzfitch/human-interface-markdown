<!-- Chunk 77 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 544 -->
A Choose dialog enables the user to select an item as the target of a customized task. For example, when a user attempts to open a broken alias, the Fix Alias dialog lets the user choose another item for the alias to open. An application can have more than one Choose dialog, but only one can be open at a time.  
<span id="page-86-0"></span>**Figure 6-10** A Choose dialog  
![](images/_page_86_Picture_3.jpeg)  
#### A Choose dialog  
- can be opened by any command
- supports multiple selection
- supports document preview
- can be resized with the resize control in the lower-right corner
- can include a Show pop-up menu, which allows the user to filter the type of files that appear in the list. Items that do not meet the filtering criteria appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an "All applicable files" item, but it does not have to be the default.  
Dialog Behavior **87**  
The dialog's default title is "Choose," but you should change it to include the name of the task. For example, if the command that brings up the dialog is Choose Picture, the dialog should be titled "Choose a Picture." Also include some instructional text at the top, such as "Choose a picture to display in the background of the folder 'Documents.'" If it's helpful, also change the Choose button to something more specific.  
The default location is the user's home folder. If the dialog is targeted to only volumes, the default location is the Computer directory. Files not appropriate for the target selection are dimmed; for navigation purposes, all folders are selectable. If it's appropriate for the Choose target to be a folder, you can add a New Folder button to the Choose dialog.  
<span id="page-87-1"></span>**Note:** Recent Places (in the Where pop-up menu of a Save Location dialog) does not record folders selected in Choose dialogs.  
The Choose dialog is available to Carbon developers through the Navigation Services APIs. Cocoa developers can use a variation of the Open dialog.