<!-- Chunk 188 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 1484 -->
iOS makes available many of the standard buttons users see in toolbars and navigation bars. These buttons, shown in [Table](#page-135-1) 7-2 (page 136), are available in two styles, each of which is appropriate for the specific usages described here:  
- **Bordered style**—For example, the Add button in the navigation bar of the Contacts app on iPhone uses bordered style. This style is suitable for both navigation bars and toolbars.
- **Plain style**—For example, the Compose button in the Mail toolbar uses plain style. This style is suitable for toolbars only. In fact, if you specify the plain style for a button in the navigation bar, it is converted to the bordered style.  
As with all system-provided buttons, you should avoid using the buttons described in Table 7-2 to represent actions other than those for which they are designed. In particular, avoid choosing a button based on its appearance, without regard for its documented meaning. For a discussion of the reasons why it's important to use these icons correctly, see "Use UI Elements [Consistently"](#page-54-1) (page 55).  
<span id="page-135-1"></span>To find out which symbol names to use to specify these buttons, see the documentation for UIBarButtonSystemItem in *UIBarButtonItem Class Reference*.  
**Table 7-2** Standard buttons available for toolbars and navigation bars (plain style)  
| Button | Name      | Meaning                                                                       |
|--------|-----------|-------------------------------------------------------------------------------|
|        | Action    | Open an action sheet that allows users to take an application-specific action |
|        | Camera    | Open an action sheet that displays a photo picker in camera mode              |
|        | Compose   | Open a new message view in edit mode                                          |
|        | Bookmarks | Show application-specific bookmarks                                           |
|        | Search    | Display a search field                                                        |
|        | Add       | Create a new item                                                             |  
| Button | Name        | Meaning                                                                         |
|--------|-------------|---------------------------------------------------------------------------------|
|        | Trash       | Delete current item                                                             |
|        | Organize    | Move or route an item to a destination within the application, such as a folder |
|        | Reply       | Send or route an item to another location                                       |
|        | Stop        | Stop current process or task                                                    |
|        | Refresh     | Refresh contents (use only when necessary; otherwise, refresh automatically)    |
|        | Play        | Begin media playback or slides                                                  |
|        | FastForward | Fast forward through media playback or slides                                   |
|        | Pause       | Pause media playback or slides (note that this implies context preservation)    |
|        | Rewind      | Move backwards through media playback or slides                                 |  
In addition to the buttons shown in Table 7-2, you can also use the system-provided Edit, Cancel, Save, Done, Redo, and Undo buttons shown in Table 7-3 to support editing or other types of content manipulation in your application.  
<span id="page-136-0"></span>To find out which symbol names to use to specify these buttons, see the documentation for UIBarButtonSystemItem in *UIBarButtonItem Class Reference*.  
**Table 7-3** Bordered action buttons for use in navigation bars and toolbars  
| Button | Name   | Meaning                                                                         |
|--------|--------|---------------------------------------------------------------------------------|
|        | Edit   | Enter an editing or content-manipulation mode                                   |
|        | Cancel | Exit the editing or content-manipulation mode without saving changes            |
|        | Save   | Save changes and, if appropriate, exit the editing or content-manipulation mode |
|        | Done   | Exit the current mode and save changes, if any                                  |
|        | Undo   | Undo the most recent action                                                     |
|        | Redo   | Redo the most recent undone action                                              |  
The buttons listed in Table 7-3 are suitable for both navigation bars and toolbars, and are available in the bordered style only. If you specify the plain style for one of these buttons, it is converted to the bordered style.  
In iOS 4 and later, you can use the system-provided page curl button in a toolbar (for more information, see the documentation for UIBarButtonSystemItemPageCurl in *UIBarButtonItem Class Reference*). The page curl button is not available for use in a navigation bar.  
![](images/_page_137_Picture_4.jpeg)  
The page curl button allows you to give users a way to curl up the bottom corner of a screen to see information underneath. For example, Maps allows people to lift the lower-right corner of a map view to access buttons that manipulate the map.  
**Don't use the page curl button to flip the screen**. If you need to flip the screen, use the Info button instead (for more information about the Info button, see "Info [Button"](#page-125-1) (page 126)). Also, make sure that some of the curled-up page isstill visible onscreen to emphasize the temporary nature of the action of flipping the screen. If the upper page disappears, the page curl becomes too much like a full-screen transition, and users lose their context.