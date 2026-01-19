<!-- Chunk 135 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 1102 -->
iPhone OS makes many of the standard buttons users see in toolbars and navigation bars available to you. These buttons, shown in [Table](#page-124-0) 10-1 (page 125), are available in two styles, each of which is appropriate for the specific usages described here:  
- Bordered style—for example, the Add button in the Phone Contacts navigation bar. This style is suitable for both navigation bars and toolbars.
- Plain style—for example, the Compose button in the Mail toolbar. This style is suitable for toolbars only. In fact, if you specify the plain style for a button in the navigation bar, it will be converted to the bordered style.  
As with allsystem-provided buttons, you should avoid using the buttons described in Table 10-1 to represent actions other than those for which they are designed. In particular, avoid choosing a button based on its appearance, without regard for its documented meaning. See "Using [System-Provided](#page-122-1) Buttons and Icons" (page 123) for a discussion of the reasons why it's important to use these icons correctly. (Information on symbol names and availability for these buttons is available in documentation for UIBarButtonSystemItem.)  
<span id="page-124-0"></span>**Table 10-1** Standard buttons available for toolbars and navigation bars (shown in the plain style)  
| Button | Meaning                                                                         | Name        |
|--------|---------------------------------------------------------------------------------|-------------|
|        | Opens an action sheet that allows users to take an application-specific action  | Action      |
|        | Opens an action sheet that displays a photo picker in camera mode               | Camera      |
|        | Opens a new message view in edit mode                                           | Compose     |
|        | Show application-specific bookmarks                                             | Bookmarks   |
|        | Display a search field                                                          | Search      |
|        | Create a new item                                                               | Add         |
|        | Delete current item                                                             | Trash       |
|        | Move or route an item to a destination within the application, such as a folder | Organize    |
|        | Send or route an item to another location                                       | Reply       |
|        | Stop current process or task                                                    | Stop        |
|        | Refresh contents (use only when necessary; otherwise, refresh automatically)    | Refresh     |
|        | Begin media playback or slides                                                  | Play        |
|        | Fast forward through media playback or slides                                   | FastForward |
|        | Pause media playback or slides (note that this implies context preservation)    | Pause       |
|        | Move backwards through media playback or slides                                 | Rewind      |  
In addition to the buttons shown in Table 10-1, you can also use the system-provided Edit, Cancel, Save, and Done buttons shown in Table 10-2 to support editing or other types of content manipulation in your application. (Information on symbol names and availability for these buttons is available in documentation for UIBarButtonSystemItem.) These buttons are suitable for both navigation bars and toolbars, and are available in the bordered style only. If you specify the plain style for one of these buttons, it will be converted to the bordered style.  
<span id="page-125-1"></span>**Table 10-2** Bordered action buttons for use in navigation bars  
| Button | Meaning                                                                         | Name   |
|--------|---------------------------------------------------------------------------------|--------|
|        | Enter an editing or content-manipulation mode                                   | Edit   |
|        | Exit the editing or content-manipulation mode without saving changes            | Cancel |
|        | Save changes and, if appropriate, exit the editing or content-manipulation mode | Save   |
|        | Exit the current mode and save changes, if any                                  | Done   |