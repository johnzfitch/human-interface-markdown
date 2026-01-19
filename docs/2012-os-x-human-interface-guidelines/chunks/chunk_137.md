<!-- Chunk 137 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 3457 -->
Sometimes you need to provide the user with additional information or functionality in a dialog, but you don't want to display it all the time. To do this, you use one of the disclosure controlsto expand the dialog and reveal the additional information or capability to the user.  
**Use a disclosure button to provide additional choices in a dialog.** In particular, the disclosure button is the appropriate choice when the additional choices are directly related to selections that are offered in a pop-up or command pop-down menu in a dialog. When users click the disclosure button the dialog expands to reveal selectionsin addition to those listed in the pop-up or command pop-down menu. (For more information about how to use a disclosure button in your dialog, see ["Disclosure](#page-290-0) Button" (page 291).)  
**Use a disclosure triangle to reveal details that elaborate on the primary information in a dialog.** When users open the disclosure triangle the dialog expands, revealing additional information and, if appropriate, extra functionality. (For more information about how to use a disclosure triangle in your dialog,see ["Disclosure](#page-289-0) [Triangle"](#page-289-0) (page 290).)  
**Respond appropriately when users can resize a dialog that contains columns of data.** If users can resize a dialog that displays columns (such as the Open dialog), the columns should grow and additional columns should appear. All other elements should remain the same size and be anchored to the right, center, or left side of the dialog.  
#### <span id="page-218-0"></span>Dismissing Dialogs  
Users expect all the buttons at the bottom right of a dialog to dismiss the dialog. A button that initiates an action is furthest to the right. This rightmost button, called the **action button**, confirms the main point of the dialog. The Cancel button is to the left of the action button.  
Usually the rightmost button or the Cancel button is the **default button**. A default button has color and pulses to let the user know that when they press Return or Enter, the default button is activated.  
![](images/_page_218_Picture_7.jpeg)  
Follow the guidelines in this section to ensure that your dialogs look and behave as users expect.  
**Use a default button only if the user's most likely action is harmless.** The default button should represent the action that the user is most likely to perform *if* that action isn't potentially dangerous. Users sometimes press Return merely to dismiss a dialog, without taking the time to read its content, so it's crucial to ensure that the default button performs a harmless action.  
**Don't use a default button at all if the user's most likely action is dangerous**—for example, if it causes a loss of user data. When there is no default button, pressing Return or Enter has no effect; the user must explicitly click a button to dismiss the dialog. This guideline protects users from accidentally damaging their work by pressing Return or Enter without fully understanding the dialog's message. You can consider using a safe default button, such as Cancel, or not using a default button at all.  
**Don't use a default button if you use the Return key in the dialog's text fields.** Having two behaviors for one key can confuse users and make the interface less predictable. Also, users might press Return one too many times and dismiss the dialog (and activate the default button) without meaning to.  
**In general, include a Cancel button.** The Cancel button returns the computer to the state it was in before the dialog appeared. It means"forget I mentioned it." Also, make sure that the keyboard shortcut Command-period and the Esc (Escape) key are mapped to the Cancel button.  
**Ensure that Cancel undoes applied changes.** If your dialog incudes an Apply button that helps users see the effect of changes before committing to them, make sure that clicking Cancel undoes all of the applied changes. Cancel should never silently commit the changes the user previewed by clicking Apply. For more guidelines on using an Apply button, see ["Accepting](#page-216-0) and Applying User Input in a Dialog" (page 217).  
**Place a third button for dismissing the dialog to the left of the Cancel button.** If the third button could result in data loss—Don't Save, for example—try to position it at least 24 points away from the "safe" buttons (Cancel and Save, for example).  
**Place a button that affects the contents of the dialog itself in the left end of the dialog.** If there is no Help button, such a button should have its left edge aligned with the main dialog text; if there is a Help button, it should be placed to the right of the Help button. For example, the Help button isto the left of the Show Details button in the Print dialog, which expands the dialog to display more information about the print job.  
![](images/_page_219_Picture_6.jpeg)  
#### <span id="page-219-0"></span>Preferences Windows  
A preferences window is a modeless dialog that contains settings the user changes infrequently. In general, the user opens a preferences window to change the default way an app displays an item or performs a task, then closes the window, and expects the new settings to have taken effect. (For some guidance on how to provide a good preferences experience in your app, see ["Preferences"](#page-92-0) (page 93).)  
Often, a preferences window has a toolbar that contains items that function as pane switchers. When the user clicks an item in this type of toolbar, the content area of the preferences window switches to display a different view, called a **pane**. This design is useful for apps that need to provide multiple settings in each of several different categories. For example, the Safari preferences window contains a toolbar that allows user to choose among categories of settings, such as bookmarks, appearance, and RSS.  
![](images/_page_220_Picture_2.jpeg)  
**Don't enable customization of a pane-switcher toolbar in a preferences window.** A pane-switcher toolbar in a preferences window does not provide a shortcut to frequently used commands, but instead acts as a convenient way to group settings. If users customize thistype of toolbar, they might forget that hidden settings are still available. For the same reason, it makes sense to disable the ability to hide the toolbar in a preferences window, too.  
**Maintain the selected appearance of an item in a pane-switcher toolbar.** When the user clicks an item in a pane-switcher toolbar, the window displays a different pane. It's important to indicate which item is currently selected by maintaining the item's selected appearance. For example, in the RSS pane of the Mail preferences window, you can see the background highlighting that indicates which toolbar item is the active one.  
![](images/_page_221_Picture_2.jpeg)  
**Don't allow resizing or include active minimize or zoom buttons in a preferences window.** Remember that preferences windows are intended to give users a place to make occasional adjustments to the way an app behaves, so there should be no need for a preferences window to be resized or to remain open for a long time.  
**Use the title of the current pane to title the preferences window.** The preferences window title should be the same as the title of the currently selected pane even if you don't use a pane-switcher toolbar to change panes. (Note that if your preferences window does not contain multiple panes, its title should be "*App Name* Preferences".) In addition, a changeable-pane preferences window should remember which pane the user selected the last time the window was open.  
<span id="page-221-0"></span>**Use the standard menu item and keyboard shortcut to open your preferences window.** Users expect most apps to include a Preferences command in the app menu. In addition, most users expect to be able to use the Command-comma keyboard shortcut to open an app's preferences window.  
#### The Open Dialog  
The Open dialog gives users a consistent way to find and open an item in an app. Its appearance varies slightly depending on whether or not the app uses the iCloud Open dialog.  
If your app is document based and iCloud enabled, it has an iCloud Open dialog that opens in its own window. Other apps have an Open dialog that is app modal, which means that users can't interact with the app until they dismiss the dialog, although they can switch to other apps.  
The iCloud Open dialog contains these elements:  
● In the title bar: Tabs for iCloud and On My Mac, the app's title—for example, "Preview"—and a search field  
● In the bottom bar: A Share menu, a thumbnail or list view for navigating the file system, and a Cancel and Open buttons  
You can see most of the required elements in the iCloud Open dialog for Preview in iCloud.  
![](images/_page_222_Picture_3.jpeg)  
The On My Mac tab replaces the window body contents with a source list that mirrors the Finder sidebar as shown here:  
![](images/_page_223_Picture_2.jpeg)  
The Open dialog for non-document-based apps contains these elements:  
- The title, "Open"
- In the tool bar: Back and forward buttons, different views for navigating the file system, a pop-up menu that contains common places a user might save things and Recent Places (the five most recent folders the user opened or saved documents to), and a search field
- In the window body: A source list that mirrors the Finder sidebar
- In the bottom bar: Cancel and Open buttons (the Open button is the default button)
- The ability for expert users to specify a pathname by pressing Command-Shift-G (note that the pathname separator is the slash (/) character)  
You can see most of the required elements in the Open File dialog for Safari.  
![](images/_page_224_Picture_2.jpeg)  
You can extend the Open dialog as appropriate for your app. For example, the TextEdit Open dialog contains an additional section that allows users to specify different encodings.  
![](images/_page_224_Picture_4.jpeg)  
The following guidelines help you use and customize an Open dialog appropriately.  
**As much as possible, use the Open command to mean "open," and not "act upon."** The Open dialog is best suited to help usersfind an item to open in your app. If you need to help usersfind itemsto use in an app-specific task, it's generally better to use a Choose dialog instead (for guidance on using a Choose dialog, see ["The](#page-225-0) [Choose](#page-225-0) Dialog" (page 226)).  
**Make sure users can use the Open command to display the Open dialog.** Users expect the Open command to display an Open dialog. Contrast this with the Choose dialog, which can be displayed by different commands in different apps. It's also a good idea to provide the standard Command-O keyboard shortcut to display the Open dialog, because most users are accustomed to it.  
**Specify a reasonable default location.** For the iCloud Open dialog, iCloud is the default location. You should not change this behavior. See "iCloud [Storage"](#page-70-1) (page 71) for more information.  
Otherwise, the default location is typically one of the predefined folders in the user's home folder. If the user selects a different folder, make sure you remember the user's selection so that it appears the next time the dialog is displayed.  
**Considerincluding a pop-up menu that allows users to filterthe types of files that appearin the list.** Display items that do not meet the filtering criteria as dimmed. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an All Applicable Files item, but it does not have to be the default item.  
**Include an Open Recent command to accompany the Open command.** The Open Recent command allows users to reopen recently opened documents without using the Open dialog.  
<span id="page-225-0"></span>**Extend the functionality oftheOpen dialog, if appropriate.** For example, it's a good idea to support document preview so that users can be sure they're opening the document they intend. In addition, you can enable multiple selection if your app allows more than one document to be opened at one time.  
#### The Choose Dialog  
A Choose dialog gives users a consistent way to select an item as the target of a task. An app can have more than one Choose dialog, but only one can be open at a time.  
A Choose dialog:  
- Can be opened by various commands
- Can support multiple selection
- Supports document preview
- Can be resized  
For example, Calendar displays a choose dialog that allows users to choose a calendar to import.  
![](images/_page_226_Picture_2.jpeg)  
**Note:** Recent Places does not record folders that users select in Choose dialogs.  
The following guidelines help you use a Choose dialog appropriately in your app.  
**Use a sheet for the Choose dialog when the chosen items are specific to the document.** For example, Mail displays a Choose dialog in a sheet to help users to find items to attach to the current message.  
![](images/_page_227_Picture_2.jpeg)  
**Customize the Choose dialog title to reflect the task (if the dialog is not a sheet).** By default, the dialog's title is "Choose." If, for example, the command that displays the dialog is Choose Picture, the dialog should be titled "Choose Picture." If it's helpful, also change the Choose button to something more specific.  
<span id="page-227-0"></span>**Considerincluding a pop-up menu that allows users to filterthe types of files that appearin the list.** Display items that do not meet the filtering criteria as dimmed. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an All Applicable Files item, but it does not have to be the default.