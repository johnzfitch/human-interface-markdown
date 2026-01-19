<!-- Chunk 95 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 1082 -->
iOS provides many of the standard toolbar and navigation bar buttons that are used in the built-in apps. To learn how to design custom bar icons, see "Bar [Button](#page-217-0) Icons" (page 218). Items in the toolbar and navigation bar can be tinted using the tintColor property.  
To find out which symbol names to use to specify the buttons described in Table 35-1, see the documentation for UIBarButtonSystemItem in *UIBarButtonItem Class Reference* .  
**Important:** As with all standard buttons and icons, it's essential that you base your usage of a button on its semantic meaning, not on its appearance. This will help your app's UI make sense even if the button associated with a specific meaning changes its appearance.  
<span id="page-148-0"></span>**Table 35-1** Standard buttons available for toolbars and navigation bars  
| Button | Name      | Meaning                                                                                                                                               |
|--------|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
|        | Share     | Open<br>an<br>action<br>sheet<br>that<br>listssystem-provided<br>and<br>app-specific<br>services<br>that<br>act<br>on<br>the<br>specified<br>content. |
|        | Camera    | Open<br>an<br>action<br>sheet<br>that<br>displays<br>a<br>photo<br>picker<br>in<br>camera<br>mode.                                                    |
|        | Compose   | Open<br>a<br>new<br>message<br>view<br>in<br>edit<br>mode.                                                                                            |
|        | Bookmarks | Show<br>app-specific<br>bookmarks.                                                                                                                    |
|        | Search    | Display<br>a<br>search<br>field.                                                                                                                      |
|        | Add       | Create<br>a<br>new<br>item.                                                                                                                           |
|        | Trash     | Delete<br>current<br>item.                                                                                                                            |
|        | Organize  | Move<br>or<br>route<br>an<br>item<br>to<br>a<br>destination<br>within<br>the<br>app,<br>such<br>as<br>a<br>folder.                                    |
|        | Reply     | Send<br>or<br>route<br>an<br>item<br>to<br>another<br>location.                                                                                       |
|        | Refresh   | Refresh<br>contents<br>(use<br>only<br>when<br>necessary;<br>otherwise,<br>refresh<br>automatically).                                                 |
|        | Play      | Begin<br>media<br>playback<br>or<br>slides.                                                                                                           |  
| Button | Name        | Meaning                                                                                                     |
|--------|-------------|-------------------------------------------------------------------------------------------------------------|
|        | FastForward | Fast<br>forward<br>through<br>media<br>playback<br>or<br>slides.                                            |
|        | Pause       | Pause<br>media<br>playback<br>or<br>slides<br>(note<br>that<br>this<br>implies<br>context<br>preservation). |
|        | Rewind      | Move<br>backwards<br>through<br>media<br>playback<br>or<br>slides.                                          |  
In addition to the buttons shown in Table 35-1, you can also use the system-provided Edit, Cancel, Save, Done, Redo, and Undo buttonsto support editing or other types of content manipulation in your app. The appearance of each of these buttons is provided by its text title. To find out which symbol names to use to specify these buttons, see the documentation for UIBarButtonSystemItem in *UIBarButtonItem Class Reference* .  
Finally, you can also use the system-provided Info button in a toolbar:  
![](images/_page_149_Picture_4.jpeg)