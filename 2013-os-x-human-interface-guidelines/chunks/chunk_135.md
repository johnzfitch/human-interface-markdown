<!-- Chunk 135 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 5501 -->
Users expect all the buttons at the bottom right of a dialog to dismiss the dialog. A button that initiates an action is furthest to the right. This rightmost button, called the **action button**, confirms the main point of the dialog. The Cancel button is to the left of the action button.  
Usually the rightmost button or the Cancel button is the **default button**. A default button has color and pulses to let the user know that when they press Return or Enter, the default button is activated.  
![](images/_page_215_Picture_9.jpeg)  
Follow the guidelines in this section to ensure that your dialogs look and behave as users expect.  
**Use a default button only if the user's most likely action is harmless.** The default button should represent the action that the user is most likely to perform *if* that action isn't potentially dangerous. Users sometimes press Return merely to dismiss a dialog, without taking the time to read its content, so it's crucial to ensure that the default button performs a harmless action.  
**Don't use a default button at all if the user's most likely action is dangerous**—for example, if it causes a loss of user data. When there is no default button, pressing Return or Enter has no effect; the user must explicitly click a button to dismiss the dialog. This guideline protects users from accidentally damaging their work by pressing Return or Enter without fully understanding the dialog's message. You can consider using a safe default button, such as Cancel, or not using a default button at all.  
**Don't use a default button if you use the Return key in the dialog's text fields.** Having two behaviors for one key can confuse users and make the interface less predictable. Also, users might press Return one too many times and dismiss the dialog (and activate the default button) without meaning to.  
**In general, include a Cancel button.** The Cancel button returns the computer to the state it was in before the dialog appeared. It means"forget I mentioned it." Also, make sure that the keyboard shortcut Command-period and the Esc (Escape) key are mapped to the Cancel button.  
**Ensure that Cancel undoes applied changes.** If your dialog incudes an Apply button that helps users see the effect of changes before committing to them, make sure that clicking Cancel undoes all of the applied changes. Cancel should never silently commit the changes the user previewed by clicking Apply. For more guidelines on using an Apply button, see ["Accepting](#page-213-0) and Applying User Input in a Dialog" (page 214).  
**Place a third button for dismissing the dialog to the left of the Cancel button.** If the third button could result in data loss—Don't Save, for example—try to position it at least 24 points away from the "safe" buttons (Cancel and Save, for example).  
**Place a button that affects the contents of the dialog itself in the left end of the dialog.** If there is no Help button, such a button should have its left edge aligned with the main dialog text; if there is a Help button, it should be placed to the right of the Help button. For example, the Help button isto the left of the Show Details button in the Print dialog, which expands the dialog to display more information about the print job.  
![](images/_page_216_Picture_7.jpeg)  
#### <span id="page-216-0"></span>Preferences Windows  
A preferences window is a modeless dialog that contains settings the user changes infrequently. In general, the user opens a preferences window to change the default way an app displays an item or performs a task, then closes the window, and expects the new settings to have taken effect. (For some guidance on how to provide a good preferences experience in your app, see ["Preferences"](#page-91-0) (page 92).)  
Often, a preferences window has a toolbar that contains items that function as pane switchers. When the user clicks an item in this type of toolbar, the content area of the preferences window switches to display a different view, called a **pane**. This design is useful for apps that need to provide multiple settings in each of several different categories. For example, the Safari preferences window contains a toolbar that allows user to choose among categories of settings, such as bookmarks, appearance, and RSS.  
![](images/_page_217_Picture_2.jpeg)  
**Don't enable customization of a pane-switcher toolbar in a preferences window.** A pane-switcher toolbar in a preferences window does not provide a shortcut to frequently used commands, but instead acts as a convenient way to group settings. If users customize thistype of toolbar, they might forget that hidden settings are still available. For the same reason, it makes sense to disable the ability to hide the toolbar in a preferences window, too.  
**Maintain the selected appearance of an item in a pane-switcher toolbar.** When the user clicks an item in a pane-switcher toolbar, the window displays a different pane. It's important to indicate which item is currently selected by maintaining the item's selected appearance. For example, in the Safari preferences window, you can see the background highlighting that indicates the Tabs item is the active one.  
![](images/_page_218_Picture_2.jpeg)  
**Don't allow resizing or include active minimize or zoom buttons in a preferences window.** Remember that preferences windows are intended to give users a place to make occasional adjustments to the way an app behaves, so there should be no need for a preferences window to be resized or to remain open for a long time.  
**Use the title of the current pane to title the preferences window.** The preferences window title should be the same as the title of the currently selected pane even if you don't use a pane-switcher toolbar to change panes. (Note that if your preferences window does not contain multiple panes, its title should be "*App Name* Preferences".) In addition, a changeable-pane preferences window should remember which pane the user selected the last time the window was open.  
<span id="page-218-0"></span>**Use the standard menu item and keyboard shortcut to open your preferences window.** Users expect most apps to include a Preferences command in the app menu. In addition, most users expect to be able to use the Command-comma keyboard shortcut to open an app's preferences window.  
#### The Open Dialog  
The Open dialog gives users a consistent way to find and open an item in an app. Its appearance varies slightly depending on whether the app uses the iCloud Open dialog.  
If your app is document based and iCloud enabled, it has an iCloud Open dialog that opens in its own window. Other apps have an Open dialog that is app modal, which means that users can't interact with the app until they dismiss the dialog, although they can switch to other apps.  
The iCloud Open dialog contains these elements:  
- In the title bar: Tabs for iCloud and On My Mac, the app's title—for example, "Preview"—and a search field
- In the bottom bar: Thumbnail and list options for navigating the file system, Share and Tags menus, and Done and Open buttons  
You can see most of the required elements in the iCloud Open dialog for Preview in iCloud.  
![](images/_page_219_Picture_6.jpeg)  
The On My Mac tab replaces the window body contents with a source list that mirrors the Finder sidebar as shown here:  
![](images/_page_220_Picture_2.jpeg)  
The Open dialog for non-document-based apps contains these elements:  
- The title, "Open"
- In the tool bar: Back and forward buttons, different views for navigating the file system, a pop-up menu that contains common places a user might save things and Recent Places (the five most recent folders the user opened or saved documents to), and a search field
- In the window body: A source list that mirrors the Finder sidebar
- In the bottom bar: Cancel and Open buttons (the Open button is the default button)
- The ability for expert users to specify a pathname by pressing Command-Shift-G (note that the pathname separator is the slash (/) character)  
You can see most of the required elements in the Open File dialog for Safari.  
![](images/_page_221_Figure_2.jpeg)  
You can extend the Open dialog as appropriate for your app. For example, the TextEdit Open dialog contains an additional section that allows users to specify different encodings.  
![](images/_page_222_Picture_2.jpeg)  
The following guidelines help you use and customize an Open dialog appropriately.  
**As much as possible, use the Open command to mean "open," and not "act upon."** The Open dialog is best suited to help usersfind an item to open in your app. If you need to help usersfind itemsto use in an app-specific task, it's generally better to use a Choose dialog instead (for guidance on using a Choose dialog, see ["The](#page-223-0) [Choose](#page-223-0) Dialog" (page 224)).  
**Make sure users can use the Open command to display the Open dialog.** Users expect the Open command to display an Open dialog. Contrast this with the Choose dialog, which can be displayed by different commands in different apps. It's also a good idea to provide the standard Command-O keyboard shortcut to display the Open dialog, because most users are accustomed to it.  
**Specify a reasonable default location.** For the iCloud Open dialog, iCloud is the default location. You should not change this behavior. See "iCloud [Storage"](#page-70-1) (page 71) for more information.  
Otherwise, the default location is typically one of the predefined folders in the user's home folder. If the user selects a different folder, make sure you remember the user's selection so that it appears the next time the dialog is displayed.  
**Considerincluding a pop-up menu that allows users to filterthe types of files that appearin the list.** Display items that don't meet the filtering criteria as dimmed. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an All Applicable Files item, but it does not have to be the default item.  
**Include an Open Recent command to accompany the Open command.** The Open Recent command allows users to reopen recently opened documents without using the Open dialog.  
**Extend the functionality oftheOpen dialog, if appropriate.** For example, it's a good idea to support document preview so that users can be sure they're opening the document they intend. In addition, you can enable multiple selection if your app allows more than one document to be opened at one time.  
#### <span id="page-223-0"></span>The Choose Dialog  
A Choose dialog gives users a consistent way to select an item as the target of a task. An app can have more than one Choose dialog, but only one can be open at a time.  
#### A Choose dialog:  
- Can be opened by various commands
- Can support multiple selection
- Supports document preview
- Can be resized  
For example, Calendar displays a choose dialog that allows users to choose a calendar to import.  
![](images/_page_224_Picture_2.jpeg)  
**Note:** Recent Places doesn't record folders that users select in Choose dialogs.  
The following guidelines help you use a Choose dialog appropriately in your app.  
**Use a sheet for the Choose dialog when the chosen items are specific to the document.** For example, Mail displays a Choose dialog in a sheet to help users to find items to attach to the current message.  
![](images/_page_225_Picture_2.jpeg)  
**Customize the Choose dialog title to reflect the task (if the dialog is not a sheet).** By default, the dialog's title is "Choose." If, for example, the command that displays the dialog is Choose Picture, the dialog should be titled "Choose Picture." If it's helpful, also change the Choose button to something more specific.  
<span id="page-225-0"></span>**Considerincluding a pop-up menu that allows users to filterthe types of files that appearin the list.** Display items that don't meet the filtering criteria as dimmed. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an All Applicable Files item, but it does not have to be the default.  
#### The Print and Page Setup Dialogs  
Users expect most documentsto be printable, or to include a printable version. OS X providesstandard dialogs that your app can display so that users can have a consistent printing experience in every app they use.  
The Print dialog isfocused on printing the current document, but it also includesfeaturesthat can be provided by individual apps and by printer modules. The Page Setup dialog gives users a way to set the scaling and orientation options for a document, based on the intended output paper size and the printer.  
By default, the Print dialog appears in its minimal form (shown here in the dialog attached to a TextEdit document). Users can get additional functionality in the expanded Print dialog by clicking Show Details.  
![](images/_page_226_Picture_3.jpeg)  
In the expanded Print dialog, user options are provided via the features pop-up menu, which displays panes that are drawn and controlled by printing dialog extensions(PDEs). PDEs are provided by the operating system, printer modules, and apps. Apple provides a number of printing panes. In the expanded Print dialog shown here, you can see the "Print header and footer" and "Rewrap contentsto fit page" optionsthat TextEdit provides.  
![](images/_page_227_Picture_2.jpeg)  
You might want to provide custom print panes that give users options that are relevant to the types of content your app handles. For example, Contacts helps users print their contact information in different styles, such as mailing label, envelope, and list. Here are some specific guidelines to keep in mind if you implement custom printing features:  
- Choose a menu item name that doesn't conflict with menu items already in the features pop-up menu, and that accurately describesthe content of the pane. For an app, the menu item should be the app name.
- Make sure the features you implement are appropriate for your app. For example, an option to print in reverse order should be provided by the operating system, not by your app. (Implementing this feature requires the app to know the hardware's capabilities.)
- Make interdependencies among options clear to users. For example, if a userselects double-sided printing, the option to print on transparencies should become unavailable.  
- Separate more advanced features from frequently used features. When the user chooses to display the advanced features, there should be an "advanced options" title above the advanced controls.
- When appropriate, show users what effect their choices will have. For example, a thumbnail image that shows the effect of changing a tone control helps users determine desired settings.
- Save a user's printing preferences for a document, at least while the document is open, and provide a way for users to save custom settings.  
If you think users would appreciate being able to set printing attributes for different printers or different paper sizes, it makes sense to provide a Page Setup dialog in your app. Be sure to save the settings that users make in this dialog with the document. Below, you can see the Page Setup dialog that TextEdit provides.  
![](images/_page_228_Picture_5.jpeg)  
#### <span id="page-228-0"></span>Find Windows  
A Find window is a modeless dialog that opensin response to the Find command and that provides an interface for specifying items to search for.  
Find windows can be useful in document-creation apps, because users can use one Find window to search for a term in several different open documents. If it makessense in your UI, however, you can offer find functionality in a scope bar. A scope bar is attached to a window and provides both search and filtering capabilities to users. For more information about scope bars and how to use them in your app, see "Using a Scope Bar to [Enable](#page-184-0) [Searching](#page-184-0) and Filtering" (page 185).  
#### <span id="page-229-0"></span>Save Dialogs  
Users expect to be able to specify a title and save location when they choose to save a document for the first time. To perform the initial save, users expect to see the standard Save dialog.  
**Note:** As much as possible, you want help users stop worrying about the save state of their content. In particular, you want them to stop thinking that they must continually choose File > Save in order to avoid losing their work.  
Although users see a Save dialog the first time they want to name and place their document, they should seldom—if ever—see a Save dialog while they continue to work on the document.  
The Save dialog hastwo states: minimal (also known as collapsed) and expanded. Clicking the disclosure button toggles between these states. For example, in the minimal Save dialog (shown here displayed by TextEdit), you can see the closed disclosure button to the right of the document title.  
![](images/_page_229_Picture_7.jpeg)  
The minimal Save dialog contains these elements:  
- The Save As text field in which users enter the document name. Expert users can enter pathnames by pressing Command-Shift-G. (Note that the pathname separator is the "/" character.)
- The Where pop-up menu, which contains mounted volumes, folders in the Finder sidebar, and Recent Places (which are the five most recent folders the user opened or saved documents to).
- A Save button (this is the default button).
- A Cancel button, which dismisses the dialog and returns the app to its previous state.
- A disclosure button. Clicking it displays the expanded Save dialog. (For more information about how to use disclosure buttons, see ["Disclosure](#page-288-0) Button" (page 289).)
- An optional accessory view, which can contain information such as text encoding settings. (In general, the accessory view should not be necessary.)  
The expanded Save dialog gives users a broader view of the file system than they get in the minimal Save dialog's Where pop-up menu. For example, the expanded TextEdit Save dialog displaysthe browsable file-system view.  
![](images/_page_230_Picture_9.jpeg)  
In addition to the items in the minimal Save dialog, the expanded Save dialog includes the following:  
- Back and forward buttons to navigate back and forth between selections made in the list or column view.
- A source list that mirrors the Finder sidebar.
- Options for navigating the file system.
- A File Format (or Format) pop-up menu, which displays a list of file formatsfrom which the user can choose.
- A New Folder button, which displays an app-modal dialog that asks the user to name the new folder, and then creates it.
- A "Hide extension" checkbox, which allows the user to control whether or not the filename's extension (.jpg, for example) is visible.  
In addition to the Save dialog, a document-based app can display the close confirmation save dialog. The close confirmation save dialog (shown when users close a document window that contains data that has never been saved) has the same minimal and expanded states as the standard Save dialog. For example, TextEdit displays the close confirmation save dialog when the user closes a new document window with unsaved changes.  
![](images/_page_231_Picture_8.jpeg)  
As with the standard Save dialog, the close confirmation save dialog includes a disclosure button to the right of the Save As text field. Clicking this button expands the dialog to show a similar browsable file system view. The differences between the close confirmation save dialog and the standard Save dialog are due to the fact  
that it's unclear whether the user intends to discard their work. For this reason, the text at the top of the dialog explains why it has appeared, and the Don't Save button at the bottom of the dialog allows the user to decline to save their work.  
There are a few ways in which you can customize a Save dialog so that it provides a better user experience. Keep the following guidelines in mind as you customize the save dialogs your app displays.  
**Specify a reasonable defaultlocation.** The default location appearsin the Where pop-up menu (in the minimal Save dialog) and in the Finder view (in the expanded Save dialog). Typically, the default location is one of the predefined folders in the user's home folder. If the user selects a different folder, make sure you remember the user's selection so that it appears the next time the dialog is displayed.  
**Allow users to choose whether to view the file extension.** The "Hide extension" checkbox should be selected as the default (that is, filename extensions should not appear in user-visible filenames unless the user requests them). If the user changes the state of the checkbox for a particular document, the next new document should match the last user-selected state, even after the user quits and reopens the app. The filename in the Save As field updates in real time as the checkbox is selected or deselected.  
**Display the default new document name before users save the document for the first time.** In general, this should be "untitled." In the Save As field, display the default name as selected so that users can easily replace it with a custom name. If the user has chosen to make the filename extension visible, the extension is not selected.  
**Display custom UI elements below the location-selection elements.** In the minimal Save dialog, custom UI elements go between the Where pop-up menu and the buttons at the bottom of the dialog. In the expanded Save dialog, custom elements go between the file-system browser and the buttons at the bottom of the dialog.  
<span id="page-232-0"></span>**Note:** In default keyboard navigation mode, pressing Tab in the expanded Save dialog shifts the keyboard focus from the Save As text field to the source list, to the visible columns, and then back to the text field.