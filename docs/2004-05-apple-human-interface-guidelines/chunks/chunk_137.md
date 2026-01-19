<!-- Chunk 137 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 672 -->
<span id="page-140-6"></span><span id="page-140-3"></span>The Open dialog appears when the user chooses the Open command or presses Command-O. The Open dialog is application modal (the user can switch to other applications).  
<span id="page-140-2"></span><span id="page-140-1"></span>If you implement an Open command, you should also include an Open Recent command so users can open recently opened documents without going through the dialog.  
**Figure 9-8** An Open dialog  
![](images/_page_140_Picture_8.jpeg)  
The Open dialog contains these elements:  
- A default title ("Open"); you should add your application's name to the Open dialog title—"TextEdit: Open," for example.
- Back and forward buttons to navigate back and forth between selections made in list or column view.  
- A pop-up menu that contains common places a user might save things and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically one of the predefined folders in the user's home folder. (For recommended default locations, see *Apple Software Design Guidelines*.) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- A sidebar that mirrors the one presented in the Finder.
- A column or list view for navigating the file system.
- A Cancel button and an Open (default) button.
- A resize control in the lower-right corner.
- Expert users can specify a pathname by pressing Command-Shift-G.  
<span id="page-141-1"></span><span id="page-141-0"></span>You can extend the Open dialog as appropriate for your application as illustrated in Figure 9-9. You might, for example, include a pop-up menu allowing users to filter the type of files that appear in the list. Items that do not meet the filtering criteria would appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an All Applicable Files item, but it does not have to be the default.  
**Figure 9-9** A customized Open dialog  
![](images/_page_141_Picture_10.jpeg)  
Open dialogs should support document preview and can support multiple selection if your application allows more than one document to be open at a time.  
**Carbon:** See *Navigation Services for Carbon: An Overview* in Carbon User Experience Documentation.  
**Cocoa:** Open dialogs are NSOpenPanels. You typically display an Open dialog by invoking the openPanel method. See *Application File Management* in Cocoa File Management Documentation.