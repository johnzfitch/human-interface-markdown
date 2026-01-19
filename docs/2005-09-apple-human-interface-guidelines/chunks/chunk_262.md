<!-- Chunk 262 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 552 -->
A Choose dialog lets a user select an item as the target of a task. For example, when a user attempts to open a broken alias, the Fix Alias dialog lets the user choose another item for the alias to open. An application can have more than one Choose dialog, but only one can be open at a time. In some situations, it may be appropriate for a Choose dialog to be a sheet.  
<span id="page-216-0"></span>**Figure 13-45** A Choose dialog  
![](images/_page_216_Picture_3.jpeg)  
#### A Choose dialog:  
- Can be opened by various commands
- Can support multiple selection
- <span id="page-216-1"></span>■ Supports document preview
- Can be resized with the resize control in the lower-right corner
- Can include a Show pop-up menu, which allows the user to filter the type of files that appear in the list. Items that do not meet the filtering criteria appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this listwith custom types and specifythe default to showwhen the dialogopens. You should include an All Applicable Files item, but it does not have to be the default.  
If the dialog is not a sheet, the dialog's default title is "Choose," but you should change it to include the name of the task. For example, if the command that brings up the dialog is Choose Picture, the dialog should be titled "Choose Picture." Also include some instructional text at the top, such as "Choose a picture to displayin the background of 'Documents.'" If it's helpful, also change the Choose button to something more specific.  
The default location is the user's home folder. If the dialog is targeted to volumes only, the default location is the user's directory. Files and folders not appropriate for the target selection should be dimmed.  
**Note:** Recent Places (in the Where pop-up menu of a Save dialog) does not record folders selected in Choose dialogs.  
<span id="page-217-2"></span>**Carbon:** The Choose dialog is available through Navigation Services. For more information, see the documentation for Navigation Services in Carbon User Experience Documentation.  
**Cocoa:** Use a variation of the Open dialog (NSOpenPanel class).