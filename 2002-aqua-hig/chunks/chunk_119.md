<!-- Chunk 119 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 427 -->
- can be opened by various commands
- can support multiple selection  
- supports document preview
- can be resized with the resize control in the lower-right corner
- can include a Show pop-up menu, which allows the user to filter the type of files that appear in the list. Items that do not meet the filtering criteria appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an "All applicable files" item, but it does not have to be the default.  
The dialog's default title is "Choose," but you should change it to include the name of the task. For example, if the command that brings up the dialog is Choose Picture, the dialog should be titled "Choose Picture." Also include some instructional text at the top, such as "Choose a picture to display in the background of the folder 'Documents.'" If it's helpful, also change the Choose button to something more specific.  
The default location is the user's home folder. If the dialog is targeted to only volumes, the default location is the Computer directory. Files and folders not appropriate for the target selection should be dimmed.  
**Note:** Recent Places (in the Where pop-up menu of a Save dialog) does not record folders selected in Choose dialogs.  
<span id="page-114-1"></span>Cocoa developers can use a variation of the Open dialog (NSOpenPanel class). The Choose dialog is available to Carbon developers through Navigation Services. For more information, see the documentation for Navigation Services, available on the Mac OS X developer documentation website.